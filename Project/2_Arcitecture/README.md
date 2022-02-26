# Block Diagram:

![Arcitecture](https://user-images.githubusercontent.com/70700323/155831607-19ebdbdc-8fb0-4895-a9e9-967b26b59f9a.png)

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
 
# Behaviour Diagram:
![image](https://user-images.githubusercontent.com/70700323/155832480-8e7f4ec6-8e2f-41f4-949b-eb774801217b.png)







