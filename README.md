# LILYGO_T-Wristband-testing

Source code of the template copied from https://github.com/TioRuben/TTGO-T-Wristband. 

## Flashing your code
Projects are meant to be build with PlatformIO. 
Every project contains `platformio.ini` file with preconfigured enviroments.

### Upload via wired connection
First of all, you need to open wristbands screen case.
Start opening from the side with charging pads as shown in image below.

![Wristband dissassembly 1](/_guide/img/wired_upload-1.jpg) ![Wristband dissassembly 2](/_guide/img/wired_upload-2.jpg)

Now you need to gently pull PCB from its case at the side with RTC battery.

![PCB 1](/_guide/img/wired_upload-3.jpg) ![PCB 2](/_guide/img/wired_upload-4.jpg)

On the back side of the primary board (side with the battery) open the FPC line connector.

![FPC 1](/_guide/img/wired_upload-5.jpg)

Connect daughter board with the FPC line to the primary board as shown on the third image.
Make sure, that FPC cable is oriented correctly (black side on top, side with visible contacts on the bottom).

![Daughter board](/_guide/img/wired_upload-6.jpg) ![FPC 2](/_guide/img/wired_upload-7.jpg)

Plug FPC in and close connector's latch.

![FPC 3](/_guide/img/wired_upload-8.jpg) ![FPC 4](/_guide/img/wired_upload-9.jpg)

Now connect daughter board to the computer with USB-C, or micro USB cable.

![USB](/_guide/img/wired_upload-10.jpg)

Your computer should immediately recognize your device and install drivers.
After successful driver installation you can start uploading your software.