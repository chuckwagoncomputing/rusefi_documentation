
Production 2001 – 2008

# 750 8 cylinders

![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_1.png)
![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_2.png)
![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_3.png)
![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_4.png)
![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_5.png)
![p](oem_docs/Bmw/7_Series_e65/2006_bmw_750_6.png)


| Connector/ Pin Number | OEM Color | Name / Function | 
| --------------------- |------- |---------------- |
| 3 | GRY     | TCU        |
| 4 | BRN     | GND Ground |
| 6 | BRN     | GND Ground |
| 7 | RED     | +12v Hot all times | 
| 8 | ORG     | +12v Hot all times | 
|   |         |           |


| Connector/ Pin Number | OEM Color | Name / Function | 
| --------------------- |------- |---------------- |
| 2 | YEL     |           |
| 3 | YEL/RED |           |
| 4 | BLU     |           |
|   |         |           |
|   |         |           |
|   |         |           |


# 760 12 cylinders

x2 DME - engine control unit using [134 pin connector](OEM-connectors#134)

x2 HDEV fuel injection module 7506280 [121 pin connector](OEM-connectors#121)

|Pin Number|Name   | Default function                            | OEM Color   |
| ---:|:---------- |:------------------------------------------- | ----------- |
| 4   | **GND**    |  Power GND                                  | BRN         |
| 5   | **GND**    |  Power GND                                  | BRN         |
| 6   | **GND**    |  Power GND                                  | BRN         |
| 15  | HPFP       |  High Pressure Fuel Pump Control Signal     | Blue/Yellow |


![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_1.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_2.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_3.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_4.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_5.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_6.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_7.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_8.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_9.png)
![p](oem_docs/Bmw/2003_7_Series_e65/2003_N73_engine_10.png)
![connector](oem_docs/TE/Connector_121_pinout.jpg)

Injector #1 + #118

Injector #1 GND #114

Injector control #44-#49
These pins are pulled-up to +12v - low-side driven control.

GND #1 #2

Power +12v: #4 #51 

The larger chip inside 7506280 says 30429, obviously google knows nothing about this 30429. But it's probably CJ830.

SAK-C505 

[wikipedia](https://en.wikipedia.org/wiki/BMW_7_Series_(E65))

Injector 13647512081 looks to be solenoid type. Fuel pressure maxes out at 120bar.
R=2.1OHm

Ignition COP 12138657273 is shared with a lot of other BMW and Mini models.


CAS 61326943828 51210030982
CAS 61356972681 
CAS 61326922329

Programming keywords:
ISTA ICON

##### HOWTO videos

Console removal https://www.youtube.com/watch?v=pGAeodWa_i4

SRS module controls fuel pump 
https://lacarpro.com/blogs/dal-works/2002-1-2-bmw-745i-no-start

RHD instrument cluster removal https://www.youtube.com/watch?v=GyVhkNa3010

Emergency Brake Release Procedure https://www.youtube.com/watch?v=xDP5w6bBccM

https://www.youtube.com/watch?v=vIzs32PNZTY&t=140s

Battery replacement https://www.youtube.com/watch?v=V-FhPSF_880

[User Manual](oem_docs/Bmw/2003_7_Series_e65/2004_Manual_7_Series.pdf)



# Transmission

[6 Speed Transmission mechatronic sleeve replacement](oem_docs/Bmw/2003_7_Series_e65/6_speed_sleeve_replacement.pdf)

[ZF6HP26 / 6R60 / 09E Remove Mechatronic Case Connector Sleeve Valve Body](https://www.youtube.com/watch?v=b0vvqtso14k)

