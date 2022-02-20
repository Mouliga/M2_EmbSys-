# SMART REFRIGERATOR USING IOT

# Introduction:
 
 A refrigerator is an essential household appliance and it is the most frequently used appliance within the household to store food items and drinks. Improvement in technology has created  an  effective  impact  on  kitchen  room  appliances. Refrigerator has made human lives more convenient keeping food fresh and preventing spoilage. Over time there has not been  much  improvement  in  the  features  since  the  basic function  of  refrigerator  is to  keep things  cool  and  people didn’t prefer  any additional features for which the cost of a product  is  increased  but  in  the  recent  times,  intelligent refrigerators  are  introduced which  are  not well  known  to many people. A smart refrigerator is which has connectivity to the internet through the Internet of Things where it can do a lot  more  other  than  just  keeping  food  cool. The  Smart refrigerator proposed  in this  paper provides  the user  with SMS notifying shortage of food amount present in the fridge and has the ability to order shortage food items online like milk, butter, etc. or messages the nearby grocery store for the order to refill the items  of quantity insisted by the user. It jointly senses  temperature,  humidity  and  displays  them  in order to scale back spoilage of food. The smart fridge also has the  ability  to  tell  if  the  door  is  kept  open  by  giving  a notification via mobile  or web application. The smart refrigerator or the internet refrigerator as it is called, is used to monitor the items inside it and notify about scarce products.
 
 # Description:
 
 The system comprises of minimum four sections where the sensors are placed Proximity sensors areplaced along with a counter which can be used to sense the number of eggs inside the refrigerator, also they are used to detect the level of milk and soft drinks in the container. The fourth application is to sense the presence of vegetables in the refrigerator which is being done with the help of pressure sensors which has a threshold of 500gm approximately. Whenever the contents inside the refrigerator goes below the set threshold it generates a trigger which is being transmitted in the form of message to the user. The another application is to check whether ice is ready, and give indication on front panel of refrigerator. This system is based on Internet of Things so all the data from the sensors is provided to microcontroller and through microcontroller it will be
placed on the cloud through Wi-Fi chip interfaced to the controller. User will have android app which will download data from cloud so as the user can monitor contents as well as he/she can control the refrigerator remotely through internet.

# COMPONENTS:

# SENSORS:
These field sensors are fitted in Refrigerator where bottles are stored, one for each bottle. They are object sensors and if not found any object in front of them, they produce NO Object signal which is fed to Object Detector Unit for further processing. 

# OBJECT DETECTOR UNIT: 
This unit generates NO Object alert signal corresponding to field sensors signal, which is server’s software format. This server understandable alert signal is fed to input port of server through suitable Interfacing stage.

# INTERFACING STAGE:
As server needs TTL compatible level signals at its input port, suitable interfacing stage must be introduced before feeding field signals directly to it to avoid any kind of damage.

# TEMPERATURE SENSOR: 
It is used to measuring the temperature in main compartment and freezer. Also used to compare the room temperature to auto-off the refrigerator.

# GAS SENSOR:
A gas detector is a device that detects the presence of gases in an area, often as part of a safety system. This type of equipment is used to detect a gases produced by vegetables. Gas detectors can be used to detect combustible, flammable and toxic gases.

# PROXIMITY SENSOR: 
A proximity sensor is a sensor able to detect the presence of nearby objects without any physical contact. In smart refrigerator these sensors are used to detect the absence of eggs or any regular items. 

# LOAD  CELL:
Over weighting detection in compartment of refrigerator can be detected using load cell.

# WORKING:

The Arduino Uno is a microcontroller board based on the ATmega328. It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz crystal oscillator, a USB connection, a power jack, an ICSP header, and a reset button. We are using sensors like Temperature sensor, Load cell, Proximity sensor, Gas sensor, Push buttons which will sense respective parameters and that values will be sent to the Arduino board. Then according to the received values from sensors Arduino will take particular action specified in program stored inside memory of Arduino. The output devices like LCD, Buzzer are used to display warnings to the user as well as Buzzer will be blown so that user can understand warning from refrigerator. Android app is made for both user as well as shopkeeper. When things go below threshold level that indication will be given to the user’s app then user will place the order if necessary. If user places order, then shopkeeper’s app will get notification regarding order then he will deliver that product to user’s home.


