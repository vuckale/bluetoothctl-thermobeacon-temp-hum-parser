# bluetoothctl-thermobeacon-temp-hum-parser
### Description:
Simple bash and python scripts that capture BLE packages, parses temperature and humidity values and prints them. 
### Required packages:
```
sudo apt install bluez mawk grep
```
### Usage:
```
script name: thermo_beacon.sh
usage: ./thermo_beacon.sh [options]
options: -h              this help
         --temperature   get temperature value in C°
         --humidity      get humidity value in %
         --csv           output csv formatted line with temperature and
         humidity (--temperature and --humidity are automatically set)
```
