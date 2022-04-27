# Inductor Design and Characterization Report

Lab 3

Jaden Redhair 04/27/2022 EE157

# Summary
The purpose of the lab was to design and build an inductor with an inductance of +/- 200uH. We ended up with a ~204uH inductor with a 495-5421-ND core, 495-5366-ND bobbin, and 22 AWG wire. We then began to vary the frequency and observed how it affected inductance. Another parameter we tested was to add an auxiliary inductor to decouple the LCR meter measurement from the power supply. Overall, we learned how to design an inductor and analyze it.

# Procedure
1. Gather materials needed:
   - Chosen AWG Copper wire
   - Ferrite E core
   - Corresponding bobbin
   - X-Acto knife
   - Gapping material (Kapton tape)
   - Auxiliary Inductor
2. Calculate the correct values of the inductor given the selected components:
   - Calculate the energy stored in the inductor. Here we can assume all the energy is stored in the air gap.
   - Given the energy, we can calculate the volume of the air gap. Which then leads us to be able to calculate the length of the effective air gap. You would do this by dividing the volume by the cross-sectional area of the core.
   - Given the effective area, we can assume the actual airgap is half of that. We can do this because the two legs of the E core roughly equal the area of the center. So, we would simply divide the gap by 2 to account for the extra gapping. Then find a close enough object or layering's of Kapton to actually put in between the core pieces to measure out the gap.
   - Now, we can calculate for the number of turns given inductance is equal to the turns squared divided by the effective reluctance.
   - Finally, we can calculate the thickness wire gauge we can fit in the openings of the core while the bobbin is installed. We simply find the area of the window and divide that by the number of turns to get the gauge thickness we can use. Also, make sure to account for insulation so the effective window area is about 0.6 times the actual.
3. Now, we can gather the chosen materials and construct our inductor!
4. Lastly, measure your inductance and see how close you could get to 200uH and how it varies with frequency.

# Results
## Calculated Parameters
For my inductor, we calculated the following:
   - Energy stored in the air gap = 0.4 mJ assuming a 410 mT Bsat
   - Volume = 5.98 mm^3
   - Length of the gap = 0.093 mm or two pieces of ~50um Kapton tape
   - Number of turns = 31
   - Window area for wire gauge = 22.75 mm^2
   - Wire diameter = 0.0749 cm or ~22 AWG (0.0701 cm)
   - Wire Resistance = 61.1 mΩ

![IMG_6349](https://user-images.githubusercontent.com/72374334/165494235-56ff4e1e-5a54-4807-82b8-1c64112449b9.jpg)

## Plots
### Inductance varied by frequency:
![Lab 3 200uH Inductance](https://user-images.githubusercontent.com/72374334/165503878-3cf3a215-cf09-4eda-858a-690be7646405.jpeg)

### Inductance with the Auxiliary Inductor at Various Currents at 10kHz
#### 0 Amp
![Lab 3 0A](https://user-images.githubusercontent.com/72374334/165504069-75c2b4e5-2c85-4982-a7b1-a09d885ce98b.jpeg)

#### 1 Amp
![Lab 3 1A](https://user-images.githubusercontent.com/72374334/165504250-fefaae85-7813-4849-b846-068bb4c9b139.jpeg)

#### 2 Amp!
![Lab 3 2A](https://user-images.githubusercontent.com/72374334/165504264-c2cee8eb-06f8-4c64-9e67-5c8538e23783.jpeg)

#### 3 Amp
![Lab 3 3A](https://user-images.githubusercontent.com/72374334/165504295-d8bd9b64-f4ce-4b2d-a3b2-071ca36f54d1.jpeg)

### Inductance with the Auxiliary Inductor at Various Currents and Frequencies
#### 0 Amp
![Lab 3 0A Freq](https://user-images.githubusercontent.com/72374334/165504606-933dafac-2836-4b09-8b7a-02821d8d0ac8.jpeg)

#### 1 Amp
![Lab 3 1A Freq](https://user-images.githubusercontent.com/72374334/165504617-b1cc330d-f608-47f6-a7fc-ac2ded42e6c4.jpeg)

#### 2 Amp
![Lab 3 2A Freq](https://user-images.githubusercontent.com/72374334/165504627-335e03fb-a89a-41e2-9836-29714a1698b7.jpeg)

#### 3 Amp
![Lab 3 3A Freq](https://user-images.githubusercontent.com/72374334/165504632-c7880987-2877-4460-a161-1c7c6ce7c051.jpeg)

# Conclusions
### Losses
We can calculate the winding losses as the resistance of the wire multiplied by the current squared.
Winding losses = 0.24 W
Now we can also calculate the core losses which is the K1 constant * frequency * flux density * volume of the core
Core losses = 3.76mW
Total losses = 0.24376 W

We saw that in the lab the inductor heated up as we applied more current. We got higher losses since both the wire and core heated up. The other source of losses we encountered was with the air gap where heat dissipated as well. In comparison, we had more losses. The winding heated up to 90 degrees and this shows that the inductor does in fact lose more heat through winding losses than core losses.

### Did we meet specifications?
Yes, we met the specifications exactly. We had a 204uH inductance and the reason for the discrepancy lies in the number of turns being rounded up, the length of the airgap increasing to 0.1mm, and just rounding errors.

### Why Kapton Instead of Aluminum?
We use Kapton because it doesn't affect the airgap all too much if it was just free space. However, aluminum isn't magnetic so it wouldn't work well as an air gapping material. It has a low magnetic permeability so all it will do is heat up a lot in the inductor.
