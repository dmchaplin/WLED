## Welcome to my project WLED!

WLED is a fast and (relatively) secure implementation of an ESP8266 webserver to control NeoPixel (WS2812B) LEDs!
Now also with experimental ESP32 support.

Uses ESP Arduino core version 2.3.0 (latest as of December 2017).

### Features: (V0.5dev)
- RGB, HSB, and brightness sliders
- Settings page - configuration over network
- Access Point and station mode - automatic failsafe AP
- WS2812FX library integrated for over 50 special effects!
- Secondary color support lets you use even more effect combinations
- Support for RGBW strips
- 25 user presets! Save your favorite colors and effects and apply them easily!
- Nightlight function (gradually dims down)
- Notifier function (multiple ESPs sync color via UDP broadcast)
- Support for power pushbutton
- Custom Theater Chase
- Full OTA software update capability (only ESP8266)
- Password protected OTA page for added security (OTA lock)
- Alexa smart home device server (including dimming)
- NTP and experimental analog clock function
- Support for the Cronixie Clock kit by Diamex
- Realtime UDP Packet Control (WARLS) possible
- Client HTML UI controlled

### Compile settings:
- Board: WeMos D1 mini (untested with other HW, should work though)
- CPU frequency: 80 MHz
- Flash size : 4MB (3MB SPIFFS)
- Upload speed: 921600

### Quick start guide and documentation:

See the [wiki](https://github.com/Aircoookie/WLED/wiki)!

### Other

Licensed under the MIT license 
Uses libraries: 
ESP8266/ESP32 Arduino Core
NeoPixelBus by Makuna
[WS2812FX](https://github.com/kitesurfer1404/WS2812FX) by kitesurfer1404 (Aircoookie fork)
Time library
Timezone library by JChristensen
Alexa code based on arduino-esp8266-alexa-multiple-wemo-switch by kakopappa

Uses Linearicons by Perxis! (link in settings page)






