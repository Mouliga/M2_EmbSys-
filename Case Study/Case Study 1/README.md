# WATER LEVEL INDICATOR:
 
# Introduction:

A water level indicator is a system that relays information back to a control panel to indicate whether a body of water has a high or low water level. Some water level indicators use a combination of probe sensors or float switches to sense water levels. The purpose of a water level indicator is to gauge and manage water levels in a water tank. The control panel can also be programmed to automatically turn on a water pump once levels get too low and refill the water back to the adequate level. A water level indicator sensor, also known as a probe sensor, is what tells the control panel that corrective action is needed. A combination of high and low sensors are used to tell the control panel when water are too high or too low. The control panel will then automatically turn the pump on or off depending on the corrective action needed.

# Description:

The Water Level Indicator employs a simple mechanism to detect and indicate the water level in an overhead tank or any other water container. The sensing is done by using a set of nine probes which are placed at nine different levels on the tank walls (with probe 9 to probe 1 placed in increasing order of height, common probe (i.e. a supply carrying probe) is placed at the base of the tank). The level 8 represents the “tank full” condition while level 0 represents the “tank empty” condition.

When the water-level is below the minimum detectable level, the seven segment display is arranged to show the digit 0, indicating that the tank is empty, when the water reaches level1 (but is below level2) the connection between the probes gets completed (through the conducting medium – water) and the base voltage of transistor increases.

This causes the base-emitter junction of transistor to get forward biased, this switches transistor from cut-off to conduction mode thus PIN (B7) of microcontroller is pulled to ground hence, the corresponding digit displayed by the seven segment display is 1.

The similar mechanism applies to the detection of all the other levels. When the tank is full, all input pins of microcontroller become low. This causes the display to show 8 and also in this case a buzzer sound is given, thereby indicating a “tank full” condition.

Most water level indicators are equipped to indicate and detect only a single level. The Water Level Indicator implemented here can indicate up to nine such levels and the microcontroller displays the level number on a seven segment display.

So, the circuit not only capable of cautioning a person that the water tank has been filled up to certain level, but also indicates that the water level has fallen below the minimum detectable level. This circuit is important in appliances such as the water cooler where there is a danger of motor-burnout when there is no water in the radiator used up also it can be used in fuel level indication.

# Block Diagram:
![image](https://user-images.githubusercontent.com/70700323/154846990-2c6b00d9-ed95-4180-a58a-30b8a20034e1.png)

# Circuit Diagram:
![image](https://user-images.githubusercontent.com/70700323/154847074-f2836b3a-1b32-447a-b1f8-9168dd13b7d4.png)

# Features:

1. Easy installation.
2. Low maintenance.
3. Compact elegant design.
4. The Automatic water level controller ensures no overflows or dry running of pump there by saves electricity and water.
5. Avoid seepage of roofs and walls due to overflowing tanks.
6. Fully automatic, saves man power.
7. Consume very little energy, ideal for continuous operation.
8. Automatic water level controller provides you the flexibility to decide for yourself the water levels for operations of pump set.
9. Shows clear indication of water levels in the overhead tank.

