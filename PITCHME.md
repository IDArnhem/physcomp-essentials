## Physical computing essentials

turning everything into a computer

---
### how the computer sees you

![Tom Igoe Human](http://res.cloudinary.com/zilogtastic/image/upload/v1505408559/igoefinger_ie2ihx.jpg)


+++

Touchscreens, touchpads and Kinect have changed this perception a little but it remains largely the same.

---
### Kinect
![Skeletal tracking](http://res.cloudinary.com/zilogtastic/image/upload/v1505408570/kinect4_wnlfpb.png)


The Kinect introduced skeletal tracking for full-body interactions but as you can see the image that the computer has of the human is still **reductionist** at best.

---
electronics let us bridge the gap between the digital domain and the physical world
---
### Microcontrollers (MCUs)

![PIC microcontroller](http://res.cloudinary.com/zilogtastic/image/upload/v1505408580/33_bdso4q.jpg)

your washing machine has one

+++
##### there are more MCUs in the world than there are CPUs
They are by far the most ubiquitous form of computing. There are many different kinds but in this course we will be dealing primarily with two kinds AVR and ESP82xx.

+++
# AVR chipset
Made by a company named Atmel, is the kind used in many of the Arduino family of MCUs. There are many AVR chips and the area of embedded electronics has been exploding the last two years.
+++
### Arduino UNO

Trusty old friend that never disappoints, big, bulky, reliable and slow. Great for the classroom, we all need one of these to sketch on, but it's too big and too **expensive** for project work.

+++
### Arduino Nano

![Arduino Nano](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_410/v1505408591/Electronics-DIY-Arduino-Nano-v3.0-Mini-ATmega328-Board-1_10-366-550x650_dmldfg.jpg)
+++
### Attiny85

![Attiny85](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_410/v1505408635/09378-1_okao4b.jpg)

If you just need a few pins for your project, why use a whole Arduino?
(note: needs a USB programmer, see next slide)
+++
### The ATtiny85 programmer

![Attiny programmer](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_410/v1505408774/tiny-avr-programmer_dsjkc2.jpg)

+++
### Attiny85 pinout

![Attiny85 pinout](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_430/v1505408652/52713d5b757b7fc0658b4567_h7idgb.png)

+++
### Meet the Digispark

The supertiny Attiny85 protoboard

![Digispark](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_420/v1505408867/SKU172392b_mh5dcp.jpg)

+++
### The HvA's XMega

![XMega](https://res.cloudinary.com/zilogtastic/image/upload/c_scale,w_420/v1543222653/IMG_6443_dfodie.jpg)

+++
### Other ATtinies

Atmel makes about 45 different varieties of the ATtiny series of MCUs. Enough to make your head spin. So if the Attiny85 doesn't suit your needs there's plenty to choose from. [See full product list here](http://www.atmel.com/products/microcontrollers/avr/tinyavr.aspx).

+++
### ESP82xx
Much more powerful MCU, supports in-chip WiFi, a lot more memory (4Mb), can be programmed with the same Arduino toolchain that you have grown used to. Popular for IoT applications.

+++
### Adafruit Featherboard HUZZAH

![HUZZAH](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_410/v1505408916/2821-01_w3lriy.jpg)

18.50,- EUR in floris.cc

+++
### Wemos D1 mini Pro

![Wemos D1](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_410/v1505408930/Wemos_D1_mini_Pro_jf1tqp.jpg)

8,- EUR in tinytronics.nl, cheaper from Chinese supplier

---
# Capacitive Sensing

turning (almost) everything into a sensor
+++
### behold the banana piano

![banana piano](https://www.youtube.com/embed/Lbkw0LFVZDI)

+++
### how it works

![Shunt flow](http://res.cloudinary.com/zilogtastic/image/upload/v1505408949/shunt_mode_sq5l1m.png)

[read more theory here](http://www.sensorwiki.org/doku.php/sensors/capacitive?s[]=capacitive)
+++
### what can you sense?

  - proximity
  - touch (contact)
  - position (in an array of capacitive sensors)

+++
##### touchscreens are capacitive sensors too

![touchscreen](http://res.cloudinary.com/zilogtastic/image/upload/v1505410629/touch-screen-technology_wqcfeq.gif)
+++
### examples: graphite (pencil)

![pencil](https://www.youtube.com/embed/uPoKn4mbrQk)

responsive drawings
+++
### while we are on graphite

![Drawudio](https://www.youtube.com/embed/PV_w38ldZaE)

[Drawudio a small step for a human, a great step for humanity](http://drawdio.com/) from MIT's **Lifelong Kindergarden** research group.

+++
### exercise: wiring your Arduino
![capacitive arduino](https://i.stack.imgur.com/zq7rx.png)
+++
### arduino library

http://playground.arduino.cc/Main/CapacitiveSensor

This does all the hard (calibration) work for you, get it from **sketch > library > add library...**
+++
### exercise

let's try getting some input signal from our piece of tinfoil

+++
### capacitive sensing
Is one of the fundamentals of interaction and it goes way back, however its a technique wide open to creativity and material research so the possibilities are endless, here are some examples old and new.
+++
### Interactive denim

![MIT musical Levi's jacket](http://res.cloudinary.com/zilogtastic/image/upload/v1505410681/Jackets_rhilqe.gif)

MIT musical Levi's Jacket
+++
### MIT musical Levi's Jacket

<video width="640" height="480" controls>
  <source src="http://res.cloudinary.com/zilogtastic/video/upload/v1505408984/jacket_ewjvrl.webm">
Your browser does not support the video tag.
</video>



+++
### Theremin

![Leon Theremin](https://www.youtube.com/embed/w5qf9O6c20o)

Leon Theremin playing the electronic instrument that he invented
+++
![cat video](https://www.youtube.com/embed/bXn4_JkVFVo)

capacitance is not just a quality of the human skin, **kat haz it too**

+++
### Google project Jacquard

![project jackard](https://www.youtube.com/embed/grKHwQIaiaA)

+++
### Google's & Levi's Commuter jacket

![commuter jacket](https://www.youtube.com/embed/yJ-lcdMfziw)

+++
### DuoSkin

![duo skin](https://player.vimeo.com/video/178334883)

MIT and Microsoft, read more about it @ http://duoskin.media.mit.edu/
+++
### "BOTANICUS INTERACTICUS": Interactive Plant Technology

![disney plants](https://www.youtube.com/embed/EcRSKEIucjk)

Disney Research [more info](https://www.disneyresearch.com/project/botanicus-interacticus-interactive-plant-technology/)

+++
### Pulp-based Computing, Marcelo Coehlo

![Pulp-Based Computing](https://player.vimeo.com/video/4272607)

[see more from this project at Marcelo Coehlo's site](http://www.cmarcelo.com/pulp-based-computing/)

+++
### Workshop PapierBoisCarton

![PapierBoisCarton](https://www.youtube.com/embed/fMmZoJJXdhs)

+++
### Media Vintage, Melissa Coleman

http://melissacoleman.nl/media_vintage/

no hard PCB electronics
+++
### Jean Paul George & Me
![band on a shirt](https://player.vimeo.com/video/132808247)

album release including interactive musical shirt for kids
+++
### beyond basics

![12-pad arduino shield](http://res.cloudinary.com/zilogtastic/image/upload/c_scale,h_400/v1505409006/2024-03_g9ruoc.jpg)

Our little Arduino circuit is handy but not very sophisticated, there are other platforms specialized in capacitive sensing. That will allow you to work with more materials and get better readings. [Like this one from Adafruit](https://www.adafruit.com/product/2024).

+++
### Touch Board, Bare Conductive

![video](https://www.youtube.com/embed/dKFRweXei90)

+++
read more about capacitive sensing

https://www.bareconductive.com/make/what-is-capacitive-sensing/
