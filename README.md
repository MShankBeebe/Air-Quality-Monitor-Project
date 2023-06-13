# Air Quality Monitor Project Overview

I live in an area that frequently has problems with wildfire smoke and gets a lot of air quality alerts.  I thought it would be useful to make an air quality monitor.
I am still learning Circuit Python, electronics, and how to work with Raspberry Pi Pico/Pico W, so this will be an ongoing project that I will update as I go.  I will be adding instructions
and links to additional resources for any other curious people who would like to build their own air monitor and/or learn with me.
My goal is eventually to have something that will measure C02, VOCs, and PM 2.5 particles and transfer the data wirelessly.

I have included some supplimental information for people who are new to microcontrollers, Pico boards, and soldering.  This project, as written, does require some soldering.  If you are experienced in all of these things, please feel free to skip ahead to the project.

## Additional Resources For Students
### About Microcontrollers
Tech Target has a nice explainer about what microcontrollers are and how they work here:
[Target Tech Explanation of Microcontrollers](https://www.techtarget.com/iotagenda/definition/microcontroller)  

### About the Pico Boards
The Rasberri Pi Foundation has wonderful documentation for the Pico and Pico W boards here:
[Pico and Pico W Documentation](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html)  
  
For quick reference, I have reproduced their Pinout Diagram here.  A larger better one is available as a PDF from the link above.
Raspberry Pi Pico W Pinout diagram:  

![Pico W Pinout](https://github.com/MShankBeebe/Air-Quality-Monitor-Project/blob/main/images/PicoWPinouts.png)

### About the SGP30 chip
[Adafruit SGP30 Tutorial](https://learn.adafruit.com/adafruit-sgp30-gas-tvoc-eco2-mox-sensor/)

### About Soldering
Soldering is a tricky thing and takes time, patience, and practice.  One of the reasons I like the Pico boards is that they do require a lot of soldering and therefore give me lots of practice.  Because they are relatively inexpensive, it's a good chip to start with.  The SGP30 chip is more expensive, so if you are new to soldering, make sure to practice soldering before you attempt to solder the pins onto this chip.

Here are some helpful links:
[Adafruit Guide To Excellent Soldering](https://www.techtarget.com/iotagenda/definition/microcontroller)
[Tom's Hardware: How To Solder Pins to Your Raspberry Pi Pico](https://www.tomshardware.com/how-to/solder-pins-raspberry-pi-pico#:~:text=Bring%20the%20tip%20of%20the,on%20the%20sponge%20%2F%20brass%20cleaner.)

## Hardware Setup For The Project
### What You Will Need
1.  1 Raspberry Pi Pico W
2.  1 USB cord that can transfer data
3.  1 breadboard
4.  wires (I prefer male to male jumper wires)
5.  A computer with the latest version of Circuit Python installed and an IDE that can work with it and boards, like MU (what I used)

### Basic Setup with Pico W and SGP30 Chip
Solder the male header pins to the Pico W and the SGP30.  Here is the basic configuration:
![Basic Configuration](https://github.com/MShankBeebe/Air-Quality-Monitor-Project/blob/main/images/Monitor1.jpg)

