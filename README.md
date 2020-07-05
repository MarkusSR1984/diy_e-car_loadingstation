# diy_e-car_loadingstation
A DIY Electrical Car Loading Station


This is a Work in Progress repository.
I will offer all PCBs and Sourcecodes here.
I create that Station because mx Brother need one to control the load current of his car to match his Photovolatik current to use maximum of the solar energy to load
the Cars Battery.

Pull requests are welcome

#Planned Hardware:
A PCB with muliply inputs and outputs.
based on a ESP8266 or ESP32 Microcontroller
messure the current load on AC Wires



ESP8266
+ needs a bit less power
+ has enogth resources to handle the controll
- needs one external ADC (1 included but 2 needet)


#IOs:
110v - 230V AC
Switch 1 (Power)
Switch 2 (Automatic On/Off)
Pushbutton 1 (Manual Loading Trigger - should ignore current Photovoltaik load)

CP - Communication with the Car
PP - Wire Detection
REL - Relais to switch off the Power from Loading Connector if no Car is connected or car Battery is full

