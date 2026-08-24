# M3Battery_Wifi

ESP8266 variant of the Model 3 battery SOC monitor: same EVTV serial parse and LED band, plus Wi-Fi so status can be reached on the LAN. SoftwareSerial is on pins 7/8; LED pins remain 4/5/6. Keep network credentials in local copies only; do not treat this public tree as a secret store.

**Source last updated:** 2022-03-03  
**Language:** C++ / Arduino  
**Target:** ESP8266 (ESP8266WiFi) plus SoftwareSerial EVTV link  
**Output:** Arduino sketch

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `M3Battery_Wifi` | C++ / Arduino | sketch | SOC LEDs plus ESP8266 Wi-Fi status for the EVTV battery feed |

## How to open

Open `M3Battery_Wifi.ino` in the Arduino IDE with ESP8266 board support. An `.ino.example` copy is alongside the sketch.

## Attribution and provenance

Dave Robinson / VaderConsulting, derived from `M3Battery`. Imported from the Arduino archive.

## License

MIT © 2026 VaderConsulting for Dave's code. See `LICENSE`.
