# Servo Control Report

Lab 6

Jaden Redhair 06/4/2022 EE157

# Summary
The purpose of the lab was to design our own PID controller to control a servo motor with op amps.

# Circuit Diagram
![IMG_0494](https://user-images.githubusercontent.com/72374334/171993252-75c9bc04-0116-4125-a7f9-d2cbba751b70.jpg)

# Our Design
In our design, we decided to switch the potentiometer and resitor of the integral portion. We did this so that we could better adjust the gain of the integrator. We also made sure our Kp stage had unity gain so that the potentiometer could adjust the gain more easily.


# Submission Items

1. I believe we set the frequency to 15kHz since that is a realtively low frequency. It allows for the opamps to keep up and it tends to be in the mid-range for op amp operation. I think the factors to consider in a PWM are the shape, switching frequency, and duty cycle.
2. We saw that the motor overcame friction at 300mV and it had a coil resitance of 5Ω so the current supplied was 0.06 Amps. This means that the power output was 18mW so the friction was 18mNm.
3. I was able to find that a gain of 120 allowed sustained oscillation. I then was able to calculate Kp = 0.00276, Ki = 0.1083, and Kd = 4.745e-5. ![Lab_6_Sub_03_Gain](https://user-images.githubusercontent.com/72374334/171994071-2e6d2401-eebd-41f3-9074-62c385b7342b.jpeg)

4. Scope Capture ![Lab_6_Sub_04_retry](https://user-images.githubusercontent.com/72374334/171994101-fc53f61d-74d5-4f36-b267-a2e072ca947e.jpeg)
5. I see here that there is overshoot
6. Scope Capture: We can see here that the cahnnel 2 is now lower in comparison to the waveform we saw in submission 4. ![Lab_6_Sub_06](https://user-images.githubusercontent.com/72374334/171994156-cc619885-bd09-4c2f-846f-0e1d797937a1.jpeg)

# Oscillating Video Time!
https://user-images.githubusercontent.com/72374334/171994374-bd2d639a-160a-4f2d-9b22-9620bf297c6e.mov

# Conclusion
In conclusion, we were able to get our servo motor working and could adjust the parameters. We learned alot about PID controllers and how to make it with op amps. We often got used to using a few lines of code for the PID and it was long but we came out with a better appreciation for hardware.

# Lab Review
I enjoyed this lab even though it took a considerable amount of time. I think after refining the wording and understanding in the lab handout, it would be more enjoyable. Also giving more instruction on adjusting the opamp gain. We had trouble trying to size the resitors and didn't know what gain to start out with. It wasn't until Aaron instructed us to use unity gain and have the potetiometer adjust it all for us. It was very relieving to get it working and see our motor do its job as a servo to determine postioning with feedback.
