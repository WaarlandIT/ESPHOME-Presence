# ESPHOME-Presence

The previous presence sensors I made did use a LD2410 milimeter wave sensor, that works great but has a limited reach.
This presence sensor makes use of a LD1155H-24G sensor that is also a 24Ghz radar detector but has a wider range.
The HLK-LD1155H-24G detection field looks like:
![image](https://github.com/WaarlandIT/ESPHOME-Presence/assets/53364386/b5b43538-0bfe-4ac3-ac09-173c72d96c05)

This build also make use of a DHT Temprature and humidity sensor and a TEMT6000 light sensor.

The files in this repo are:
- esphome-presence.yaml
  This is the ESPHome config yaml to generate the code for the sensor
- config.yaml
  This is the example code that you need to create the BLE device config for the config.yaml of Home Assistant. 

Details about the build will follow

