# DC-Motor-Control Library
![DC Motor Control PCB](https://github.com/Infineon/Assets/blob/master/Pictures/DC-Motor-Control.jpg | width=300)
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

# PCB Design Data
In case you want to change the design or reuse it for your own projects, please find the XMC 2Go board design for EAGLE under the following link:

[DC Motor Control Shield Design Data](https://www.infineon.com/dgdl/Infineon-DC_Motor_Control_Shield-PCB-v01_00-EN.zip?fileId=5546d4624cb7f111014cc23eebe1325f&sd=t)

# Board Information, Datasheet and Additional Information
A PDF summarizing the features and layout of the DC motor control shield is stored on the Infineon homepage [here](https://www.infineon.com/dgdl/Infineon-Motor_Control_Shield_with_BTN8982TA_for_Arduino-UM-v01_00-EN.pdf?fileId=5546d4624ca27d02014cb20b89867eed).
The datasheet for the BTN8982TA can be found here [BTN8982TA Datasheet](https://www.infineon.com/dgdl/Infineon-BTN8982TA-DS-v01_00-EN.pdf?fileId=db3a30433fa9412f013fbe32289b7c17) while the respective application note is located here [NovalithIC™ half-bridge family BTN89xy](https://www.infineon.com/dgdl/Infineon-NovalithIC_BTN89x0-x2-AN-v00_05-EN.pdf?fileId=db3a30433fa9412f013fc8d88e3d430a).
