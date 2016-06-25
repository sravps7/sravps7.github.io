---
layout: project
title: Phone to Arduino Communication using light
category: project
permalink: /projects/phone-arduino-light-communcation.html
---

This project was done in the winter of my second year of my engineering along with a batchmate of mine.

The project successfully was able to send data from the phone to the arduino using light as a medium. We built an Android app which would take any string as an input. This string was then encoded into bits and sent over to the torchlight on the phone. The torchlight would blink according to the bit pattern. 

This blinking was read by IR LEDs (yes, you read it right!!). We had two LEDs placed for reading this bit pattern from the phone. One LED was to measure the external disturbances. The difference in the readings of the two LEDs was used for further processing.  

The potential differences across these LEDS was then sent to an Arduino where it was decoded to get back the string. 

We were able to adjust the speeds of transmission using the app. The maximum speed we could reach was around 8 bits per second. If transmission of only numbers was considered, we were able to increase the speed of transmission by changing the encoding and decodeing procedure. 