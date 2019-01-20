# Home-Assistant.io

My Home Assistant configuration files are running on my [Hass.io](https://www.home-assistant.io/hassio/) installation on an Odroid C2.


## Where I started

- [Home-Assistant.io](https://home-assistant.io/) 
- [HASS.OS](https://www.home-assistant.io/hassio/)
- [HASSbian - Raspbian Image mit HomeAssistant auto-installer](https://home-assistant.io/docs/configuration/splitting_configuration/) (previously used on a Pi3)
- [Splitting up the configuration.yaml](https://github.com/cbulock/home-assistant-configs) (does not work on HassOS on my Odroid, probably a folder rights problem)
- [Storing secrets](https://home-assistant.io/docs/configuration/secrets/)


## Devices on HAss.OS

- [Odroid C2 with 8GB eMMC-Modul](https://www.pollin.de/p/odroid-c2-set-mit-8-gb-emmc-modul-gehaeuse-und-netzteil-810531)
- AVM Fritz!Box 7490
- AVM Fritz!DECT 200 Wall Plugs
- Google Chromecast Audio
- Google Chromecast
- Osram Smart+ Plugs (via HUE Bridge)
- Philips Hue Bridge (v1)
- Philips Hue Colour Bulbs (v1) (only 1 still working, 2 died after nearly 2,5 years)
- Sonos Loudspeaker
- IKEA TRÅDFRI Bridge
- IKEA TRÅDFRI White Bulbs
- Z-Wave USB.ME Stick
- Z-Wave Fibaro FGMS001 Motion Sensor
- Z-Wave Fibaro FGWPEF Wall Plugs
- Zyxel 24-port Switch

## HAss Components used

- [Darksky Weather](https://www.home-assistant.io/components/weather.darksky/)
- [Darksky Weather Sensor](https://www.home-assistant.io/components/sensor.darksky/)
- [DuckDNS](https://www.home-assistant.io/components/duckdns/)
- [AVM FritzBox Net Monitor](https://www.home-assistant.io/components/sensor.fritzbox_netmonitor/)
- [AVM FritzBox Switch](https://www.home-assistant.io/components/switch.fritzdect/)
- [Google Travel Time](https://www.home-assistant.io/components/sensor.google_travel_time/)
- [Luftdaten](https://www.home-assistant.io/components/sensor.luftdaten/)
- [Min/Max Sensor](https://www.home-assistant.io/components/sensor.min_max/)
- [MQTT](https://www.home-assistant.io/components/mqtt/) MQTT not used right now
- [MQTT - own server](https://www.home-assistant.io/docs/mqtt/broker#run-your-own)
- [MQTT Statestream](https://www.home-assistant.io/components/mqtt_statestream/)
- [OpenSky Sensor](https://www.home-assistant.io/components/sensor.opensky/)
- [Pi-Hole Sensor](https://www.home-assistant.io/components/sensor.pi_hole/)
- [RESTful Sensor](https://www.home-assistant.io/components/sensor.rest/) for pulling data from [Tankerkönig.de](http://www.tankerkoenig.de/)
- [SNMP Sensor](https://www.home-assistant.io/components/sensor.snmp/) for Zyxel Switch
- [Statistics](https://www.home-assistant.io/components/sensor.statistics/)
- [Systemmonitor](https://www.home-assistant.io/components/sensor.systemmonitor/)
- [Uptime HAss](https://www.home-assistant.io/components/sensor.uptime/)
- [Uptimerobot](https://www.home-assistant.io/components/binary_sensor.uptimerobot/) - (~15.000 DNS request/day)
- [Waze Travel Time](https://www.home-assistant.io/components/sensor.waze_travel_time/)
- [Workday Binary Sensor](https://www.home-assistant.io/components/binary_sensor.workday/)
- [YR.no Weather](https://www.home-assistant.io/components/sensor.yr/)

## HAss Add-Ons used
- [Log Viewer](https://community.home-assistant.io/t/community-hass-io-add-on-log-viewer/64377)
- [Lovelace Migration](https://community.home-assistant.io/t/community-hass-io-add-on-lovelace-migration/61552)
- Samba
- [Configurator][https://www.home-assistant.io/addons/configurator]
