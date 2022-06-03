# homebridge-synology-surveillance-homemode FOR DSM7

Simple Homebridge plugin to turn on/off homemode on Synology Surveillance station.

Switch "on" -> home mode off (cameras are on)
Switch "off" -> home mode on (cameras are off)

Configuration:
```
 {
            "accessory": "SSHomeMode",
            "name": "Security Cameras",
            "url": "https://192.168.1.x:5001/",
            "username": "user",
            "password": "password
        }
```
