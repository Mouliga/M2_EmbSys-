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
 
# Sensors:
   * Temperture and Humidity Sensor:
       * The temperature and humidity sensor is necessary to reduce the watering frequency. That is when the weather gets cooler, less water is needed whereas vice versa in the other case.
   * Soil Moisture sensor:
       * The soil moisture sensor is used to measure the volumetric water content of soil. It is used to monitor soil moisture content to control irrigation in greenhouses. A moisture sensor is used to sense the level of moisture content present in irrigation field. It has a level detection module in which we can set a reference value.
    
# Bluetooth Module:
The HC-04 module can be used as a Master as well as a slave device for transmitter and receiver. This means that it can connect to most phones and computers with Bluetooth aw well as to another slave device such as keyboards and other HC-06 modules. To connect with other slave devices a master module would be necessary. It uses the UART protocol to make it easy to send and receive data wirelessly.

# Relay Module:
The relay module is an electrically operated switch that allows you to turn ON or OFF a circuit using voltage and/or current much higher than a Microcontroller could handle. There is no connection between the low voltage circuit operated by the Microcontroller and the high power circuit. The relay protects each circuit from the other. Each channel in the module has three connections named NC, COM, and NO. Depending on the input signal trigger mode, the jumper cap can be placed at high level effective mode which ‘closes’ the normally open (NO) switch at high level input and at low level effective mode which operates the same but at low level input.

# Peristaltic Pump:
A peristaltic pump is a type of positive displacement pump used for pumping a variety of fluids. The fluid is contained within a flexible tube fitted inside a circular pump casing. It is reputed to pump water from a depth of about 31 feet.

# Working Principle:
  * Soil moisture sensor, Temperature and Humidity sensor, Pump all are connected to major component arduino with Bluetooth connectivity.
  * Once the values of temperature and moisture are generated on serial monitor. The threshold can also be notified on serial monitor itself.
  *  And if result of Moisture, Temperature and Humidity goes below the threshold value the pump will automatically turn ON and if the level of Moisture, Temperature and Humidity increase upto threshold level of field then pump will automatically turn OFF.

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

 

