# PiDeviceNet


I made this project to use Raspberry Pis to control various devices around my home. This includes relays, VRMs, LCDs, and various sensors. The idea here is to have a main Pi that handles the communication to several other Pis to relay commands and manage device control across the home. This is a work in progress and just something I'm playing with in my free time.

As I continue working, I'm realizing that this could potentially be a useful tool for anyone to use as a drop-in solution for their own device control using multiple raspberry pies. I'll be making functionality generic and adaptable for anyone to make use of this as I move forward to help with this. I plan to release this project as package that anyone can add to their projects and get up and running really quickly and easily. 


<br/>
Raspberry Pi models supported:

* Raspberry Pi Models: A, B (revisions 1.0 and 2.0), A+, B+, 2, 3, 3+, 3 A+, Compute Module 3, Zero, Zero W.
* Raspberry Pi 4 is **NOT** supported at this time! (There's a memory mapping issue for i2c and pwm access that is present in the BCM base library. This is a known issue and should be solved soon.)

<br/>

Controllable devices currently supported:

* Relays
* i2c LCDs (16x2, 16x4, 20x2, 20x4 fully supported!)

<br/>

Devices currently in developement/testing:

* PWM voltage regulators
* Temperature and humidity sensors (DHT sesnors)

<br/>

More devices and features that are coming soon:

* More LCD sizes and interface types
* Button and switch input
* Belkin Wemo device support
* LED indication output
* Speakers (good for alarms or notification tones)
* Proximity sensors
* Voice recognition for commands
* OpenHab integration for phone control support using Siri and Google Assistant
* Desktop GUI control program for Windows and Mac

<br/>
These features toward the bottom are further out, but I do plan to add them when I can. My goal is to make this a powerful, yet really easy to use solution that anyone with some raspverry pies can use! Any feedback or requests that you have are appreciated, so please feel free to reach out!
