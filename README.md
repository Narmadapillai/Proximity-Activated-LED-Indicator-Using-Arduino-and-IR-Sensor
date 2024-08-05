# Proximity-Activated-LED-Indicator-Using-Arduino-and-IR-Sensor

Objective:

To build a system where an LED blinks whenever the IR sensor detects an object within its proximity range. This can be used in various applications, such as a simple object detection system or a proximity alert.

Components                                                 

1. Arduino  UNO                                                  

2.  IR sensor                                                    

3.  LED                                                           

4.  Jumper Wires

   Working Principle:

IR Sensor Operation: The IR sensor emits infrared light from an LED and detects the reflected light with a photodiode. When an object comes within the sensor's range, the amount of reflected light changes, causing the sensor’s output to switch state.

Arduino Processing: The Arduino reads the output from the IR sensor. If the sensor detects an object (i.e., the output is HIGH), the Arduino sends a signal to turn the LED on and then off, causing it to blink.

LED Indicator: The LED blinks in response to the sensor's detection of an object. The blinking behavior is controlled by the Arduino based on the sensor's output.

Circuit Connections:

IR Sensor VCC connects to Arduino 5V to provide power.
IR Sensor GND connects to Arduino GND to complete the circuit.
IR Sensor OUT connects to Arduino Digital Pin 2 to read the sensor’s output.
LED Anode (+) connects to Arduino Digital Pin 13 through a 220-ohm resistor.
LED Cathode (-) connects to Arduino GND.

Applications:

Object Detection Systems: Used in security systems to detect when someone approaches.
Interactive Displays: Can be part of exhibits or interactive installations.
Proximity Alerts: Simple proximity alerts for devices or environments where detecting nearby objects is crucial.
