# ArduinoPresenter (WIP)
Rubberduckey like device to impress your peers in class

## disclaimer
1) This project makes use of the windows alt-codes and will thus only work if the pc on which you will present runs MS Windows
   https://www.alt-codes.net/
2) Currently, only the German and English Keyboard Layouts are supported, feel free to commit other layouts

## Part list:
**the links provided here are from amazon since it is available pretty much everywhere. Please consider buying the parts from a local retailer instead if possible.**
- Arduino Pro Micro or Leonardo
  https://www.amazon.com/KeeYees-ATmega32U4-Development-Microcontroller-Bootloader/dp/B07FXCTVQP/ref=sr_1_3?dchild=1&keywords=arduino+pro+micro&qid=1619895997&sr=8-3
  (any other board with a ATmega32U4 should work, though you may need to change a few things like the target board in the Arduino IDE)
- Cherry MX Push Button https://www.amazon.com/Cherry-Blue-Keyswitch-pack-himalayanelixir/dp/B01N2L8RR2/ref=sr_1_3?dchild=1&keywords=cherry+mx+blue+switches&qid=1619896184&sr=8-3
  (any other push button will work, please get one that is large enough to click comfortably)
- 1x 10KOhm Resistor like here https://www.amazon.com/Elegoo-Values-Resistor-Assortment-Compliant/dp/B072BL2VX1/ref=sr_1_3?dchild=1&keywords=resistors&qid=1619896596&sr=8-3
- PCB-Board to facilitate connecting the parts like this one: https://www.amazon.com/Chanzon-Double-Sided-Board-Sizes/dp/B07LF78ZY3/ref=sr_1_14?dchild=1&keywords=hole+pcb+soldering&qid=1619896821&sr=8-14
- Single Row female 2.54 mm headers https://www.amazon.com/Single-Headers-Machine-Female-2-54mm/dp/B0187LTEX2/ref=sr_1_10?dchild=1&keywords=female+pin+bar+soldering+2.54mm&qid=1619896923&sr=8-10
## Optinal parts for light:
**the links provided here are from amazon since it is available pretty much everywhere. Please consider buying the parts from a local retailer instead if possible.**
- 1x 3mm LED in your favorite color with the corresponding resistor https://www.amazon.com/EDGELEC-200pcs-Emitting-Assorted-Resistors/dp/B0785DLY5T/ref=sr_1_5?dchild=1&keywords=3mm+LED&qid=1619896683&sr=8-5

## Required tools:
- Computer with python and the Arduino Desktop IDE installed
  https://www.python.org/downloads/  https://www.arduino.cc/en/Guide
- Soldering iron
- Hot Glue gun to insulate to bottom of the PCB

## instructions:
### 1. install the libraries
open the arduino IDE, click `tools`>`Manage Libraries`, wait and type `Keyboard` into the Filter and install it.
![image](https://user-images.githubusercontent.com/57110140/116792952-19514300-aac4-11eb-9866-0241af467734.png)
### 2. clone this repository
Download the source as zip or copy+paste the clone command into your terminal
![image](https://user-images.githubusercontent.com/57110140/116793127-160a8700-aac5-11eb-820c-0fa1dddc15c7.png)
