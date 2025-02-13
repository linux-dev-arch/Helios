# Helios
A very light weight cli operating system for arduino boards

# How to install 
* Download the arduino sketch from the releases tab.

* Open the sketch in arduino ide

* make some modifications if necessary like changing the amount of temporary storage or adding custom commands or change the baud rate.

* click on upload

# Accessing the CLI

## On Linux 
* use picocom to access the cli by typing the following

 sudo chmod 777 /dev/ttyUSB0
 
  picocom -b 9600 -D /dev/ttyUSB0
## Windows

* Use an app like Putty to access the command line

