# Parking_Management_System Report

*Parking Management is something our society is longing for especially in highly populated cities. This Project helps you to view the optimized space available in the garage and also provides records of vehicles that have arrived and departed it also helps to monitor business.*

## 1_Requirements

## Introduction
This project is about Parking Management System. This system provides vacant parking slots up to date in the vicinity and reduces the traffic issues due to illegal parking along the roads.

## Research

![History of PMS](https://user-images.githubusercontent.com/59198753/142820003-0569fc32-2d4c-404e-a555-ce9a03c4ef6c.jpg)

Car Parking Management systems were developed in the early 20th century in response to the need for alleviating the search for vacancy in the parking area.

REFERENCE

[History of parking management system](https://blog.getmyparking.com/2017/07/12/history-of-automated-parking-system/)

## Cost estimation

**Estimated cost = hours needed to build an app * cost per hour to build an app.**

## Features

-   Logging details about the vehicle.
-   View the availabale space in the garage. 
-   Display arrival and departure of the vehicle.

## Features to be added in future

-   Integrate GPS routing system with this mobile application to guide the users to vacant position.
-   Ability to reserve their space in the garage from mobile application.
-   Integrate RFID tag operation with the mobile application for seamless payment facility and update the vehicle occupation within blink of an eye. (fully automated parking    system).

## SWOT Analysis
![SWOT Analysis](https://user-images.githubusercontent.com/59198753/142820086-951e7b7b-8fb1-4132-b224-a5388751bb9f.jpg)

## 4 W's & 1 H
![4w 1h](https://user-images.githubusercontent.com/59198753/142821633-8a7b353d-2478-4df5-90fd-c60b5e75610a.jpg)

## Detail Requirements

### High Level Requirements
| ID    | Description                             | Status              | 
|-------|-----------------------------------------|---------------------|
| HLR01 |Log vehicle details                      |Implemented          |
| HLR01 |Update Parking status in app             |Implemented          |
| HLR03 |Integrate payment portal using RFID Tag  |Future               |
| HLR04 |Guide to vacant space with Routing sensor|Future               |
### Low Level Requirements
| ID    | Description           | Status              | 
|-------|-----------------------|---------------------|
| LLR01 |Open the app           |   Implemented       |
| LLR02 |View the parking status|   Implemented       |
| LLR03 |Connect to GPS         |   Future            |

## 2_Design/Architecture

* Behavioural Diagram low level and high level
![Activity Diagram of Parking Management System](https://user-images.githubusercontent.com/59198753/143300781-e0331be1-8326-47f5-ad75-70f57efd7d1b.png)

![pms](https://user-images.githubusercontent.com/59198753/143300790-6f8c56dd-bf5b-42ff-a9e2-61502a949d6e.png)

* Structural Diagram low level and high level
![Package Diagram of Parking Management System (1)](https://user-images.githubusercontent.com/59198753/143303224-58eeb946-632a-4ec9-befe-e47d97129760.png)

## 3_Implementation

| Folder | Description                                    |              
|------- |------------------------------------------------|
| inc    | All header files                               |                     
| src    | Main source code for parking management system |
| test   | All source code and data for testing purposes  |
| build  | build output                                   |

## 4_TestPlanAndOutput

## TEST PLAN:
### High Level Test plan
| ID    | Description                             | Expected O/P | Actual O/P | Type of Test |
|-------|-----------------------------------------| ------------ | ---------- | ------------ |
| H_01  |obtain vehicle details                   |PASSED        |SUCCESS     | Requirement  |
| H_01  |Verify details                           |PASSED        |SUCCESS     | Scenario     |
| H_03  |Update Parking status in app             |PASSED        |SUCCESS     | Boundary     |

### Low Level Test Plan
| ID    | Description           | Expected O/P | Actual O/P | Type of Test | 
|-------|-----------------------| ------------ | -----------| ------------ |
| L_01  |Open the app           | PASSED       |SUCESS      | Requirement  |
| L_02  |View the parking status| PASSED       |SUCESS      | Scenario     |
| L_03  |Reserve your space     | PASSED       |SUCCESS     | Boundary     |

## 6_ImagesAndVideos

In this directory the output execution is captured in the form of GIF and Images

### Images, Videos and GIFs of execution of code 

![output1](https://user-images.githubusercontent.com/59198753/143302062-7e902e03-3410-42a2-ab39-6f62a5a2236b.png)
![output2](https://user-images.githubusercontent.com/59198753/143302069-2e33477d-099c-4423-990b-c9f71802d4a8.png)
![output3](https://user-images.githubusercontent.com/59198753/143302072-9db5a6bf-7cc8-4a15-9a79-04e85f2c9bba.png)

Output execution GIF:
![parking_management_system](https://user-images.githubusercontent.com/59198753/143302204-42bb98df-d610-4875-a88a-672d6b26df3f.gif)







