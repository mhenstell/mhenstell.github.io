---
layout: project
permalink: /chumby-hacking
category: experiment 
type: "Wireless Utility" 
img: chumby-hacking
title: Chumby Hacking
technologies: [Chumby, Arduino, X10] 
when: 09/2010
collaborators: 
task: 
desc: 
images: [1.jpg, 2.jpg, 3.jpg, 4.jpg]
sourcecode: [[Github, "https://github.com/mhenstell/Infocast"]]
context: 
---

In 2010, Bestbuy's Insignia brand released the Infocast, a desktop Internet-powered display device based on the [Chumby](http://chumby.com/).

<!--break-->

The device featured an 8" touch screen, 2GB memory, Stereo speakers, two USB ports, WiFi, and an 800Mhz processor running Linux, for about $80 on sale.

This quick hack involved mounting an Arduino to a bracket on the backside of the device, plugging it in using a USB-Serial cable, and connecting the arduino to a cheap X10 transmitter I got off eBay. I made a really simple website interface to control my lights from my phone, and the instructions were sent through the Internet to my Infocast, which commanded the Arduino to control the lights.

I then hooked my door buzzer up to the Arduino, allowing me to buzz myself in from the same interface. Going further, I devised a simple scheme to buzz me in even quicker. I noticed that when my iPhone was woken up from sleep (but before unlocking), it attempted to connect to any known network in range. By setting a static IP on my iPhone and running a simple script on my Infocast to continually ping that IP, I was able to buzz myself in to my apartment just by hitting the lock button on my phone. This could be done without even taking the phone out of my pocket, and as I lived on the ground floor, it worked perfectly when I was standing outside the front door.