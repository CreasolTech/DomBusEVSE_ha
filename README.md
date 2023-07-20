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
## DomBus12 - 9 I/Os
[![DomBus12 module with 9 I/Os](https://images.creasol.it/creDomBus12_200.webp)](https://store.creasol.it/DomBus12)
Compact module with 9 ports, that can be configured as analog/digital inputs, pushbutton and UP/DOWN pushbutton, counters (water, gas, S0 energy, ...), NTC temperature and ultrasonic distance sensors. 2 ports are configured by default as open-drain output and can drive up to 200mA led strip (with dimming function) or can be connected to the external module DomRelay2 to control 2 relays.

