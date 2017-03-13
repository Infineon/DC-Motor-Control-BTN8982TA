# DC-Motor-Control Library
Library of Infineon's [DC motor control shield](https://www.infineon.com/cms/en/product/productType.html?productType=5546d4624ad04ef9014b07c0c07922e0) for Arduino. 

## Summary
The DC motor control shield is a high current motor control board being compatible to Arduino. It is capable to drive two uni-directional DC motors (half bridge configuration) or one bi-directional DC motor (H-Bridge configuration). The implemented integrated [BTN8982TA NovalithIC™](https://www.infineon.com/cms/de/product/power/motor-control-and-gate-driver-ics/intelligent-motor-control-ics/single-half-bridge-driver/BTN8982TA/productType.html?productType=db3a30443ef951e3013f0f6c88742068) half bridges can be controlled by a PWM via the IN Pin. Interfacing to a microcontroller is made easy by the integrated driver IC which features logic level inputs, diagnosis with current sense, slew rate adjustment, dead time generation and protection against overtemperature, undervoltage, overcurrent and short circuit.

## Key Features and Benefits
* Compatible with Arduino Uno R3
* Capable of high frequency PWM e.g. 30kHz
* Adjustable slew rates for optimized EMI by changing external resistor
* Driver circuit with logic level inputs
* Diagnosis with current sense
* Protection e.g. against overtemperature and overcurrent
* Fast and inexpensive prototyping of DC motor control
* Easy testing of half and full bridge motor control
* Status flag diagnosis with current sense capability
* Overtemperature shut down with latch behavior and undervoltage shut down

## Installation

## Usage
Please follow the examples in the /examples directory in the library to learn more about the usage of the library.
