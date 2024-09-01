---
title: "Inventory Dispensing System"
date: 2022-06-25T18:35:46+05:30
draft: false
layout: "project_x"

description: "Smart Cupboard for Issuing Lab Inventory."
carousel:
  items: 1
  duration: 7000
  height: 35
  unit: "rem"
  images:
   - image: /images/projects/IDS.jpg
     caption: Inventory Dispensing System
   - image: /images/projects/raspberry_pi_ids.jpg
     caption: Raspberry Pi with RFID Scanner
   - image: /images/projects/arduino_ids.jpg
     caption: Cupboard PCB, Arduino and Amplifiers
   - image: /images/projects/bin_ids.jpg
     caption: Storage bin with Proximity Sensor
   - image: /images/projects/connection_graph_ids.jpg
     caption: Communication Graph
credits: "Members: Preet Shah and Videh Patel"
# checkout:
#   links:
#     - icon: fab fa-github
#       url: https://github.com/videh25/3D-Simulation-of-Standard-Manipulators
content: |-
    
    My best and most hard-work drenched project of BTech, as a part of Mechatronics course offered	 by Prof. Madhu Vadali. To cater the need of students working late nights in 	Tinkerers’ Lab (student run makerspace of IITGn), we ideated, designed and prototyped an Inventory Dispensing System.
    This mechatronic system consists of a Raspberry Pi, connected to an RFID sensor and the internet; and cupboards, consisting of Arduino Nanos and load cells. All of them are connected over an I2C network with Raspberry Pi as the master and Arduinos as slaves. Once the user scans a valid RFID card, the cupboard unlock.  Arduinos sense the number of items taken/returned by the user through load cell readings and Raspberry Pi updates an online database with the information.

    Do check out the infomercial! ^_^

---