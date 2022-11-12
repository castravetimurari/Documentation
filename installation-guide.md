---
description: Flash your air and ground unit with OpenHD firmware
---

# Installation Guide

Prerequisites:\
1\) A windows or linux PC (otherwise, read "manual install" below)\
2.1) For hardware that doesn't have soldered memory (e.g. RPI4): SD card reader and a high quality SD card at least 8GB in size (16GB or higher is recommended)\
2.2) For hardware with soldered memory (e.g. Ochin & CM4 with eMMC): High quality USB cable\
\
Step 1:\
Download and install the latest OpenHD imager (based on rpi imager) from \
[https://github.com/OpenHD/OpenHD-ImageWriter](https://github.com/OpenHD/OpenHD-ImageWriter)\
![](<.gitbook/assets/Screenshot from 2022-11-12 16-46-44.png>)\


Step 2: (Only CM4 with emmc): Connect your CM4 via USB and initialize flashing (TODO)\
\
Step 3:\
Open up the imager and select the latest OpenHD release from the drop down. The imager will automatically download the selected image. You can also download the image manually and flash it using the "Custom image" selector.

![](<.gitbook/assets/Screenshot from 2022-11-12 16-47-39.png>)\
\
Step 4:\
Insert your SD card into the card reader, and select it from the "Choose storage" option. If you are using a CM4, it'l show up like an SD card.\
\
Step 5:\
Click on "Settings" on the lower right corner and select either air or ground (depending weather you want to flash an air or ground image). You cannot skip this step.\
\
Step 6:\
Flash your image by clicking on "Write". This might take a while.&#x20;

\