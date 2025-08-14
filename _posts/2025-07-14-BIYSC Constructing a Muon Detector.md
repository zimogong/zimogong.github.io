---
layout: post
title: Building a Muon Detector
date: 2025-07-14 21:23:00 +0800
math: true
categories: [Cosmic Ray Detector, BIYSC, Physics]
tags: [BIYSC, Notes, Cosmic Rays]
media_subpath: /assets/img/20250714/
image:
  path: nils.jpg
---

Hey there! For all these days we had been working on our muon detectors, and finally we completed this task! Today we installed the last piece of component into our apparatus and successfully detected some signals from the sky(wherever the source, we actually don't know exactly). We all felt a strong sense of accomplishment when our hand-made detector receive signals that could have come from a supernova. The occasional jumping of the waves in the oscilloscopes seemed like congratulations to us since we have devoted so much effort into the seemingly simple construction of the device. 

Enough chitchat, here are some notes I made in the process of the project.

## How Our Muon Detectors Work:

1. The muon particles that come from cosmos strike the plastic scintillator(inside the detector)

2. The muon particles interact with the plastic scintillator and excite some electrons in the material's atoms to a higher level.

3. The electrons then return to the ground state after emitting photons of a particular frequency(typically in the blue light range).

4. The photons are detected by the SiPM(silicon photomultiplier), either directly or after being reflected several times through the reflective foils inside the detector.

5. The SiPM produce an electrical signal that travel through the circuit to the amplifier to intensify the signal.

6. The amplified signal then flow to the oscilloscope to visualize it(The crest indicated that the SiPM had detected a muon):

​                   We often had to stack two detectors, one on the top of another, in order to exclude the possibility of receiving signals from other particles since only a muon can pass through two detectors concurrently. Therefore, we recorded a detected muon only when two oscilloscopes that were connected to the two detectors both display a crest. 

Probably not a muon: 

![Not a muon](Oscilloscope.png)

Muon detected: 

![muon](oscilloscope2.png)

## The Manufacturing Procedure of the Detector:

1. Prepare all the things we need:

   - SiPM

   * Plastic Scintillators
   
    ![plastic Scintillators](plastic.png)

   * Cables

   * Circuit boards

   * Reflective foils

   * A laser cutter

     ![laser cutter](laser cutter.jpg)

   * A box(For holding the components of the detector and blocking light)

   * Resistors(51 ohms)

   * Capacitors(100 nF)

   * Power supplies

   * Oscilloscopes

   * Welding guns

   * A drill

     ![drill](drill.png)

   * Multimeters

   * Amplifiers 

     ![amplifier](amplifier.jpg)

   * A computer\.

2. Draw a sketch of the detector and discuss with others to refine it.

3. Measure the dimensions of the box and determine the length and width of the plastic scintillators, circuit boards, and reflective foils

4. Upload the data into the laser cutter and use it to cut out the plastic scintillators. Drill holes on two opposite sides of the light-blocking boxes.

   {% include embed/youtube.html id='9dKw_2wgfDw' %}

5. Install the circuit elements onto the circuit board(Make sure all the components work before soldering by utilizing a multimeter to test them) and solder the cables.

6. Place the circuit into the light-blocking box and fix it in place by using tapes.

7. Install all the rest components of the detector into the box(Plastic scintillators, reflective foils and so on)

8. Connect the circuit inside the box to the amplifier outside through cables that pass through the holes of the box.

   And now our detectors are ready to work!!
   
   ![inside](inside the box.jpg)
