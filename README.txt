                                                         INTELLIGENT FLUID FLOW RATE DETECTION SYSTEM USING RASPBERRY PI
                                                        ==================================================================


INSTALLATION
--------------------
First open terminal in raspberry pi then enter this commands

1. sudo apt-get update

2. sudo apt-get upgrade

3. sudo apt-get install RPi.GPIO
then reboot by entering this command

4. sudo reboot
then connect lcd pin to raspberry pi GPIO
RS =26
EN =19

data pin of lcd (D4, D5, D6, D7) to
D4 =13
D5 =6
D6 =5
D7 =11

Now connect loadcell to rasberry pi GPIO
DT=9
SCK=8

Now connet motor to rasberry pi GPIO
motor=23

Now connect Triggering pin (reset) to rasberry pi GPIO
key=25

then create Folder on Desktop then open terminal enter this
CD Desktop

then create a file by entring this command
sudo nano File name .py 

then create code in it

to save this code enter 'ctrl+x' and enter 'y' and press enter

then to execute python code on pi enter this code

5. sudo python file name .py 


