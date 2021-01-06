# SEN0240_Demo
This repository contains code and documentation on how to collect data from an SEN0240 Electromyography sensor.
With this repoitory you should be able to visualise simple muscle contravtion.

## Hardware needed

A [SEN0240](https://www.dfrobot.com/product-1661.html) is needed to get muscle contraction info.
An [Arduino](https://store.arduino.cc/) (or similar) to compute data from SEN0240.

## prerequisite

If you are using a clone of arduino please download firmware to detect device in Arduino firmware.

It should now appear fine in [Arduino IDE](https://www.arduino.cc/en/Main/OldSoftwareReleases) under tools => port.

## Connection

The SEN0240 control board should look like this.

![](img/Emg_board_function2.png)

| Port    | Description       | Connected to          |
| --------|-------------------|-----------------------|
| 1       | Data port         | Arduino A0 pin        |
| 2       | Anode             | Arduino 3V or 5V power|
| 3       | Cathode           | Arduino GND           |
| 4       | Censor Connector  | Censor port           |

The connection to the Arduino should look like this

![](img/Emg_schema.png)

## Censor position
TBD
