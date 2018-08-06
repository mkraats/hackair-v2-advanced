# hackair-v2-advanced

A fork of the hackAIR v2 sensor running on Wemos D1 mini. ( hackAir-Arduino/examples/Wemos/Wemos.ino )

This sensor has the following changes from the official version:

- Adafruit.IO support so you can graph your PM10/PM25 values in real time.
- Debug mode for development ( ie, don't send data to platform when the sensor is on your desk )
- Support for mDNS to make sensor reachable via hackair.local.
- Support for adding hackAIR API key via WiFiManager. 
