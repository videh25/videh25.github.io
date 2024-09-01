---
title: "Ball On Beam"
date: 2022-06-25T18:35:46+05:30
draft: false
layout: "project_x"

description: "Smart Beam that Balances a Ball"
carousel:
  items: 1
  duration: 7000
  height: 35
  unit: "rem"
  images:
   - image: /images/projects/BallOnBeam.gif
     caption: The system at work!
   - image: /images/projects/cad_bob.jpg
     caption: CAD model for the setup.
   - image: /images/projects/team_bob.jpeg
     caption: "The Team: Trans-Idea"
credits: "Members: Aryan Shah, Videh Patel, Sanskar Nalkande, Tej Patel, Sresth Tosniwal"
# checkout:
#   links:
#     - icon: fab fa-github
#       url: https://github.com/videh25/3D-Simulation-of-Standard-Manipulators
content: |-
    
    A standard project trying to get hands dirty with Control Theory. 

    Our objective was to balance a ball on a beam equipped with an IR sensor, stepper motor and an arduino. We implemented a PD controller with feedback linearization to  balance the ball at any desired point on the beam.

    **Cool story:** Once we had completed building the setup, we realized that the stepper motor was not able to generate the torque large enough to move the beam. It was a Eureka moment for us to realize that we can hang some stones on the other side of the motor's lever and use counterweight to generate the missing torque!


---