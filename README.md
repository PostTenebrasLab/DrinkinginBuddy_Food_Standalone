# Drinking-in-Buddy Food Standalone

## Build

```
curl --fail --remote-name --location https://www.forward.com.au/pfod/SipHashLibrary/SipHash.zip
arduino-cli --config-file arduino-cli.yaml lib install --zip-path SipHash.zip
arduino-cli lib install 'Adafruit GFX' 'Adafruit SSD1306' ArduinoJson@5
arduino-cli --config-file arduino-cli.yaml core install esp8266:esp8266
arduino-cli compile --fqbn esp8266:esp8266:d1_mini
```
