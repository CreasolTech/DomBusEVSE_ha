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
Our industrial and home automation modules are designed to be
* very low power
* very reliable
* bus connected (no radiofrequency interference, no battery to replace).

Modules are available in two version:
- with DomBus proprietary protocol

## DomBusTH - Compact board to be placed on a blank cover, with temperature and humidity sensor and RGW LEDs
<a href="https://store.creasol.it/DomBusTH"><img src="https://images.creasol.it/creDomBusTH6_200.png" alt="DomBusTH domotic board with temperature and humidity sensor, 3 LEDs, 6 I/O" style="float: left; margin-right: 2em;"></a>
Compact board, 32x17mm, to be installed on blank cover with a 4mm hole in the middle, to exchange air for the relative humidity sensor. It can be **installed in every room to monitor temperature and humidity, check alarm sensors, control blind motor UP/DOWN**, send notifications (using red and green leds) and activate **white led in case of power outage**.

Includes:
* temperature and relative humidity sensor
* red, green and white LEDs
* 4 I/Os configurable as analog or digital inputs, pushbuttons, counters (water, gas, S0 energy, ...), NTC temperature and ultrasonic distance sensors
* 2 ports are configured by default as open-drain output and can drive up to 200mA led strip (with dimming function) or can be connected to the external module DomRelay2 to control 2 relays; they can also be configured as analog/digital inputs, pushbuttons and distance sensors.
<br clear="all"/>

## DomBus12 - Compact domotic module with 9 I/Os
<a href="https://store.creasol.it/DomBus12"><img src="https://images.creasol.it/creDomBus12_200.webp" alt="DomBus12 domotic module with 9 I/O" style="float: left; margin-right: 2em;"></a>
**Very compact, versatile and cost-effective module with 9 ports**. Each port can be configured by software as:
* analog/digital inputs
* pushbutton and UP/DOWN pushbutton
* counters (water, gas, S0 energy, ...)
* NTC temperature and ultrasonic distance sensors
* 2 ports are configured by default as open-drain output and can drive up to 200mA led strip (with dimming function) or can be connected to the external module DomRelay2 to control 2 relays.
<br clear="all"/>

## DomBus23 - Domotic module with many functions
<a href="https://store.creasol.it/DomBus23"><img src="https://images.creasol.it/creDomBus23_400.webp" alt="DomBus23 domotic module with many functions" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
Versatile module designed to control **gate or garage door**.
* 2x relays SPST 5A
* 1x 10A 30V mosfet (led stripe dimming)
* 2x 0-10V analog output: each one can be configured as open-drain output to control external relay
* 2x I/O lines, configurable as analog/digital inputs, temperature/distance sensor, counter, ...
* 2x low voltage AC/DC opto-isolated inputs, 9-40V
* 1x 230V AC opto-isolated input
<br clear="all"/>

## DomBus31 - Domotic module with 8 relays
<a href="https://store.creasol.it/DomBus31"><img src="https://images.creasol.it/creDomBus31_400.webp" alt="DomBus31 domotic module with 8 relay outputs" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
DIN rail low profile module, with **8 relays and very low power consumption**:
* 6x relays SPST 5A
* 2x relays STDT 10A
* Only 10mW power consumption with all relays OFF
* Only 500mW power consumption with all 8 relays ON !!
<br clear="all"/>

## DomBus32 - Domotic module with 3 relays
<a href="https://store.creasol.it/DomBus32"><img src="https://images.creasol.it/creDomBus32_200.webp" alt="DomBus32 domotic module with 3 relay outputs" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
Versatile module with 230V inputs and outputs, and 5 low voltage I/Os.
* 3x relays SPST 5A
* 3x 115/230Vac optoisolated inputs
* Single common for relays and AC inputs
* 5x general purpose I/O, each one configurable as analog/digital inputs, pushbutton, counter, temperature and distance sensor.
<br clear="all"/>

## DomBus33 - Module to domotize a light system using step relays
<a href="https://store.creasol.it/DomBus33"><img src="https://images.creasol.it/creDomBus32_200.webp" alt="DomBus33 domotic module with 3 relay outputs that can control 3 lights" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
Module designed to **control 3 lights already existing and actually controlled by 230V pushbuttons and step-by-step relays**. In this way each light can be activated by existing pushbuttons, and by the domotic controller.
* 3x relays SPST 5A
* 3x 115/230Vac optoisolated inputs
* Single common for relays and AC inputs
* 5x general purpose I/O, each one configurable as analog/digital inputs, pushbutton, counter, temperature and distance sensor.

Each relay can toggle the existing step-relay, switching the light On/Off. The optoisolator monitors the light status. The 5 I/Os can be connected to pushbuttons to activate or deactivate one or all lights.
<br clear="all"/>

## DomBus36 - Domotic module with 12 relays
<a href="https://store.creasol.it/DomBus36"><img src="https://images.creasol.it/creDomBus36_400.webp" alt="DomBus36 domotic module with 12 relay outputs" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
DIN rail module, low profile, with **12 relays outputs and very low power consumption**.
* 12x relays SPST 5A
* Relays are grouped in 3 blocks, with a single common per block, for easier wiring
* Only 12mW power consumption with all relays OFF
* Only 750mW power consumption with all 12 relays ON !!
<br clear="all"/>

## DomBus37 - 12 inputs, 3 115/230Vac inputs, 3 relay outputs
<a href="https://store.creasol.it/DomBus37"><img src="https://images.creasol.it/creDomBus37_400.webp" alt="DomBus37 domotic module with 12 inputs, 3 AC inputs, 3 relay outputs" style="float: left; margin-right: 2em; vertical-align: middle;"></a>
Module designed to be connected to alarm sensors (magnetc contact sensors, PIRs, tampers): it's able to monitor mains power supply (power outage / blackout) and also have 3 relays outputs.
* 12x low voltage inputs (analog/digital inputs, buttons, alarm sensors, counters, temperature and distance sensors, ...)
* 3x 115/230Vac optoisolated inputs
* 2x relays SPST 5A
* 1x relay SPST 10A
* In12 port can be used to send power supply to an external siren, monitoring current consumption
<br clear="all"/>

