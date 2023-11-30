# HAM-UAV

the project for SAUVC2024

## block diagram 

![block diagram](https://github.com/leemark00/HAM-AUV/assets/46148445/89d07444-5e86-43cf-9cbf-d0b7a68bb625)

## to-do

[O] 


## important

.    patch raspberry pi 3b according by 
Open source.list

    sudo nano /etc/apt/source.list

comment the current line by adding # in the front of the line, it would be something like this after adding comment to the line:

    #deb http://raspbian.raspberrypi.org/raspbian/ bullseye main contrib non-free rpi
then add at the end of the file:

    deb http://mirror.ossplanet.net/raspbian/raspbian/ bullseye main contrib non-free rpi
After that ctrl+s to save the changes now update

    sudo apt update
then

    sudo apt upgrade

