# Table of content:
## 1.About the Smart switch
###  i.Description
### ii.Identifying features
### iii.State of art
### iv.5W’s & 1H and S.W.O.T analysis
## 2.Requirements:
### i.High level requirements
### ii.Low level requirements
## 3.Design:
### i.Behaviour Diagram
#### a.High Level Flow chart Behavioural Diagram
#### b.Low Level Flow chart Behavioural Diagram
### ii. Structural Diagram
#### a.High Level UML Use Case Structural Diagram
#### b.Low Level UML Use Case Structural Diagram
## 4.Test plan and Output
### High level test plan
### Low level test plan

# About the Smart Switch
## 1.1 Description:
# **Introduction**

### A Smart Switch is an system that controls the accessories so as to activate home appliances and to permit for various ways that of preparation, the smart switch system wants a mechanism  for communication between the  various devices within the system, and for coordination among the varied processes running on such devices.

### The Smart Switch is known as application of IOT based Home automation, with the use of new technology, to make the domestic activities more convenient, comfortable, secure and economical. These switches can be controlled remotely. It   saves   energy   and   makesoperation   of   assorted   accessories of home application   additional   convenient.   It involves the automatic dominance of electrical devices in homes or perhaps remotely through wireless communication. 
## 1.2 Features:
### It shall  connect to the internet via home/office network.
### It shall be an online grid, it can be accessed from anywhere.
### It shall display the status of the switch.
### It shall  control the functionality of the switch via an app(remote access).
### It shall be  controlled and accessed digitally you can automate tasks based on time.
### It shall have one smart switch in your setup, they can be controlled together say, wheather the status of the power is turned on or off.

## 1.3 State of art
### The main objective of this project is to develop a smart switch using an Arduino board with wifi being remotely controlled by any Android OS smart phone. As technology is advancing so houses are also getting smarter. Modern houses are gradually shifting from conventional switches to centralized control system, involving remote controlled switches. Presently, conventional wall switches located in different parts of the house makes it difficult for the user to go near them to operate. Even more it becomes more difficult for the elderly or physically handicapped people to do so. Remote controlled home automation system provides a most modern solution with smart phones. In order to achieve this, a Bluetooth module is interfaced to the Arduino board at the receiver end while on the transmitter end, a GUI application on the cell phone sends ON/OFF commands to the receiver where loads are connected. By touching the specified location on the GUI, the loads can be turned ON/OFF remotely through this technology. The loads are operated by Arduino board through opto isolators and thyristors using triacs.

# Swot Analysis
![swot analysis](https://user-images.githubusercontent.com/47137831/160228006-07574b48-62bc-4bbf-951b-1f6777abde99.png)






# 5W's 1H
![5wh1](https://user-images.githubusercontent.com/98865218/160111347-1eddd85a-bf31-40ab-bf92-4d76d3fbc30a.png)



# High Level Requirements 


|ID|status|Description|
|:----:|:---:|:----:|
|HLR_01|Press switch 1| It shall operate Air conditioner |
|HLR_02|Press switch 2| It shall operate LightBulb|
|HLR_03|Press switch 3| It shall operate fan|
|HLR_04|Press switch 4| It shall see status of Bulb/Fan/Air conditioner |

# Low Level Requirements

## Low Level Requiremets for HLR_01

|ID|status|Description|
|:----:|:---:|:----:|
|LLR_01|Light glow| if client press switch "1"|
|LLR_02|Light off |if client press switch "0" |

## Low Level Requiremets for HLR_02

|ID|status|Description|
|:----:|:---:|:----:|
|LLR_01|Fan ON| if client press switch "2"|
|LLR_02|Fan OFF| if client press switch "0"|

## Low Level Requiremets for HLR_03

|ID|status|Description|
|:----:|:---:|:----:|
|LLR_01|Air conditioner ON |if client press switch "3"|
|LLR_02|Air conditioner OFF|if client press switch "0"|

##  Low Level Requiremets for HLR_03

|ID|status|Description|
|:----:|:---:|:----:|
|LLR_01|client can see the status of the bulb/fan/Air conditioner |if press switch "4"|

![Screenshot (250)](https://user-images.githubusercontent.com/98865009/160227491-9d9e2d8c-5107-4333-991c-24014eb31101.png)

