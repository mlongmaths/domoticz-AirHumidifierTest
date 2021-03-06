# domoticz-AirHumidifierTest
Domoticz plugin for Xiaomi Humidifier
* based on https://github.com/develop-dvs/domoticz-AirHumidifier2

* Add model deerma.humidifier.jsq

## Installation
```
pip3 install -U python-miio
```

* Make sure your Domoticz instance supports Domoticz Plugin System - see more https://www.domoticz.com/wiki/Using_Python_plugins

* Get plugin data into DOMOTICZ/plugins directory
```
cd YOUR_DOMOTICZ_PATH/plugins
git clone https://github.com/develop-dvs/domoticz-AirHumidifier2
```
Restart Domoticz
* Go to Setup > Hardware and create new Hardware with type: AirHumidifier2
* Enter name (it's up to you), user name and password if define. If not leave it blank
* Select your model (zhimi.humidifier.v1 / zhimi.humidifier.ca1 / zhimi.humidifier.cb1)

## Update
```
cd YOUR_DOMOTICZ_PATH/plugins/domoticz-AirHumidifier2
git pull
```
* Restart Domoticz

## Troubleshooting

In case of issues, mostly plugin not visible on plugin list, check logs if plugin system is working correctly. See Domoticz wiki for resolution of most typical installation issues http://www.domoticz.com/wiki/Linux#Problems_locating_Python
