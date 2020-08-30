# PXN-2119 for Microsoft Flight Simulator (FS2020)
Peripheral Control Settings for [PXN-2119](http://www.e-pxn.com/products/arcade-stick/pxn-2119) HOTAS on Microsoft Flight Simulator

![pxn-2119-fs2020_cover](https://user-images.githubusercontent.com/9207205/91651241-dbc39280-eabc-11ea-9c29-29563ef03a79.jpg)

The PXN-2119 is a poor simmer's HOTAS. It's the only HOTAS available in my region as of today. Regardless, it got me into MS Flight Simulator again after nearly two decades of absence. The last Flight Simulator I played was [2004: A Century of Flight](https://en.wikipedia.org/wiki/Microsoft_Flight_Simulator_2004:_A_Century_of_Flight). I sucked at the game back then, I still suck at it now.

In FS2020, the PXN-2119 has no name. It's probably because the Windows 10 driver for it is not in English. I didn't find a way, in-game or otherwise, to export the controls to a file. So, this repo will have to be in the form of a documentation for now.

# How To Use This Repository
This repository contains files in Markdown format. Each one has button and axis assignments for a particular aircraft. Simply click on a file for the aircraft you like, then use it as a reference for your in-game control options in FS2020 > Options > Controls. You can search by Name or Input within the FS2020 control options.

If you're just getting started like me, you might want to check out the controls for the Cessna 152. It's the aircraft used in the training lessons.

![pxn2119-cessna152_menu](https://user-images.githubusercontent.com/9207205/91654032-4df5a080-ead8-11ea-87d2-9b3e58267865.jpg)

# In-game Controls
In FS2020, you can assign controls for each aircraft via the Preset Manager. Here's a sample workflow:

1. Go to FS2020 > Options > Controls
2. From there, click on the unknown peripheral to highlight it.
3. Click on PRESET MANAGER and assign a name to it. For example, name it _PXN-2119-CESSNA-152_.
4. In the FILTER setting, set it to ALL instead of ESSENTIALS.
5. Search for a particular control name in the SEARCH filter.
6. Use the files contained in this repository as a reference.

![pxn2119_preset_manager](https://user-images.githubusercontent.com/9207205/91654131-028fc200-ead9-11ea-8033-e2629cbb9471.jpg)

## PXN-2119 Buttons and Axes
The PXN-2119 has 16 buttons, 6 axes, and 2 POV hats. The Throttle base is connected to the Joystick base via a PS2 connector (KB/mouse connector from the olden days). Then, the Joystick base is connected to the PC via USB:

![pxn2119_control_labels](https://user-images.githubusercontent.com/9207205/91651736-d9643700-eac2-11ea-996f-206442c51563.jpg)

**Axes**
1. Aileron axis = Joystick main control for flying
2. Rudder axis = Twist Joystick twist left or right; can be used for taxiing
3. Slider axis = behind the Joystick; can be used for flaps
4. Throttle axis = used to control RPM speed during take-off and when airborne
5. Small rotary axis = lower right of throttle
6. Large rotary axis = upper right of throttle; can be used to control mixture/turn off engine

**Buttons**
1. Trigger = Button 1; can be used for the main brake
2. Lower Trigger = Button 2; can be used for the parking brake
3. Buttons 3-6 = can be used to control elevator trim (3-4) and seat height (5-6)
4. Buttons 7-12 = located at the left of the Joystick base; assign anything, such as the light toggle
5. Button 13 = on the lower right side of the throttle; can be a toggle for reverse thrust
6. Button 14 = can be used to toggle the landing gear
7. Buttons 15-16 = can be used to increase or decrease acceleration when taxiing

**POV Hats**
1. Joystick POV = can be used to control cockpit camera and external camera
2. Throttle POV = located above Button 16 on the throttle; no idea what it can be used for

***
_Credits:_

- [PXN Website](http://www.e-pxn.com) (_for the reference photos_)
- [Squirrel on YouTube](https://www.youtube.com/channel/UCSeb5KSN6BC1c0WwEjUzM_A)