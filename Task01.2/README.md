# Getting Started with ESP32 using Arduino IDE - Blink LED
<br>

![Getting-Started-with-ESP32](https://user-images.githubusercontent.com/101488769/177843270-5a49b027-cc02-4f93-9d6b-e9cbb667edcb.png)
<br>

<b> ESP32 can be programmed directly from the Arduino IDE</b> which makes it easy to work for the large community of Arduino developers. Here in this <b> ESP32 getting started tutorial</b>, we will <b> configure ESP32 in Arduino IDE and program it to Blink an LED.</b> So, let’s get started with the ESP32 development board.

 

### Materials Required
* ESP32 Module
* USB cable
* Arduino IDE

### Table of Contents
* [Preparing ESP32 in Arduino IDE](#Preparing_ESP32_in_Arduino_IDE)
* [Video to help](#video_to_help)
* [Testing](#testing)
* [Concluion](#concluion)
<br>


## Preparing ESP32 in Arduino IDE
<br>
<b> Step 1:</b> First you need to download and install <b> Arduino IDE </b> software which you can download from https://www.arduino.cc/en/Main/Software for free. If you have already installed Arduino IDE on your PC, then make sure that it is the latest version of IDE as the older version doesn’t include the ESP32 board.
<br>
<br>

<b> Step 2:</b> After installing, open IDE and go to <b> Files -> Preferences </b> and open preference window and see the <b> “Additional Boards Manager URL’s” </b> as:
![Preparing-ESP32-in-Arduino-IDE](https://user-images.githubusercontent.com/101488769/177851701-3bb32d05-e64d-43be-a215-1e50e4355377.png)
<br>
<br>

<b> Step 3:</b> This box may be empty or contain some other URL if you have used it previously for ESP8266. You just have to paste the below URL into this box if the box contains already another URL, then paste it by separating another URL using comma(,).

https://dl.espressif.com/dl/package_esp32_index.json
<br>
<br>

<b> Step 4:</b> After pasting the given URL my window looks like this as I already used ESP82666, Now press OK and the window will disappear.
![Setting-Preference-for-Interfacing-ESP32-with-Arduino](https://user-images.githubusercontent.com/101488769/177852612-34b0508e-a24f-43bf-81bf-5929925cc78b.png)

