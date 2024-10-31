# Drowsy-Driver-Detection
## Problem Statement: Many accidents occur every year relating to drowsy drivers. When tired drivers drive, they can get into accidents.

## Solution: Use xiao esp32s3 sense for model deployment. If the driver is drowsy, use a buzzer to make a beep sound. Else, do not make a sound.

## Materials
  1. Xiao esp32s3 Sense
  2. Xiao expansion board
 3. 3d design for case
 ![Screenshot 2024-10-30 at 9 03 18 PM](https://github.com/user-attachments/assets/d79a8414-7aa7-4bb6-a70e-e047fd1166b8)
## Step 1 - Edge Impulse Model Training
   1. Used Roboflow dataset and uploaded onto Edge Impulse
   2. Ran basic model training on Edge Impulse
![Screenshot 2024-10-30 at 9 01 50 PM](https://github.com/user-attachments/assets/68dae959-e43a-475d-9cfc-d542705e6360)
## Step 2 - Deploy Model as Arduino Library
  1. Make sure Model is int8 quantanized format before deploying
  2. Deploy Model as Arduino Library
  ![Screenshot 2024-10-30 at 9 00 00 PM](https://github.com/user-attachments/assets/5fbac9be-b14e-4d80-85b0-736a7fe7d093)


## Step 3 - Upload Code File --> drowsy.c
   1. Uploading will take some time please be patient!
   2. If not displaying results press reset or reboot button
![Screenshot 2024-10-30 at 8 57 55 PM](https://github.com/user-attachments/assets/bc937236-31c6-46dc-9e11-7f8528fcdabb)

Done!!!

