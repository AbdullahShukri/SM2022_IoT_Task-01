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
* [Preparing ESP32 in Arduino IDE](#Preparing-ESP32-in-Arduino-IDE)
* [Programming ESP32 With Arduino IDE](#Programming-ESP32-With-Arduino-IDE)
* [Blinking LED](#Blinking-LED)
* [Concluion](#concluion)
<br>


## Preparing-ESP32-in-Arduino-IDE
<br>
<b> Step 1:</b> First you need to download and install <b> Arduino IDE </b> software which you can download from https://www.arduino.cc/en/Main/Software for free. If you have already installed Arduino IDE on your PC, then make sure that it is the latest version of IDE as the older version doesn’t include the ESP32 board.
<br>
<br>

<b> Step 2:</b> After installing, open IDE and go to <b> Files -> Preferences </b> and open preference window and see the <b> “Additional Boards Manager URL’s” </b> as:
<br>
<br>
![Preparing-ESP32-in-Arduino-IDE](https://user-images.githubusercontent.com/101488769/177851701-3bb32d05-e64d-43be-a215-1e50e4355377.png)
<br>
<br>

<b> Step 3:</b> This box may be empty or contain some other URL if you have used it previously for ESP8266. You just have to paste the below URL into this box if the box contains already another URL, then paste it by separating another URL using comma(,).
<br>
https://dl.espressif.com/dl/package_esp32_index.json
<br>
<br>

<b> Step 4:</b> After pasting the given URL my window looks like this as I already used ESP82666, Now press OK and the window will disappear.
<br>
<br>
![Setting-Preference-for-Interfacing-ESP32-with-Arduino](https://user-images.githubusercontent.com/101488769/177852612-34b0508e-a24f-43bf-81bf-5929925cc78b.png)
<br>
<br>

<b> Step 5:</b> Now go to <b> Tools-> Board-> Board Manager </b>  and search for ESP32 and press <b> install </b>, it will take some time to install, make sure that you have an internet connection; after installing, your window looks like this
<br>
<br>

![Install-ESP32-Library-in-ArduinoIDE](https://user-images.githubusercontent.com/101488769/177852983-08c9c80c-17b4-41e6-90ec-0722ca2744f4.png)
<br>
<br>

After this, close the window of board manager and your Arduino IDE is ready to program ESP32.
<br>
<br>

## Programming-ESP32-With-Arduino-IDE
Now you are ready to <b> program your ESP32 using Arduino IDE</b> according to your requirements. Following are the steps required to program the ESP32 with Arduino IDE. Here we will <b> upload an LED binky program in ESP32 using Arduino IDE.</b>
<br>
<br>

<b> Step 1:</b> First of all, connect your ESP32 to your computer using a micro-USB cable, make sure that Red LED goes high after connecting it with the PC.
<br>
<br>

<b> Step 2:</b> Now you have to select your board; so go to <b> Tools-> Boards -> esp32 -> select “WEMOS D1 MINI ESP32”. </b>
<br>
<br>

![WEMOS D1 MINI ESP32](https://user-images.githubusercontent.com/101488769/178156726-88c93f41-b899-40aa-8418-97e3725d9439.png)
<br>
<br>


<b> Step 3:</b> Now open device manager and check to which com port ESP32 is connected. Here, my ESP is connected to COM3.
<br>
<br>

![COM3](https://user-images.githubusercontent.com/101488769/178156801-3b355dc8-37bb-497b-b319-0fa436fc57b5.png)
<br>
<br>

## Blinking-LED
One of the first projects made with Arduino is “how is to blink a LED”.  Many examples exist for blinking a Led with Arduino. Unfortunately, these tutorials do not have details about the coding and are very basic in their explanation. In this tutorial, I hope to help new users go into more detail and understand the code used for controlling a LED.
<br>
<br>

![Blink](https://user-images.githubusercontent.com/101488769/178157772-2dd62332-14f8-40f7-a474-257a9bd3e1a1.png)
<br>
<br>

![Code](https://user-images.githubusercontent.com/101488769/178157858-7fe6cd48-06e3-4076-b254-0477afec77ec.png)
<br>
<br>
