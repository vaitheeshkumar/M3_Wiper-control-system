## PROJECT TITLE : WIPER CONTROL SYSTEM

 * This Project is an **Wiper control system** , a wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.
 * We are trying to simulate this project on **stmcube 32 IDE**

# ABSTRACT
1) The Wiper speed control system controls the operational speed of the wiper in accordance with the rain condition. 
2) It cleans raindrops or any other liquids off the vehicle's windscreen. 
3) The prior system required mannual wiper activation, and the operation of bringing up the wiper was difficult to manage.
4)  As a result, this method is proposed to address this issue. The project's goals are to improve ageing the automobile systems by giving automated transmission.
5)  Most of the cars have two wipers, one on the rear window and other on the front glass.
6)   The wipers parts visible from the cars are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. 
7)   the warn gear is able to generate the force required to move the wipers as fast as they need to move.
8)    Now a days we have the automated control wiper system whenever we stop wiping in between the process it will automatically come to initial position this is the new wiper system behind the wiper arm.
9)   This proposed wiper system's principle is comparable to those of other existing conventional wipers.
---
FEATURES
---
1) It shall lock the car when the button is pressed once
2) It shall open the car when the button is pressed twice
3) It shall wiper on and it moves clock wise direction and when the button is pressed thrice
4) It shall wiper off and it moves anti clock wise direction and when the button is pressed four times
5) It shall wiper complete one cycle when the button is pressed five times.

# Requreiments

# Introduction
 1) This Project is an **Wiper control system** , a wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.
 2) We are trying to simulate this project on **stmcube 32 IDE**
 

---

 FEATURES
---
 * When the button is pressed once the car will **start**--->The ignition key postion at **ACC**
 * When the button is pressed again the wiper will **start**--->Wiper **On**
 * When the button is pressed again the wiper will **off**--->Wiper **Off**
 * When the button is pressed thrice the car will **sto**p--->The ignition key position at **Lock**

# Working principle
Blue, Green and Orange LEDs, Come on and OFF alternately for set frequency.  
1) It shall lock the car when the button is pressed once
2) It shall open the car when the button is pressed twice
3) It shall wiper on and it moves clock wise direction and when the button is pressed thrice
4) It shall wiper off and it moves anti clock wise direction and when the button is pressed four times
5) It shall wiper complete one cycle when the button is pressed five times.
---
# SWOT ANALYSIS
---
# 5W's & 1H
# What
1) A **wiper speed control system** for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions. 
2) The control system includes a rain sensor (30) detecting rain conditions to produce . 
3) An analog signal having an amplitude depending upon the detected rain conditions.

# WHY
1) Windshield wipers keep the windshield of a vehicle clear from **rain water, snow, dust and road spray** 
2) The first windshield wipers were operated manually by moving a lever inside the car
3) The ain purpose of wiper system is to clean the widscreen sufficiently to provide suitable visubility at all times

# Where
1) Windshield wipers are controlled by the stalk on the right of your steering wheel. 
2) Inside and out side the car

# When
1) When the weather condition is bad the wiper is activate and clean the car window
2) windscreen wiper is a device used to remove rain, snow, ice, washer fluid, water, and debris from a vehicle's front window

# Who
* Who is driving or controlling the car

# How
* By using STM like by multiple pushes on a button
 
# Strengths
1) No human interaction with car
2) Manages all commands with one key automatically
 
# Weaknesses

1) Unable to monitor status of car
2) Range is limited
30 Wait for certain time after every command to press new command
# Opportunities

1) The Scope of this sytem is huge in car control
2) can be used where  the car need thesed command
3) Low cost
# Threats

* When new command is given without completing the current command it will not take current command
---
 
# Software Requirement
* **STM32 IDE**

# COMPONENTS AND SUPPLIES:
* STM32F407 Discovery Board
1) Push Button
2) LEDs
3) Resistors
4) Power Supply
# ADVANTAGES:
1) To save money during wet seasons, turn off the irrigation system.
2)  Electricity bills are lowered as a consequence.Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
3)  As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
4)  It is quite simple to use.
5)  As a consequence, less energy is consumed.
6)  Rain sensor-based systems are extremely simple to install.
7)  Individual rain sensors are fairly inexpensive.
# Disadvantages:
1) When water falls squarely on the rain sensor, the mechanism activates.
2) The entire system cost rises when more components, including a rain sensor, are required.
3) Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.

# High Level Requirements

* HLR1---> It will start the car
* HLR2--->It will start the wiper  
* HLR3--->It shall seen speed of the wiper work 
* HLR4--->It will stop the wiper 
* HLR5--->It will stop the car 


# Low Level Requirements
 
* LLR1--->If the User button is pressed Once, the red LED will be on
* LLR2--->If the User Button is pressed TWICE, Blue,Green,Orange LED's come ON at a time with set of frequency 
* LLR3---> If the User Button is pressed THIRD time, ON All LED's in CLOCKWISE manner an speeed will increase
* LLR4--->If the User Button is pressed FOURTH time ,all LED's on anticlock manner
* LLR5--->If the User Button is pressed FIFTH times, the red LED will be off | 

## OUTPUT
1) User button is hold for two seconds,the red LED is on
![OUTPUT 1](https://user-images.githubusercontent.com/101281756/168282534-b0d06215-88b5-43aa-acc4-cbd8bceafda7.png)

2) Wiper Speed is LOW
![OUTPUT 2](https://user-images.githubusercontent.com/101281756/168282574-5062a6b9-4ca3-431f-a947-4845e4ad74f5.png)

3) Wiper Speed is MEDIUM
 ![OUTPUT 3](https://user-images.githubusercontent.com/101281756/168282691-5c97e5dd-c712-42fb-acc6-83d63fe73c1c.png)

4) Wiper Speed is HIGH
![OUTPUT 4](https://user-images.githubusercontent.com/101281756/168282728-081f1ff2-729c-4e41-95d1-6f5a29178010.png)

5) User button is pressed and hold for 2 seconds, the red LED is off
![OUTPUT 5](https://user-images.githubusercontent.com/101281756/168282767-1a6ebe61-e0e6-4fd0-a4fb-9ea048574235.png)
