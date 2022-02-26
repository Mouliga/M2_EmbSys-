# SMART IRRIGATION SYSTEM:

# Introduction:
Automatic Irrigation system monitors the soil moisture and depending on set points turns on/off the pump which is connected to the relay. This way you can keep soil moisture to a set point.This system automatically waters the plants when we are on vacation. As we are setting the soil moisture level, we need not worry about too much of watering and the plants end up dying anyway.The project is designed to develop an automatic irrigation system which switches the pump motor ON/OFF on sensing the moisture content of the soil.

# Advantages:
  1. Smart irrigation systems can optimize water levels based on things such as soil moisture and weather predictions.
  2. Long Term Enhanced Landscape Health.
  3. Project The Community’s Water Supply For Generations.

# Disadvantages:
  * Smart watering system is a bit expensive.
  * Depending on the size of your property, you will need more systems. Of course saving on water bills will lead to less cost. If you want to use this system for lawn watering, it's better to fix it under the ground before planting.

# Components:
  * Arduino
  * Bluetooth Module	
  * Temperature and Humidity Sensor	
  * Soil moisture sensor	
  * Peristaltic pump	
  * LEDs	Red, Green and Yellow	
  * Miscellaneous		
  * Adaptor	
  * Connecting Jumpers		
  * Breadboard

# Requirements:
# High Level Requirements:
ID   |        Description
---- | -----------------------------------------------------------------------
HLR1 |   It shall controls the data and sense the devices
HLR2 |   It shall transfers the data,when the data is received
HLR3 |   It sahll recives the data, when the data is transfered
HLR4 |   It shall measures the moisture level
HRL5 |   It shall measures the temperature and air surrounding environment
HLR6 |   It shall automatically ON/OFF the circuit

# Low Level Rquirements:
ID   |        Description                                                    | HRL ID
---- | --------------------------------------------------------------------- | -------------
LLR1 |   Arduino contols the data of the devices used                        |  HLR1
LLR2 |   Bluetooth module can transfer and receive the data and vice-versa   |  HLR2,HLR3
LLR3 |   Moisture sensor detects the water content of the soil               |  HLR4
LLR4 |   Temperature and Humidity sensor detects the water frequency and air |  HLR5
LLR5 |   Relay circuit allows automatic ON/OFF the circuit                   |  HLR6

 

