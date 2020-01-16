# DellInspiron5567Hackintosh
My personal experience of installing Mac OS X Catalina on Dell Inspiron 15 5567.

Laptop Specs:

Cpu:Intel core i7-7500U

IGPU:Intel HD620

EGPU:Radeon R7 M445

Wifi adapter:Tp-link tl-wn725n v3

OS version:10.15.2

What's Working:
1-Graphics with QE/QI(Intel HD620 ofc)
2-Wifi on external usb adapter
3-Touchpad/Keyboard
4-Battery status
5-Sleep/Wake
6-Fn keys totally remapped.
7-Internal Speakers with 3.5 mm headphone input/Internal Mic.
8-Bluetooth.

What's not working:
1:Internal wifi.(Intel wifi is not supported in hackintosh)
2:Card Reader(Disabled in SSDT-UIAC)

DSDT/SSDT patching was done by following Rehabman's Guides on various threads and sites and also other threads needed to solve some issues.
N.B: I am using British-PC Keyboard Layout and modified VodooPS2Keyboard's according it(actually swaped two keys together only )so if you are using any other layout you have to do some modifying.

