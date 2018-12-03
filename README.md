# INCUBE.CO: Automation-Dashboard
The Automation Dashboard is the springboard for our development of home automation solutions.
It is made of several different hardware and software components:

## Hardware
- *Raspberry Pi* (Real-Time/Reactive Web App Server, MQTT Broker)
- *NodeMCU* boards (Remote I/O controllers and feedback - MQTT Clients)
- Electronics (Relays, Motor Drivers, Sensors, etc.)

## Software
- *Meteor*/Javascript (Mobile/Web App Software)
- *Arduino IDE* (NodeMCU software)

# Setup / Configuration
## Raspberry Pi
### Download Noobs/Rasbian

### Setup environment (ssh/no GUI/etc)

### Install Mosquitto

### Install Meteor

### Create Project
Our next step is to create the project environment.  Begin by creating the meteor project.
> $ meteor create home-automation

This creates the directory in the /home/pi directory

### Add / Remove Packages
Now we need to add the packages that we need.  And remove the ones we don't.  Make sure you are in the project directory before using the *meteor* commands.

MQTT Support - We want to expose our project to the MQTT.js package.
> $ meteor add mkarliner:mqtt

## Arduino IDE
- Install Arduino IDE
- Add Libraries for NodeMCU
- Add Libraries for MQTT
- Add Libraries for Ping

## NodeMCU Firmware
- Get firmware
-- Set it up with MQTT libraries installed
- NodeMCU Pinouts

# Code
## Meteor

## Arduino
