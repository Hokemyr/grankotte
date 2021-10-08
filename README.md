# grankotte
Here is an album of the unpopulated pcb: https://imgur.com/a/oZs480X

Here is an album of the populated pcb: https://imgur.com/a/ElyGUbr

# Intro
This is the github page for my attempt at making a replacement for the arduino pro-micro, but with usb-c.

# Description
My goal with this project was to create a replacement for the very popular Pro-micro microcontroller that is commonly used in various DIY electronic projects. 
Initially i started working on the project because i was bored and wanted to practice pcb and electronics design, so i settled on making a copy of the arduino pro-micro. 
But after a while i realized that i should probably make it an upgrade from the original pro-micro (which has a micro usb port as the main way of conecting it to a pc), 
so i decided to make one with a USB-C port (although its only USB type-c 2.0). The microcontroller i choose was the Atmega32u4 as that is the one used on the original pro-micro,
and its the microcontroller i was most comfortable with at the time, i decided against using an Atmega32u4 in a package like VQFN that would save spacec on the pcb and went with a QFP package instead as that would be way easier to assemble on my own. 

When i first assembled the prototypes they seemed to work fine, no shorts or anything, i even flashed a keyboard layout onto one (using QMK firmware) and they seemed to work.
But after further testing i realized that i had wired two pins the wrong way around (i cant remember which though) so they were kind of usuable in a random homemade project but would be unusable in a regular keyboard pcb. I have not got around to fixing it as i lost all the files in a hard drive failure. :(

# Features

- Atmega32u4 microcontroller

- USB Type-c 2.0

- Standard pro-micro footprint and pinout
