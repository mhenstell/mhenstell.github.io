---
layout: project
permalink: /muon-detector
category: project 
type: "Desktop Project" 
img: muon
title: Muon Detector
technologies: [Geiger Tubes, Arduino] 
when: 12/2012
collaborators: []
task: 
desc:
images: [1.jpg, 3.jpg, 4.jpg, 5.jpg, 6.jpg, 7.jpg, 9.jpg, 10.jpg, 11.jpg]
sourcecode: [[MuonDetector, "https://github.com/mhenstell/MuonDetector"]] 
---

This is a basic Muon detector that uses three Geiger-Müller tubes, three high-voltage supplies, and a Teensy (Arduino-compatible) microcontroller.

<!--break-->

The Teensy provides three PWM outputs that drive the HV supplies, and watches the outputs of the tubes for the voltage spikes characteristic of an electrical avalanche signifying an ionization event.

This detector isn't meant to be scientifically accurate; rather it was intended as a neat desktop device to make you aware of the cosmic rays passing through you at all times.

I built this as a Spacemas present for my girlfriend. The design and source is open, in case you're interested in making something similar. This project was inspired by a project by [Robert Hart](http://www.hardhack.org.au/geiger_muller_detector).

I did a quick series of write-ups on my blog with many more details about this project: [Part 1]({{ site.baseurl }}/blog/2012/12/26/space-1/), [Part 2]({{ site.baseurl }}/blog/2012/12/27/space-2/), [Part 3]({{ site.baseurl }}/blog/2012/12/28/space-3/)