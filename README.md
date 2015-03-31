## OPEN WEATHER MONITORING SYSTEM

## INTRODUCTION

As a country, Sri Lanka has been constantly proven development largely with new urban development projects started with the expansion of living conditions. Very seemingly, a weather forecasting and severe weather warning has been affecting the lives of community more than ever. A very recent incident is the calamity that happened in Haldummulla, in Badulla District which is believed to have killed over a hundred people bringing casualties and property loss by a landslide. Apart from this, even a slight change in the rainfall may affect from urban traffic jams to flooding in lower land. Although it is very important to forecast and analyse weather, the existing weather platforms are not doing a fine tuned job that is needed for the community. Therefore a system of interconnected de localized weather forecasting applications can be highly recommended to the forecasting system of the country.

Wireless Sensor Networks (WSN) can help to monitor environmental conditions and water quality, allowing an easier, faster and cheaper data logging, which will lead into a better utilization of resources of each organization or government.  
Aim of this project at monitoring in real-time to determine the weather data and react against unexpected situations of weather , avoiding possible damages that natural disasters such as floods usually provoke in cities.

On the one hand, these sensor nodes have been used to measure parameters such as temperature, humidity, wind speed/direction, water level.  

As a result of this project, weather parameters can be monitored in real-time in order to check that all the elements within the network are working properly and to be able to react against an unexpected situation. Therefore, a huge amount of money can be saved by minimizing the effects of a natural disaster.

Wireless sensor networks bring advantages in the form of lowering the cost of sensor installation. Lowering the cost is achieved by avoiding the need for materials and testing which all raise the costs of labour.

## LITERATURE REVIEW

*PRETESIC Project*  
 PRETESIC project has been developed by the Institute of Computer Technology (ITI) in collaboration with the Polytechnic University of Valencia (UPV) and Telefonica Cathedra, and it has been deployed in the city of Valencia (Spain). This system is able to monitor water quality by measuring different environmental parameters and its main advantage is to minimize the time required to deploy a wireless sensor network in a particular area.PRETESIC is aimed at monitoring Valencia's network of sanitary sewers in real-time to determine the quality of water. In this way, the system is able to react against unexpected situations, avoiding possible damages that natural disasters such as floods usually provoke in cities.

*Differences from Pretesic Project*  
• Pretesic project mainly focus on determine water quality and flood detection. In open weather monitoring system project we mainly focus on weather data .  
• Pretesic project collect data from sensor nodes using mobile nodes. But here we collect data using our device and send data to centralized online server which can distribute data through REST API.  
• In specific time period ,If there huge difference between measurable values ,sensor node directly inform near weather forecasting authority.

## DESIGN AND IMPLEMENTATION

This system is a combination of sensor networks, communication technology and embedded systems, and this achieves remote real time monitoring for weather data. There are five key elements in a wireless monitoring system: data measurement, convert analog readings into digital, data transmission to remote server, data analysis and distribution of data through REST API.  
 The sensor nodes have a fixed location. Each sensor node measure and the data will be sent to the central computer by using GSM shield through GPRS. The system will be having sensor board; micro controller and GSM module. All the data will be stored in the temporary storage buffer. Each sensor node can be powered with rechargeable batteries .The micro controller will be released data in every five minute while monitoring point system will be in sleep mode(in order to save battery). Each sensor node has a LCD screen and a control panel to display the measurements In the central server, it collects all the data from each sensor node and analyses the data.

## BILL OF MATERIAL

1 x Rs.7800 GSM/GPRS shield  
2 x Rs. 660 DHT11 Temp/Humidity Sensor  
1 x Rs.2250 Wind Sensor  
1 x Rs.1000 Other electronic components

Total cost: Rs.12 350/=

## MEMBERS

*   KULATHILAKA B.U. (E/11/217)
*   LANKATHILAKA Y.M.P.N.(E/11/237) @NirmalL
*   MARASINGHE M.M.D.B.(E/11/258) @dhammika-marasinghe
*   NANAYAKKARA N.B.U.S.(E/11/268)