

This program illustrates the working of Soil Moisture Sensor.
The Sensor senses the humidity level in the soil and send to the Arduino through the anlog pin.

Soil/Dust Humidity/Water/Moisture Sensor

This is a simple water sensor can be used to detect soil moisture when the soil moisture deficit module outputs a high level, and vice versa output low. Use this sensor produced an automatic plant watering device, so that the plants in your garden without people to manage.
Sensitivity adjustable the blue digital potentiometer adjustment
Operating voltage 3.3V-5V
Module has digital output for more accurate.
With fixed bolt hole for easy installation
Small board PCB size: 3cm * 1.6cm
Power indicator (red) and digital switching output indicator (green)
Comparator LM393 chip, very stable
 

Connections:

VCC  connect to 3.3V-5V
GND  connect to GND
DO   digital value output connector(0 or 1)
AO  analog value output connector
 

Usage:

Soil moisture module is most sensitive to the ambient, generally used to detect the moisture content of the soil.
When the module can not reach the threshold value, DO port output high, when the the soil humidity exceeds a set threshold value, the module D0 output low;
The small board digital output D0 can be connected directly to the MCU, MCU to detect high and low, to detect soil moisture;
Small board digital output DO can directly drive the buzzer module or relay module in our store, which can form a soil moisture alarm equipment;
Small board analog output AO and AD module connected through the AD converter, you can get more precise values ??of soil moisture;

The interfacing of Arduino with the Sensor is given in the below link
(http://www.instructables.com/id/Soil-Moisture-Sensor/?ALLSTEPS)