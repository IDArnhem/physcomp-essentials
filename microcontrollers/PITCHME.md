## Physical computing essentials

turning everything into a computer

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
### Microcontrollers (MCUs)

![PIC microcontroller](https://www.elprocus.com/wp-content/uploads/2013/02/33.jpg)

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

![Arduino Nano](https://twinschip.com/image/cache/data/%20Developer%20Boards/Board/Arduino/Electronics-DIY-Arduino-Nano-v3.0-Mini-ATmega328-Board-1_10-366-550x650.jpg)
+++
### Attiny85

![Attiny85](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToQP1OoeXTy_9duz56s40DH7enrHFN_1tSgCgvXNPvcRq8itNnXw)

If you just need a few pins for your project, why use a whole Arduino?
(note: needs a USB programmer, see next slide)
+++
### The ATtiny85 programmer

![Attiny programmer](https://www.floris.cc/shop/1299-large_default/tiny-avr-programmer.jpg)

+++
### Attiny85 pinout

![Attiny85 pinout](https://cdn.sparkfun.com/assets/f/8/f/d/9/52713d5b757b7fc0658b4567.png)

+++
### Meet the Digispark

The supertiny Attiny85 protoboard

![Digispark](https://img.banggood.com/thumb/view/2014/xiemeijuan/10/SKU172392/SKU172392b.jpg)

+++
### Other ATtinies

Atmel makes about 45 different varieties of the ATtiny series of MCUs. Enough to make your head spin. So if the Attiny85 doesn't suit your needs there's plenty to choose from. [See full product list here](http://www.atmel.com/products/microcontrollers/avr/tinyavr.aspx).

+++
### ESP82xx
Much more powerful MCU, supports in-chip WiFi, a lot more memory (4Mb), can be programmed with the same Arduino toolchain that you have grown used to. Popular for IoT applications.

+++
### Adafruit Featherboard HUZZAH

![HUZZAH](https://cdn-shop.adafruit.com/480x360/3405-06.jpg)

18.50,- EUR in floris.cc

+++
### Wemos D1 mini Pro

![Wemos D1](https://www.cnx-software.com/wp-content/uploads/2016/09/Wemos_D1_mini_Pro.jpg)

8,- EUR in tinytronics.nl, cheaper from Chinese supplier
