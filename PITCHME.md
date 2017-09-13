## Physical computing essentials

---
### how the computer sees you

![Tom Igoe Human](https://interactiondesign.files.wordpress.com/2011/06/igoefinger.jpg)


+++

Touchscreens, touchpads and Kinect have changed this perception a little but it remains largely the same.

---
### Kinect
![Skeletal tracking](http://psychic-vr-lab.com/blog/wp-content/uploads/2015/03/kinect4.png)

+++

The Kinect introduced skeletal tracking for full-body interactions but as you can see the image that the computer has of the human is still **reductionist** at best.

---
electronics let us bridge the gap between the digital domain and the physical world
---
### Microcontrollers

![PIC microcontroller](https://www.elprocus.com/wp-content/uploads/2013/02/33.jpg)

your washing machine has one

+++
### there are more microcontrollers in the world than there are full computers
They are by far the most ubiquitous form of computing. There are many different kinds but in this course we will be dealing primarily with two kinds AVR and ESP82xx

+++
### AVR chipset
most common for the Arduino family of microcontrollers

+++
### Arduino Nano

![Arduino Nano](https://twinschip.com/image/cache/data/%20Developer%20Boards/Board/Arduino/Electronics-DIY-Arduino-Nano-v3.0-Mini-ATmega328-Board-1_10-366-550x650.jpg)

+++
### ESP82xx
much more powerful microcontroller, supports WiFi, a lot more memory (4Mb), can be programmed with Arduino toolchain

+++
### Adafruit Featherboard HUZZAH

![HUZZAH](https://cdn-shop.adafruit.com/480x360/3405-06.jpg)

18.50,- EUR in floris.cc

+++
### Wemos D1 mini Pro

![Wemos D1](https://www.cnx-software.com/wp-content/uploads/2016/09/Wemos_D1_mini_Pro.jpg)

8,- EUR in tinytronics.nl

+++
### Attiny85

![Attiny85](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToQP1OoeXTy_9duz56s40DH7enrHFN_1tSgCgvXNPvcRq8itNnXw)

If you just need a few pins for your project, why use a whole Arduino?
(note: needs a USB programmer)
+++
### Attiny85 pinout

![Attiny85 pinout](https://cdn.sparkfun.com/assets/f/8/f/d/9/52713d5b757b7fc0658b4567.png)


---
## Capacitive Sensing

turning (almost) everything into a sensor
+++
### behold the banana piano

![banana piano](https://www.youtube.com/embed/Lbkw0LFVZDI)

+++
### how it works

![Shunt flow](http://www.sensorwiki.org/lib/exe/fetch.php/sensors/shunt_mode.png?w=&h=&cache=cache)
+++
### what can you sense?

  - proximity
  - touch (contact)
  - position (in an array of capacitive sensors)

+++
### touchscreens are capacitive sensors too

![touchscreen](http://m.eet.com/media/1157903/caponefig1.gif)
+++
### examples: graphite (pencil)

![pencil](https://www.youtube.com/embed/uPoKn4mbrQk)

responsive drawings
+++
### wiring your Arduino
![capacitive arduino](https://i.stack.imgur.com/zq7rx.png)
+++
### arduino library

http://playground.arduino.cc/Main/CapacitiveSensor

this does all the hard (calibration) work for you
+++
## more examples

![MIT musical Levi's jacket](http://web.media.mit.edu/~joep/SpectrumWeb/captions/Jackets.GIF)

MIT musical Levi's Jacket
+++
### MIT musical Levi's Jacket

http://www.media.mit.edu/~joep/MPEGs/jacket.mpg

+++
### Theremin

![Leon Theremin](https://www.youtube.com/embed/w5qf9O6c20o)

Leon Theremin playing the electronic instrument that he invented
+++

![cat video](https://www.youtube.com/embed/bXn4_JkVFVo)

capacitance is not just a quality of the human skin, cats can do it too

+++
### Google's project Jacquard jacket
![project jackard](https://www.youtube.com/embed/grKHwQIaiaA)

+++
# DuoSkin

![duo skin](https://player.vimeo.com/video/178334883)

more details @ http://duoskin.media.mit.edu/

+++
### read more about capacitive sensing

https://www.bareconductive.com/make/what-is-capacitive-sensing/
