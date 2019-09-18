## GreenPonik_PH.py Library for Raspberry pi
---------------------------------------------------------
This is the sample code for Gravity: Analog pH Sensor / Meter Kit V2, SKU:SEN0161-V2
## Table of Contents

* [Installation](#installation)
* [Methods](#methods)
* [Credits](#credits)
<snippet>
<content>

## Installation

Dependencies:

The Analog pH Sensor should work with ADS1115
[DFRobot_ADS1115](https://github.com/DFRobot/DFRobot_ADS1115/tree/master/RaspberryPi/Python) 

Run the program:

```shell

$> python3 GreenPonik_PH.py

```
## Methods

```Python

"""
@brief Init The Analog pH Sensor
"""
def begin(self);

"""
@brief Convert voltage to PH with temperature compensation
"""
def readPH(self,voltage,temperature);

"""
@brief Calibrate the calibration data
"""
def calibration(self,voltage,temperature);

"""
@brief Reset the calibration data to default value
"""
def reset(self);

```

## Credits
Writter by Mickael Lehoux, from [GreenPonik](https://www.greenponik.com), 2019

based on [DFRobot library](https://github.com/DFRobot/DFRobot_PH/tree/master/RaspberryPi/Python)
