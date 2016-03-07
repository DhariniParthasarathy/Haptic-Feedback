# Haptic Feedback  
ECE 387 Midterm

Miami University, Spring 2016

# Overview

**Input:** Flex Sensor  
**Output:** Vibration Motor  
**Micro-controller:** Arduino Uno  
**Chip:** DRV2605L Haptic Motor Controller

**Description:** The DRV2605L is a motor driver specifically designed to control haptic motors, such as vibration motors. This driver has the ability to have various effects when driving a vibrator motor. For example, ramping the vibration level up and down, 'click' effects, different buzzer levels, or even having the vibration follow a musical/audio input. 

This project is part of our ECE 387 group project--'Glove-Controlled Mouse.' With flex sensors acting as inputs, haptic feedback will be provided when the sensors are flexed in a particular configuration. These configurations are right and left clicking, scrolling, etc. For this midterm, I am working with one flex sensor as the input. I will model different outputs using the vibration motor and the haptic motor controller. This is so that I will be able to assemble the haptic feedback component into the group project with fewer debugging issues. 