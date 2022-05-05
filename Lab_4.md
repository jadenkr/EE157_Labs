# Magnetic Forces & Materials

Lab 4

Jaden Redhair 05/05/2022 EE157

# Summary
In this lab, we were able to understand a solenoid and how it worked. From the physical design to the electromechanical forces produced from it.

# Inductance vs. Frequency
So we can see here that when fully plunged, the inductance is really high but as frequency increases, it drops drastically. This is because there is hardly any airgap so the energy stored is larger. However, frequency lowers that inductance. In the fullt extended version, the inductance starts low and gradually decreases but not as drastically as when it is fully plunged. We are more interested in low frequency because we don't really ever send high frequency signals to drive a motor.


![Lab_4_FullyPlunged_10-10kHz](https://user-images.githubusercontent.com/72374334/166879796-a7a74dd5-71ed-40be-b4c5-5c1a20fccdf4.jpeg)

![Lab_4_FullyExtended_10-10kHz](https://user-images.githubusercontent.com/72374334/166879815-35f38a08-eb63-4e54-b2e2-f0e3d415921a.jpeg)

# L vs distance extended
The line here is pretty smooth and what we are seeing is that as distance increases, inductance decreases since the airgap is getting longer and longer.

![image](https://user-images.githubusercontent.com/72374334/166880492-5424942c-70d7-428e-959e-aea57e32f4ed.png)

# Force as a function of position
When we think about the force vs the position, we see that as we go further away, inductance decreases. This means that as we increases the distance, force decreases as well.
When we felt the solenoid and tried to push it back together at 12V, we felt that it had a more force as we slowly tried to let it fully extend.

# Integral of Voltage vs Current Through the Coil
Here we have the plots for the integrated voltage vs current of the solenoid extended, plunged, and the ferrite inductor.

![Solenoid Extended-20Hz](https://user-images.githubusercontent.com/72374334/166883531-56c6cafd-ac90-42ed-8907-e36f82f43a31.png)
![Solenoid Extended-40Hz](https://user-images.githubusercontent.com/72374334/166883534-960e8bb4-59a2-4950-b19b-af606ee1ac32.png)
![Solenoid Extended-60Hz](https://user-images.githubusercontent.com/72374334/166883536-9018db83-681c-428c-86e6-77225cb1d603.png)
![Solenoid Extended-80Hz](https://user-images.githubusercontent.com/72374334/166883541-ee3901a9-9961-4c46-9b2d-7eeaa6eb9935.png)
![Solenoid Extended-100Hz](https://user-images.githubusercontent.com/72374334/166883543-b777fbc9-2c55-45c3-abd5-13fb5723ef31.png)
![Solenoid Extended-120Hz](https://user-images.githubusercontent.com/72374334/166883544-8f3c0436-03eb-4ecf-830d-753d16c2cf04.png)
![Solenoid-20Hz](https://user-images.githubusercontent.com/72374334/166883546-78a97757-d1f4-4cda-91ba-91a1d5def6dc.png)
![Solenoid-40Hz](https://user-images.githubusercontent.com/72374334/166883548-dbed2a34-31fa-4f30-90e3-9944347e7ca9.png)
![Solenoid-60Hz](https://user-images.githubusercontent.com/72374334/166883550-69d830c9-aa6f-4387-b768-e64a04768f28.png)
![Solenoid-80Hz](https://user-images.githubusercontent.com/72374334/166883553-8157d720-62e4-488d-bd31-1bc0026e9a11.png)
![Solenoid-100Hz](https://user-images.githubusercontent.com/72374334/166883555-7f6a401c-fb31-440f-9b9d-d89ef2d8d0fb.png)
![Solenoid-120Hz](https://user-images.githubusercontent.com/72374334/166883557-37d3a2ab-bafb-44ea-b6c1-d77302ebdab6.png)
![Ferrite Inductor-150Hz](https://user-images.githubusercontent.com/72374334/166883512-d46bc365-5bd0-4b34-a27e-61aa008b330e.png)
![Ferrite Inductor-200Hz](https://user-images.githubusercontent.com/72374334/166883518-ff4c81e9-fa87-43aa-8198-2b4404fa80e8.png)
![Ferrite Inductor-250Hz](https://user-images.githubusercontent.com/72374334/166883521-ec09b549-0ff1-4ce5-9991-c7fd10bf5355.png)
![Ferrite Inductor-300Hz](https://user-images.githubusercontent.com/72374334/166883522-4fd1e7f6-aebe-4d84-aa08-366b21a99382.png)
![Ferrite Inductor-350Hz](https://user-images.githubusercontent.com/72374334/166883524-faff7baa-662b-4478-aa94-428f4d881118.png)
![Ferrite Inductor-400Hz](https://user-images.githubusercontent.com/72374334/166883525-e1b216da-3bbb-4153-a633-b4a96d92e9c0.png)
![Ferrite Inductor-450Hz](https://user-images.githubusercontent.com/72374334/166883530-1cfc316a-e175-4d6a-bf88-94232c8a9a5e.png)

# B & H Curves
Now, we have the B-H curves plotted at different frequencies. This is when fully extended and fully plunged. When looking at the power losses, we notice that as we increase the frequency, the power losses decrease.

![B_H_Solenoid Extended-20Hz](https://user-images.githubusercontent.com/72374334/166884013-dc4c6a37-bc6f-4f86-bedb-b3754972dcc8.png)
![B_H_Solenoid Extended-40Hz](https://user-images.githubusercontent.com/72374334/166884028-aacf1b43-7736-45a1-9d20-ed14c98394a8.png)
![B_H_Solenoid Extended-60Hz](https://user-images.githubusercontent.com/72374334/166884033-f9d63246-b072-4ad2-a580-6fb0651b4de1.png)
![B_H_Solenoid Extended-80Hz](https://user-images.githubusercontent.com/72374334/166884042-f9ef9665-eec8-400a-973f-e9f8ac44745d.png)
![B_H_Solenoid Extended-100Hz](https://user-images.githubusercontent.com/72374334/166884050-d41a4ef5-63a8-4ba9-bfdf-876774325f7e.png)
![B_H_Solenoid Extended-120Hz](https://user-images.githubusercontent.com/72374334/166884056-38bcae13-6b00-46d5-a9c9-426f531a1854.png)
![B_H_Solenoid-20Hz](https://user-images.githubusercontent.com/72374334/166884061-24541b10-91c1-4540-a26d-410da92bdfa3.png)
![B_H_Solenoid-40Hz](https://user-images.githubusercontent.com/72374334/166884067-85fa8eaf-70ad-4eef-a9ff-2f08ed466664.png)
![B_H_Solenoid-60Hz](https://user-images.githubusercontent.com/72374334/166884072-e8c2607e-c9be-4d37-98bc-bbe92a5b89fc.png)
![B_H_Solenoid-80Hz](https://user-images.githubusercontent.com/72374334/166884077-c24383bd-6cc8-4b0d-bca4-b200b76d550e.png)
![B_H_Solenoid-100Hz](https://user-images.githubusercontent.com/72374334/166884083-c650ab0f-1d5e-4757-b651-4b895c4e03c5.png)
![B_H_Solenoid-120Hz](https://user-images.githubusercontent.com/72374334/166884088-4dccb63d-354d-48b6-86cb-bb4291de267e.png)

# Conclusions
What we learned in this lab was that solenoids are literally an E core inductor with a varying airgap that changes as the plunger is extended or plunged. That in a solenoid, the force increases as we have higher inductances.
