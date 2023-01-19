# RPI and Arduino Serial communication
Serial communication is simply a way to transfer data. The data will be sent sequentially, one bit at a time (1 byte = 8 bits), contrary to parallel communication, where many bits are sent at the same time. Two Basic resources to write the USB serial communication protocol between Arduino and Raspberry Pi.


## Arduino to RPI
Serial arduino library is used for communication between the Arduino board and a computer or other devices. All Arduino boards have at least one serial port (also known as a UART or USART), and some have several.  [reference](https://www.arduino.cc/reference/en/language/functions/communication/serial/)

## RPI to Arduino
PySerial is a python library for serial communication which can open a port. It provides backends for Python running on Windows, OSX, Linux, BSD (possibly any POSIX compliant system) and IronPython. The module named “serial” automatically selects the appropriate backend. [Reference](https://pyserial.readthedocs.io/en/latest/pyserial_api.html)
