# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 Introduction

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 

##### Other Links: [Arudino link I used to download it](https://www.arduino.cc/en/software/)


## Steps I followed
Write the steps you followed here.  This way you can keep track of where you might have messed up if the project does not work.
1. I have download Arduino IDE 2.3.6 for windows 10 or newer.
2. I've downloaded [CH341SER.ZIP](https://www.wch.cn/downloads/CH341SER.ZIP.html?type=en) because we need those drivers in order to work on the cam.
3. Also I download "CH340 Windows Driver: Attached as CH34x_install_windows_v3_4" and I have extract both files and click install on the setup and it was successfull.
4. I went to Arudino and copy this link (https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json) and put it throught preferences.
5. Then I downloaded esp32 by Esspressif in boards manager in Arudino.
6. On the Arduino I connect to the cam with the board AI Thinker esp32-cam with the port com 5 serial port (usb)
7. I went to file than example and went to basic blink where I was playing with the camera to check how to make it blink quicker or slower.
8. 

## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

1. E (485) camera: Camera probe failed with error 0x105(ESP_ERR_NOT_FOUND)
Camera init failed with error 0x105
 How did I solve: 

### Example Problem
1. Arduino code will not load on ESP32 Cam.
   Answer: Camera drivers were incorrect I needed to install the driver: [https://www.wch-ic.com/downloads/CH341SER_ZIP.html](https://github.com/martin-ger/esp32_nat_router).  I used file, "CH341SER.ZIP" and it worked.


## Final Report
