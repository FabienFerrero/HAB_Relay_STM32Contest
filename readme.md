<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/STM32-in-the-sky.png">


# HAB_Relay_STM32Contest
* Last edition : 15/06/2019
* Author: Fabien Ferrero

The Repository contain the Code and Results of the STM32inthesky experiment which was performed on the 11/06/19.

In this event with 4 different High Altitude Balloons were launched from Rousset, France
https://blog.st.com/stm32-in-the-sky/

Polytech'Nice was participating to the contest and design a nacelle including several LoRa nodes connected on TheThingsNetwork (https://www.thethingsnetwork.org/).
As you can see in the picture, two nodes were outside the nacelle, so we try to protect the battery from the cold temperature as much as possible

<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/Nacelle.png">

<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/launch.jpg">

The Polytech'Nice balloon was lauched at 3PM. It reach an altitude of 31km.

From this altitude, the balloon was able to transmit on many TTN Gateways. An average max communication distance of 600km was achieved (which correspond to the line of sight at this altitude considering earth curvature).
The longest gateway detected was in Weiz near Graz in Austria. The total distance was 835km.
The EUI on the gateway is : EUI-70B3D5B020030D77
I'm still trying to confirmed the GPS position of this GW.

<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/vue_ballon2.png">

<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/dipole2_2.jpg">

The balloon finally land close to gap
<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/map.jpg">

Line of Sight versus Altitude considering earth curvature

<img src="https://github.com/FabienFerrero/HAB_Relay_STM32Contest/blob/master/pictures/LOS_vs_Altitude.jpg">









