# Heating Monitor

## Goal

As simply as possible, monitor key aspects ofa old oil fired centra heating system
in order to improve efficiency

## ESPHome

Monitors the Boiler

Config in [heating.yaml]

Upload: `esphome run heating.yaml`

## TODO

- Install Home Assistant on a raspberry Pi
- Install blink on an ESP32
  - setting up wifi
    - <https://www.upesy.com/blogs/tutorials/how-to-connect-wifi-acces-point-with-esp32#>
  - reading DS18B20 thermocouples
    - <https://randomnerdtutorials.com/esp32-ds18b20-temperature-arduino-ide/>
    - <https://randomnerdtutorials.com/esp32-multiple-ds18b20-temperature-sensors/>
    - <https://esp32io.com/tutorials/esp32-temperature-sensor>
  - sending thermocouple data to HA via MQTT
    - <https://www.kincony.com/forum/showthread.php?tid=1826>
  - reading boiler burner status via mains optocoupler; send to HA via MQTT
  - install on boiler
- reading data from Switchbot Meters and sending to HA
  - <https://www.home-assistant.io/integrations/switchbot/>
  - <https://github.com/ronschaeffer/sbm2mqtt>
- investigate [ESPHome](https://esphome.io/)
