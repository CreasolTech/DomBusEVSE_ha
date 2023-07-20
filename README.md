# DomBusEVSE_ha
Home Assistant configuration files for DomBusEVSE module used to make a DIY smart wallbox charging station
[![alt DomBusEVSE DIY wallbox home-made](https://images.creasol.it/creDomBusEVSE_dashboard1.png "Modulo EVSE per autocostruirsi una smart wallbox")](https://www.creasol.it/en/support/domotics-home-automation-and-diy/making-a-diy-homemade-wallbox-working-with-home-assistant)

More information in the web pages:

* [DomBusEVSE page](https://www.creasol.it/EVSE)
* [DomBusEVSE with Home Assistant](https://www.creasol.it/en/support/domotics-home-automation-and-diy/making-a-diy-homemade-wallbox-working-with-home-assistant)
* [Creasol store](https://store.creasol.it/en/18-ev-electric-vehicles)

# Configuration files
* **configuration.yaml** with changes to include **dombus1.yaml** with all entities for DomBus modules connected to the same bus, and some helpers.
* **dombus1.yaml** contains entities for all DomBus modules connected to this bus
* **automations.yaml** contains some automations to configure the module
* **dashboard_wallbox.yaml** contains a dashboard with main controls for the DomBusEVSE module

# DomBusEVSE
## Youtube video showing DomBusEVSE working with Domoticz 
[![How DomBusEVSE works - Video using Domoticz, in this case](https://img.youtube.com/vi/m_n_A4lo9Gw/0.jpg)](https://youtu.be/m_n_A4lo9Gw)

## Home made wallbox using DomBusEVSE and Home Assistant
[![DomBusEVSE connections](https://images.creasol.it/creDomBusEVSE_wallbox_photo_ha.jpg "DIY wallbox using Creasol DomBusEVSE module with Home Assistant")](https://www.creasol.it/en/?view=article&option=com_content&id=160)

# Other DomBus modules that can be used with Home Assistant

## DomBusTH - Compact board to be placed on a blank cover, with temperature and humidity sensor and RGW LEDs
<a href="https://store.creasol.it/DomBusTH"><img src="https://images.creasol.it/creDomBusTH6_200.png" alt="DomBusTH domotic board with temperature and humidity sensor, 3 LEDs, 6 I/O" style="float: left; margin-right: 2em;"></a>
<div>
Compact board, 32x17mm, to be installed on blank cover with a 4mm hole in the middle, to exchange air for the relative humidity sensor. Includes:
* temperature and relative humidity sensor
* red, green and white LEDs
* 4 I/Os configurable as analog or digital inputs, pushbuttons, counters (water, gas, S0 energy, ...), NTC temperature and ultrasonic distance sensors
* 2 ports are configured by default as open-drain output and can drive up to 200mA led strip (with dimming function) or can be connected to the external module DomRelay2 to control 2 relays; they can also be configured as analog/digital inputs, pushbuttons and distance sensors.
</div>
<br clear="all"/>

## DomBus12 - Compact domotic module with 9 I/Os
<a href="https://store.creasol.it/DomBus12"><img src="https://images.creasol.it/creDomBus12_200.webp" alt="DomBus12 domotic module with 9 I/O" style="float: left; margin-right: 2em;"></a>
9 ports that can be configured by software as:
* analog/digital inputs
* pushbutton and UP/DOWN pushbutton
* counters (water, gas, S0 energy, ...)
* NTC temperature and ultrasonic distance sensors
* 2 ports are configured by default as open-drain output and can drive up to 200mA led strip (with dimming function) or can be connected to the external module DomRelay2 to control 2 relays.
<br clear="all"/>

## DomBus23 - Domotic module with many functions
<a href="https://store.creasol.it/DomBus23"><img src="https://images.creasol.it/creDomBus23_400.webp" alt="DomBus23 domotic module with many functions" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
* 2x relays SPST 5A
* 1x 10A 30V mosfet (led stripe dimming)
* 2x 0-10V analog output: each one can be configured as open-drain output to control external relay
* 2x I/O lines, configurable as analog/digital inputs, temperature/distance sensor, counter, ...
* 2x low voltage AC/DC opto-isolated inputs, 9-40V
* 1x 230V AC opto-isolated input
<br clear="all"/>

