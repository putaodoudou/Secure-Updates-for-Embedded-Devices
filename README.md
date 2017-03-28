# Secure-Updates-for-Embedded-Devices
IoT security has not been fully looked at, and mostly how updates are delivered to embedded devices.  This project implements PKI on the update mechanism of embedded devices

-----------------------------------------------
Getting the script on your Pi

You can either cut and paste the above code into a nano window on your pi, like thisÖ

nano pwm2.py
cut and paste the above code from this page
CTRL+O
y
CTRL+X

Or, type the following directly from the command line (e.g. LXTerminal) on your PiÖ

wget http://raspi.tv/download/pwm2.py.gz
gunzip pwm2.py.gz

Either way, after that you can run it with

sudo python pwm2.py (But you will need RPi.GPIO 0.5.2a or higher)
