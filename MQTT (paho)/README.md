Use the Eclipse broker mosquitto, at https://github.com/eclipse/mosquitto
On mac `brew install mosquitto`, you then have 2 options:
To have launchd start mosquitto now and restart at login:
  `brew services start mosquitto`
Or, if you don't want/need a background service you can just run:
  `mosquitto -c /usr/local/etc/mosquitto/mosquitto.conf`

Use MQTT lens to observe traffic https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm?hl=en

<p align="center">
<img src="https://github.com/robmarkcole/Useful-python/blob/master/MQTT%20(paho)/mqtt_lens.png" width="800">
</p>