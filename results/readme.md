In this directory, you will find the raw results on the STM32intheskyexperiment.

A high altitude balloon was launched from Rousset the 11/06/19.

Sereral LoRa Node were embedded in the nacelle.

 * Dipole : Miniature UCA board with integrated antenna, RFM95 and BluePill
 * Dipole2 : Miniature UCA board with integrated antenna, RFM95 and BluePill
 * Patch : PCB board with RFM95, bluePill and connected to a patch antenna
 * Relay : B-L072Z-LRWAN1 connected to a dipole antenna
 
 GW_Name is the file with all GW reached for each packet
 
 You will also find the sensor results for Dipole Node which was using a BME280 sensor (T°, Humidity and Pressure).
 
 It is funny to see that the node was unable to operate from 11 to 30km when the temperature are below -40°c.
 
 But when the balloon reach 25km which temperature close -25°c, the node was again able to operate.
 
 And of course, it was the slot time where the nodes reach the longest distance.
 
After the balloon burst, the node was again unoperating between 25km and 4km (you can note the temperature inertia thanks to the protection).
Miraculously, the node operate again at 4km for a very short time. The battery was probably so stressed that the peak current from the LoRa transciever definitly kill the battery. 
RIP device EUI-50FF1A0000001005, your life was short but you make me dream !
 
 <img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/Sensor_Voltage.jpg">
 
 <img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/Sensor_Temp.jpg">

 
