To clone this repo:<br>
`git clone https://github.com/conciseusa/raspberry-pi-pico-w-temperature-controller.git`<br>

Cheatsheet version of:<br>
https://projects.raspberrypi.org/en/projects/get-started-pico-w/0
[Getting started with your Raspberry Pi Pico W](https://projects.raspberrypi.org/en/projects/get-started-pico-w/0)<br>
Then added a control loop for controlling temperature.<br>

sudo apt install python3-tk thonny # If do not have installed already<br>
Download the latest version of Raspberry Pi Pico W firmware at:<br>
[https://rpf.io/pico-w-firmware](https://rpf.io/pico-w-firmware)<br>

Hold down the BOOTSEL button<br>
Connect USB cable from the Raspberry Pi Pico W to a desktop computer, laptop, or Raspberry Pi<br>
Release the BOOTSEL button after 2 seconds<br>
Raspberry Pi Pico should show as an externally connected drive.<br>
Drag and drop the firmware file you downloaded into the file manager.<br>
Raspberry Pi Pico should disconnect.<br>
Open the Thonny editor.<br>
Check text in the bottom right-hand corner of Thonny.<br>
If it does not say ‘MicroPython (Raspberry Pi Pico)’, click on the text and select ‘MicroPython (Raspberry Pi Pico)’<br>
In Thonny, choose Tools > Manage packages<br>
picozero -> Ctrl-V to box ->Search on PyPi<br>
Click on picozero in the search results. Click on Install.<br>
Seemed to already be installed on Ubuntu 22.04<br>

Now should be able to open and run the .py files in this repo.
