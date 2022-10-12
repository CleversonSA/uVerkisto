# uVerkisto
An open source SBC based pocket PC computer.

# background
At 2000´s I was a hard user of PDAs and I´ve became a professional PDA developer (from 2004-2007) at Brazil. Of course, times changed and the smartphone has it fixed place in my personal and businnes usage, keeping my PDA usage just for nostaugia. Many years later, I´ve purchased a HP 200lx and finally my dream PDA, HP Jornada 720 (I still have those with my in very good shape and working condition). But, when the Rapsberry PI Zero was released, I realized that a such small full linux desktop could be the base to build a "modern version" of a PDA, just for fun or any other purpose.

After some failed build attempts from the past, like in this almost vintage video (https://www.youtube.com/watch?v=Mo7BqMrNIDs) I´ve gave up of a portable custom portable Linux.

But, years later, I´ve inspired by N-O-D-E (https://www.youtube.com/c/NODEtv) builds and decided to gave a new try. I´ve purchased a 3D printer and tried design a custom Pocket Linux PC, or, a little and compact cyberdeck. 

That´s why this repository exists.


# DISCLAIMER

This is an W.I.P. open source project, in APACHE 2.0 License, so if you want to build this, you have to ACCEPT THE RISKS BY YOURSELF! Specially this project requires a Li-ion battery, soldering and eletronic skills, and it could be potentialy DANGEROUS (catch fire, etc).


# SBC choice

At this time, 2022/10/12, I´m using a Raspberry PI Zero W from 2018, just because the form factor. It´s slow for general usage, but for terminal apps, script editing, taking notes, simple games, It runs very well. 

I have a RPi 3B and RPi 4B but they are a power hog for a small battery form factor usage.


# 3D Printing

I´m using a Creality Ender 3D Printer with PLA. For slicing, I´m using the Ultimaker Cura 5.0.0 app.

+ My basic settings

   - Standard Quality: 0.2mm
   - Wall line count: 2
   - Top/Bottom thickness: 0.8
   - Bottom layers: 4
   - Infill Density: 15.0%
   - Build plate temperature: 60
   - Print speed: 50
   - Enable retraction: true
   - Generate support: true
   - Plate adesion type: skirt

 # Parts
 
 + Raspberry PI Zero W (or W2 or a form factor compatible)
 + XBox 360 Chat pad clone (I don´t tested with the original chat pad one)
 + Arduino Teensy 1.2
 + 3.5 SPI LCD Screen (HDMI will supported yet)
 + 1S Li-ion BMS with mini usb charger
 + 1S 1000Mha 3.7V li-ion battery
 + DC-DC 3.7 to 5v booster (600 mAh at least)
 + Some wires
 + An On-Off switch
 + Two screws (see into the photos)
 + (Optional) An old FW-91 Casio and any piezo.

# Keyboard

This project uses a hard wired keyboard, interfaced by the Arduino Teensy and RPi Usb port. If you want to use a BT or 2.4Ghz one that fits into the case and cover, go ahead, but personally, I prefer to use a wired one.

The WIP project of this keyboard could be seen at my other GitHub Repository:

https://github.com/CleversonSA/teensy-xbox-cheap-chatpad-keyboard-usb


# Building

I´ve not created a step by step building video, but I´ll post many photos as possible of this build:

+ Front View Opened
![Imgur Image](https://imgur.com/ASfawPd.jpg)

+ Side view Closed (this is an issue to fix, the case does not close very well)
![Imgur Image](https://imgur.com/sC47W0y.jpg)

+ Top View Closed with "Real time clock" (Optional)
![Imgur Image](https://imgur.com/mCk7kJd.jpg)

+ Top view opened with "Real time clock" (Optional)
![Imgur_Image](https://imgur.com/kbsJeix.jpg)

+ Side view opened
![Imgur_Image](https://imgur.com/IGLXG8a.jpg)

+ Bottom teardown
![Imgur_Image](https://imgur.com/TZt1MRg.jpg)

+ Bottom keyboard cover teardown (I promess more detailed wiring in future)
![Imgur_Image](https://imgur.com/SnQ19sr.jpg)

+ Top teardown
![Imgur_Image](https://imgur.com/3vg7Kym.jpg)


