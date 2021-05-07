
# Changelog

## [V1.0](https://github.com/Mr-HaleYa/MyWater_Misc/tree/master/PCB/V1.0)
The first version with 4 short circuits and the wrong ping was assigned to the Ultrasonic sensor, and a lot of the pins were backward... 

## [V1.1](https://github.com/Mr-HaleYa/MyWater_Misc/tree/master/PCB/V1.1)
Improved the routes, thickened the charging traces, added some more Silk Screen Decals, and fixed polarity issues.

##### Added
- 4 Battery pack
- option to use Pre-Fab DHT11
- MPPT heat cutout
- Company LOGO

##### Fixed
- Short Circuits 
- corrected Sensor pin
- polarity of pins

## [V1.2](https://github.com/Mr-HaleYa/MyWater_Misc/tree/master/PCB/V1.2)
Changed the pins that power the board to use the pins on the back of the TTGO so we have all battery protections that are included. Altered the MPPT heat cut out to have a second small PCB built inside of it with small bridges so it can be removed and used as the temp sensor for the Ultrasonic Sensor.

##### Added 
- Connectors for battery pad on the back of ttgo
- Backward battery protection
- overcharge Protection
- Over-Discharge protection
- 3A overcurrent protection
- on/off switch
- 0.96" or 1.3" OLED Debug screen
- Debug_S or Debug_F jumper headers
- SMD resistor options
- Mini PCB in MPPT cutout

##### Fixed
- location of terminal blocks 
- grounding of solar pins
- grounding of MPPT
- battery pack orientation 

## [V2.0](https://github.com/Mr-HaleYa/MyWater_Misc/tree/master/PCB/V2.0)
A new format for a new box. Almost all the hardware is the same except for the addition of an MCP23017 multiplexer that adds 16 more GPIO pins and uses I2C, It is mainly used for a set of 2 dip switches that set station settings and info. Also changed out the DHT11 for an AM2320 because the freezing temperatures were breaking the sensor.

#### Added
- MCP23017 multiplexer
- 8 pin dip for station settings
- 3 pin dip for setting station type
- am2320 temp / humidity sensor
- 120VAC -> 5VDC for mains power

## [V3.0](https://github.com/Mr-HaleYa/MyWater_Misc/tree/master/PCB/V3.0)
Fixed a lot of small problems with the new format. Added 3 pushbuttons for navigation a menu on the screen for config and control of the station. Added another MCP23017 for even more GPIO pins for the pushbuttons. Also added a ton of little improvements.

#### Added
- Another MCP23017 multiplexer
- 3 pushbuttons for screen control
- external battery header
- jumper pads for setting power source
- switch to control when in config mode
- voltage divider to measure external DC voltage
- switch to turn on/off when using external DC
- voltage divider to check if the 5Vin rail has power
- Low-Side on/off switch for the camera using small MOSFET
- 12V MPPT solar charger for charging external 12V pack

