# Drowsy-Driver-Detection
## Problem Statement: Many accidents occur every year relating to drowsy drivers. When tired drivers drive, they can get into accidents.

## Solution: Use xiao esp32s3 sense for model deployment. If the driver is drowsy, use a buzzer to make a beep sound. Else, do not make a sound.

## Materials
  1. Xiao esp32s3 Sense
  2. Buzzer
  3. 3d design for case
  4. Jumper Cables
  5. Sodlering Iron & other soldering materials

## Step 1 - Edge Impulse Model Training
   1. Used Roboflow dataset and uploaded onto Edge Impulse
   2. Ran basic model training on Edge Impulse

## Step 2 - Deploy Model as Arduino Library
  1. Make sure Model is int8 quantanized format before deploying
  2. Deploy Model as Arduino Library

## Step 3 - Upload Code File --> drowsy.c

## Step 4 - Solder Buzzer onto Xiao Esp32s3 sense

## Step 5 - 3d print case for the Device

## Done!! 
