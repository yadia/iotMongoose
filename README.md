# iotMongoose
Project for implementing Mongoose OS in a ESP32 board

## Reference
Shout out to  for Alvaro Viebrantz his project introducing [Mongoose OS and Google cloud](https://medium.com/google-cloud/build-a-weather-station-using-google-cloud-iot-core-and-mongooseos-7a78b69822c5)

# Mongoose OS
Mongoose OS is an operating system for commercial IoT products (ESP32, ESP8266).
https://mongoose-os.com 
## Features
* OTA updates and remote management
* Security - flash encryption
* IoT Cloud integration - AWS IoT, Google IoT, Microsoft Azure, Generic MQTT/Restful
* Prototyping  and scripting: 
      Prototyping mJS JavaScript Engine
      Production: C/C++
      
## Install Mongoose OS on MAC
For other OS please refer to https://mongoose-os.com/docs/quickstart/setup.html 

```
curl -fsSL https://mongoose-os.com/downloads/mos/install.sh | /bin/bash
~/.mos/bin/mos --help      
~/.mos/bin/mos

```
Quick Start guide for Web UI and command line mode https://mongoose-os.com/docs/quickstart/setup.html

# Drivers

* Espressif board CH340g Mac-OS-X driver (Github link) [https://github.com/adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver]
* Espressif board Silabs drivers (Silabs website link) [https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers]


