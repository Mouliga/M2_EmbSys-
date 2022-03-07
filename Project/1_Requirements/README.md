# SECURITY SYSTEM:

# Introduction:
Security is an important part of home, especially if we are going to share a house with prior strangers without a lock on our room door. This system has ultrasonic sensors which are responsible for the detection of intrusion. The ultrasonic sensor we use are HC-SR04. The controlling modules are Arduino UNO board.

# Advantages:
  1. The security system is more secure, is reliable, enabling real-time awareness and alerts from your home, and combating many of the vulnerabilities you will find on other        types of system.
  2. The system is easier to install with faster support.
  3. It is easy to replace an existing system or add a new functionality.
  4. The system is flexible and versatile. 
  5. It is easy to implement and expand the system. 
  6. It is the foundation of a true smart home. 
  7. It is cost effective.

# Disadvantages:
  * There is limited distance under which sensor can detect the object.
  * The ultrasonic sensor provides 2cm to 400cm of non-contact measurement functionality with a ranging accuracy that can reach up to 3mm only.
  * The thief can also jam the signal produced by the sensor that can take the sensors anywhere from a few minutes to three hours to reestablish communication.
 
# Components:
  * Arduino
  * Servo motor
  * Ultrasonic sensor
  * LCD Screen
  * 10K Potentiometer
  * Resistor (220 ohms)
  * Breadboard

# Requirements:
# High Level Requirements:
ID   |        Description
---- | -----------------------------------------------------------------------
HLR1 |   It shall controls the data and sense the devices
HLR2 |   It shall controls the position of ultrasonic sensor
HLR3 |   It shall detects the intruders on their physical presence
HLR4 |   It shall displays the output

# Low Level Rquirements:
ID   |        Description                                                    | HRL ID
---- | --------------------------------------------------------------------- | -------------
LLR1 |   Arduino contols the data of the devices used                        |  HLR1
LLR2 |   Servo motor helps sensor to cover larger area                       |  HLR2
LLR3 |   Ultrasonic sensor can measure the distance to an obstacle 
         within its conic beam.                                              |  HLR3
LLR4 |   LCD screen displays the output                                      |  HLR4


 

