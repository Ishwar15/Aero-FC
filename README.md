# Aero-FC
### Communicating with raspberry pi

>sudo apt-get update

>sudo apt-get install python3-dev python3-opencv python3-wxgtk4.0 python3-pip python3-matplotlib python3-lxml python3-pygame

>sudo pip install pymavlink

>sudo pip install mavproxy

>sudo raspi-config

>enable serial port of rasperry bi in serial 

>nano /boot/config.txt

>ls /dev/tty*

>sudo -s

mavproxy.py --master=/dev/ttyAMA0 --baudrate 921600 --aircraft MyCopter
