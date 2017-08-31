# Drivers mxu11x0

* Connect the Moxa to the PC through USB.
* Install the driver by executing as root the command "./mxinstall"
* Run the command "dmesg | grep tty" to check where the device has been connected.
* Run "socat - /dev/ttyUSB[X]" to send AT commands to the device
