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
1) Windshield wipers keep the windshield of a vehicle clear for **rain water, snow, dust and road spray** 
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
