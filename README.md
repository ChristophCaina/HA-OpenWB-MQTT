# OpenWB 2.0 MQTT Integration for HomeAssistant
_THIS is an fork based on the work of https://github.com/a529987659852/openwbmqtt!_   
_**PLEASE USE THE ORIGINAL COMPONENT (which you will also find in HACS)**_

Note: I provide this custom integration without any warranty. It lies in the responsability of each user to validate the functionality with his/her own openWB!

This is a Custom Component for HomeAssustant supporting the [openWB Wallbox](https://openwb.de/main/) with Software Version 2.0  
The integration subscribes to MQTT topics `prefix/<various values>` which are used by openwb to broadcast information and displays this informations as sensor entities.
In addition, the integration provides services that execute actions on the openwb (for example enable/disable a charge point).

## Requirements
This integration requires an installed Mosquitto MQTT Broker in HomeAssistant.

(to be continued)
