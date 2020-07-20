# LILYGO_T-Wristband-testing

Source code of the template copied from https://github.com/TioRuben/TTGO-T-Wristband. 

## Flashing your code
Projects are meant to be build with PlatformIO. 
Every project contains `platformio.ini` file with preconfigured enviroments.

### Upload via wired connection
First of all, you need to open wristbands screen case.
Start opening from the side with charging pads as shown in image below.

<img src="_guide/img/wired_upload-1.jpg" alt="Wristband dissassembly 1" width="250"/> <img src="_guide/img/wired_upload-2.jpg" alt="Wristband dissassembly 2" width="250"/>

Now you need to gently pull PCB from its case at the side with RTC battery.

<img src="_guide/img/wired_upload-3.jpg" alt="PCB 1" width="250"/> <img src="_guide/img/wired_upload-4.jpg" alt="PCB 2" width="250"/>

On the back side of the primary board (side with the battery) open the FPC line connector.

<img src="_guide/img/wired_upload-5.jpg" alt="FPC 1" width="250"/> 

Connect daughter board with the FPC line to the primary board as shown on the third image.
Make sure, that FPC cable is oriented correctly (black side on top, side with visible contacts on the bottom).

<img src="_guide/img/wired_upload-6.jpg" alt="Daughter board" width="250"/> <img src="_guide/img/wired_upload-7.jpg" alt="FPC 2" width="250"/>

Plug FPC in and close connector's latch.

<img src="_guide/img/wired_upload-8.jpg" alt="FPC 3" width="250"/> <img src="_guide/img/wired_upload-9.jpg" alt="FPC 4" width="250"/>

Now connect daughter board to the computer with USB-C, or micro USB cable.

<img src="_guide/img/wired_upload-10.jpg" alt="USB" width="250"/> 

Your computer should immediately recognize your device and install drivers.
After successful driver installation you can start uploading your software.