# Block Diagram:
![Irrigation](https://user-images.githubusercontent.com/70700323/156915301-116b7dae-c7db-41f9-bfb8-5addd054a777.jpg)

# Sensors:
  * Soil Moisture sensor:
    * The soil moisture sensor is used to measure the volumetric water content of soil. It is used to monitor soil moisture content to control irrigation in greenhouses. A moisture sensor is used to sense the level of moisture content present in irrigation field. It has a level detection module in which we can set a reference value.Soil moisture sensors can send data in both in analog as well as in digital.
    
# Servo Motor:
A servomotor (or servo motor) is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration.It consists of a suitable motor coupled to a sensor for position feedback.

# Relay Module:
The relay module is an electrically operated switch that allows you to turn ON or OFF a circuit using voltage and/or current much higher than a Microcontroller could handle. There is no connection between the low voltage circuit operated by the Microcontroller and the high power circuit. The relay protects each circuit from the other. Each channel in the module has three connections named NC, COM, and NO. Depending on the input signal trigger mode, the jumper cap can be placed at high level effective mode which ‘closes’ the normally open (NO) switch at high level input and at low level effective mode which operates the same but at low level input.

# Water Pump:
A water pump can drain water from a basement or shallow flooded areas, drain and fill a swimming pool or dam. It can also be utilised in the irrigation needed for agriculture. Water pumps are employed for getting rid of excess water to reduce the downtime from large rain events.

# Working Principle:
  *  We are using a soil moisture sensor that,nsenses the moisture content in the soil,send this data to the Arduino.Soil moisture sensors can send data in both. in analog as well as in digital.
  * We insert the soil moisture sensor in the soil and connect it to the Arduino and the sensor sends the data to the Arduino about the moisture inside the soil.
It makes the smart irrigation controller, the Arduino will get the action on the data.
  * If the soil moisture sensor detects no moisture or very little moisture then the pump will get started and water the plants.
  * The water pipe is connected to the servo motor which rotates according to the requirement.
  * If there are two crops A & B and if A has less amount of moisture, then the servo motor rotates toward crop A and starts the watering and when it will fill up it will rotate towards crop B.
 
# Flow Chart:
![Flowchart](https://user-images.githubusercontent.com/70700323/156916834-5e5025e8-d29d-431e-946d-329f86c96f1f.jpg)

# Structural Diagram:
![Structural](https://user-images.githubusercontent.com/70700323/156917455-aaa5f77c-b760-43c2-a8ae-3566e161b525.jpg)










