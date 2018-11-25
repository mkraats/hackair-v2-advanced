# hackair-v2-advanced

A fork of the hackAIR v2 sensor running on Wemos D1 mini. ( hackAir-Arduino/examples/Wemos/Wemos.ino )

This sensor has the following changes from the official version:

- Adafruit.IO support so you can graph your PM10/PM25 values in real time.
- Debug mode for development ( ie, don't send data to platform when the sensor is on your desk )
- Support for mDNS to make sensor reachable via hackair.local.
- Support for adding hackAIR API key via WiFiManager.
- Support for sending data to InfluxDB.
- Support for sending data to openSensemap.

# Important: ArduinoJSON library support

The ArduinoJSON library installs ArduinoJSON version 6 by default. This version is still in beta ( see https://arduinojson.org/v5/example/ ) and the author recommends using version 5. It also introduces a few breaking changes. This sketch compiles with at least 5.13.2.
