# CS:GO to WLED gamestate integration (С4)
Displays С4 status

* Green - can defuse
* Yellow - can defuse (only with defuse kit)
* Red - run!

[Example video](https://youtu.be/Oddy42e71_c)

## Dependencies
* [WLED](https://github.com/Aircoookie/WLED "WLED") for ESP8266/ESP32
* [Python 3.x](https://www.python.org/downloads/) (to run source code if necessary)

## How to use
* Copy "gamestate_integration_wled.cfg" to "csgo/cfg" directory.
* For example `D:\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\gamestate_integration_wled.cfg`
* Adjust the WLED IP in the `config.json`
* Install dependencies: `pip install -r requirements.txt`
* Run `app.py`

## Based on
[Counter-Strike: Global Offensive Game State Integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration)
