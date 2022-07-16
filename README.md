# week2_SpeechRecognition-ESP32Setup

Speech Recognition in files uploaded in Repositry Work Only in Chrome Browser .

wisdom ESP32 Setup Algorithim in Arduino :

install Arduino App 
	
in Arduino IDE go to *File* then go to *Preferences*
	
in *Additional Board Manager URLs* Enter The URL below :
	
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
	
click *Ok* 
	
in Arduino IDE click *Tools* then click *Board* then click *Boards Manager*
	
in Board Manager Search For *ESP32* and click install in *ESP32 by Espressif Systems*
	
close the window

in Arduino IDE  click *Tools* then click *Board*
	
in Board Menu click *ESP32 Arduino* then click *WEMOS D1 MINI ESP32*
	
plug in ESP32 in PC 
	
in Arduino IDE click *Tools* then click *Port*
	
select the port "COM4"
	
in Arduino IDE click *File* then click *Examples*
	
in Examples click *Basic* then click *Blink*
	
the Blink code work with LED Light in ESP32 device to check that not broken

change Delay of LED in code if you want to make it faster or slower
	
Click on Upload or *->* icon to run code on Your ESP32 Device
