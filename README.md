# cbr250rri
This repository contains a collection of hardware & software projects related to the CBR250RRi motorcycle project.

The CBR250RRi project is a long term project involving modifying a 1996 Honda CBR250RR motorcycle. The most significant change was to convert from carburettors to fuel injection. The project has included building custom hardware modules to carry out specific tasks. The details of these additional hardware & software projects are included here.

See website https://www.cbr250rri.com/ for further project details.



## CAN Dash Controller

Teensy 3.2 based controller board designed to recieve engine data from ECU via CAN-Bus and use it to control a Koso RX2N motorcycle dash.


## MAP-CMP Sensor

Small module designed to output an engine phase signal (camshaft posn) based on a single cylinder inlet port pressure trace.


## GPS-IMU CAN Module

Teensy 3.2 based controller board designed to collect GPS & IMU data from SkyTraq Venus838LPx and Bosch BNO055 breakout boards and transmit the data via CAN-Bus.


## CAN Datalogger Module

Teensy 3.2 based CAN-Bus data logger module. Data is recieved via CAN-Bus and written to a microSD card in raw binary format. A Python script is used to convert the binary log files to csv using a CAN DBC file.
