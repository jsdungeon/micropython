# micropython
First steps with micropython using ESP32 and ESP8266 micro controller

I am playing around with a M5STACK ESP32 based microcontroller. You can read more about it here: https://github.com/m5stack/M5Stack
There is a forum as well: http://forum.m5stack.com/category/4/products

Actually I am displaying text on the integrated screen.
The next step is how to use the keyboard.

I am using Microsoft code with some extensions to directly code on the device or to write a script and run it on the device.
It is connected to my laptop (Win10 64) via a USC-C cable. It is necessary to add the driver so that Win is recognizing the device.
The communication with MS code is done via USB -> COM. It is necessary to check at which COMP port the device has been recognised by windows.
Before you can use micropython you have to flash it to the M5STACK.
I will try to add more details about this in the near future.

CP210x USB to UART Bridge VCP Drivers https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
DO NOT download the univeral drive!
Use this one: Download for Windows 7/8/8.1/10 (v6.7.5)


But don't forget: I'm a noob with this ;-)

Cheers & have fun!
