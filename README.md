# Adaptive-PID-for-BLDC-Speed-Control
This project's major is to show how to design and implement an adaptive PID (APID) for your power system. The adaptive PID design compares the reference speed with the actual speed of BLDC. The output of PID then feeds a controlled voltage source attached to a universal 3-phase bridge, the bridge that is connected to a BLDC motor.
The torque is constant during the first 0.2 sec of simulation; then, it is changed abruptly to 10N to examine the ability of APID speed control despite torque variation.

The APID model is adapted from the following article:
Self-tuning of PID controllers by adaptive interaction ( https://ieeexplore.ieee.org/abstract/document/879256/)

You might also find my article for another practical example:
Online Adaptive Power Factor Correction Controller for DC-DC Converters ( https://digital-library.theiet.org/content/conferences/10.1049/cp.2014.1495 )

Please do not hesitate to contact me if you need any more information.

Cheers,
Mahdi
