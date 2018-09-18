# EC463-HWminiproject
This is the github repo of Grabrielle Abad and Lina Lin Wei for Senior Design mini-project.

==OPERATING SYSTEM==
We purchased a 16GB SDCard and installed Raspian onto it.
Due to the short time available, we opted to install Raspian using NOOBS.
The New Out Of Box Software made setting up the raspberry pi much easier.
Moreover, we did not need to download any special imaging software and had a recovery interface which gave us a safety layer if anything goes wrong.
Instruction on how to install NOOBS
://www.raspberrypi.org/documentation/installation/noobs.md

==ADDITIONAL SETUP==
Following the instructions given by Professor Hirsch on GitHub, we connected the raspberry Pi to the internet via wifi(BU's 802.1x). 
To prevent outside users from accessing our Pi, we changed the default password to a more secure one.
After the project, we will format the SDcard and change the Kerberos Password used.
For added security, we could also create another user on the Raspberry Pi. 
With the Raspberry Pi on the BU Wifi, we could easily ssh into the Raspberry Pi.
This allowed us to work without using any monitor. We have also installed screen
Screen allowed us to build on the Raspberry Pi without having to leave the SSH session open.

==INSTALLING OPENCV==
We decided to use OpenCv as the computer vision and machine learning software library.
The main reason behind choosing OpenCv is because it is open-source and has been used extensively by many people.
This meant that problems we would run into, would easily have an online solution. 
Moreover, given our non-computer engineering background, OpenCv was the easiest to install with multiple tutorials on how to.
We followed:https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/
The tutorials were helpfull and well-documented. However, the build time took over 24hr on the Pi.
One improvement we suggest, at this stage, isto cross compile OpenCv on a computer for a Raspberry Pi.

