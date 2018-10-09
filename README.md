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

## HAss Components used

- [Darksky Weather](https://www.home-assistant.io/components/weather.darksky/)
- [Darksky Weather Sensor](https://www.home-assistant.io/components/sensor.darksky/)
- [Google Hangouts Hub](https://www.home-assistant.io/components/hangouts/) and [Notifications](https://www.home-assistant.io/components/notify.hangouts/)
- [Google Travel Time](https://www.home-assistant.io/components/sensor.google_travel_time/)
- [Luftdaten](https://www.home-assistant.io/components/sensor.luftdaten/)
- [MQTT](https://www.home-assistant.io/components/mqtt/)
- [MQTT - own server](https://www.home-assistant.io/docs/mqtt/broker#run-your-own)
- [MQTT Statestream](https://www.home-assistant.io/components/mqtt_statestream/)
- [Pi-Hole Sensor](https://www.home-assistant.io/components/sensor.pi_hole/)
- [RESTful Sensor](https://www.home-assistant.io/components/sensor.rest/) for pulling data from [Tankerkönig.de](http://www.tankerkoenig.de/)
- [SNMP Sensor](https://www.home-assistant.io/components/sensor.snmp/)
- [Systemmonitor](https://www.home-assistant.io/components/sensor.systemmonitor/)
- [Uptime HAss](https://www.home-assistant.io/components/sensor.uptime/)
- [Uptimerobot](https://www.home-assistant.io/components/binary_sensor.uptimerobot/)
- [Waze Travel Time](https://www.home-assistant.io/components/sensor.waze_travel_time/)
- [YR.no Weather](https://www.home-assistant.io/components/sensor.yr/)

## HAss Add-Ons used
- [IDE Cloud9](https://community.home-assistant.io/t/community-hass-io-add-on-ide-based-on-cloud9/33810)
- [Log Viewer](https://community.home-assistant.io/t/community-hass-io-add-on-log-viewer/64377)
- [Lovelace Migration](https://community.home-assistant.io/t/community-hass-io-add-on-lovelace-migration/61552)
- [MotionEye](https://community.home-assistant.io/t/community-hass-io-add-on-motioneye/71826)
- [MQTT Server & Web client](https://community.home-assistant.io/t/community-hass-io-add-on-mqtt-server-web-client/70376)
- [Portainer](https://community.home-assistant.io/t/community-hass-io-add-on-portainer/68836) (presently deactivated, see forum)
- Samba
- [SSH & Web Terminal](https://community.home-assistant.io/t/community-hass-io-add-on-ssh-web-terminal/33820)
