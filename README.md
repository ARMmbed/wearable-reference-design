# Wearable Reference Design
Welcome to the Wearable Reference Design (WRD) main GitHub page. This page serves as an index to the WRD software framework, which is a collection of yotta modules. Each module is only responsible for a specific function but when put together by the yotta build system these modules transform into a highly portable application. 

Applications programmed using the WRD hardware abstraction API, and build on a supported target, will automatically adapt to the target platform and take advantage of any supported hardware features because of the yotta build system.

This flexibility enables rapidly prototyping new hardware peripherals simply by changing a single line in a JSON file. Similarly, new wearables can be build from scratch by combining supported components and peripherals into a new platform target.

#Example Applications
To highlight the flexibility and portability of the WRD, we have put together a set of example applications:

User interaction (buttons, touch interface, and graphics):
https://github.com/ARMmbed/wearable-reference-design-example-user-interface

Onboard communication:
https://github.com/ARMmbed/wearable-reference-design-example-message-center

#Partner Libraries
Below is a featured list of some of our contributing partners and their libraries:

* Myotest - Step counting library using 3-axis accelerometer data. Trial library available on yotta and an example application can be found here: https://github.com/ARMmbed/wearable-reference-design-example-myotest-step-counting
For more information visit: http://www.myotest.com

