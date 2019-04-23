# Xiaomi Original & Aqara Device Handlers for SmartThings

Maintained by bspranger
Forked from a4refillpad's Xiaomi repository. Contributions from veeceeoh, ronvandegraaf, tmleafs & gn0st1c.

Install manually or using GitHub integration with these settings:
```
Owner: bspranger
Name: Xiaomi
Branch: master
```

---

## Pairing

These devices are not easy to pair initially. More information and help is available at <a href="https://community.smartthings.com/t/original-aqara-xiaomi-zigbee-sensors-contact-temp-motion-button-outlet-leak-etc/113253/1">this SmartThings Community Post</a>.


## Supported Xiaomi Devices

| | |
| --- | --- |
| [![Xiaomi Button](images/button.jpg)](./devicetypes/bspranger/xiaomi-button.src) | [![Xiaomi Aqara Button](images/aqarabutton.jpg)](./devicetypes/bspranger/xiaomi-aqara-button.src) |
| **Xiaomi Button** | **Xiaomi Aqara Button** |
| [![Xiaomi Door/Window Sensor](images/door.jpg)](./devicetypes/bspranger/xiaomi-door-window-sensor.src) | [![Xiaomi Aqara Door/Window Sensor](images/aqaradoor.jpg)](./devicetypes/bspranger/xiaomi-aqara-door-window-sensor.src) |
| **Xiaomi Door/Window Sensor** | **Xiaomi Aqara Door/Window Sensor** |
| [![Xiaomi Motion Sensor](images/motion.jpg)](./devicetypes/bspranger/xiaomi-motion-sensor.src) | [![Xiaomi Aqara Motion Sensor](images/aqaramotion.jpg)](./devicetypes/bspranger/xiaomi-aqara-motion-sensor.src) |
| **Xiaomi Motion Sensor** | **Xiaomi Aqara Motion Sensor** |
| [![Xiaomi Temperature Humidity Sensor](images/temp.jpg)](./devicetypes/bspranger/xiaomi-temperature-humidity-sensor.src) | [![Xiaomi Aqara Temperature Humidity Sensor](images/aqaratemp.jpg)](./devicetypes/bspranger/xiaomi-aqara-temperature-humidity-sensor.src) |
| **Xiaomi Temperature Humidity Sensor** | **Xiaomi Aqara Temperature Humidity Sensor** |
| [![Xiaomi mijia Honeywell Fire Alarm Detector](images/smoke.jpg)](./devicetypes/bspranger/xiaomi-mijia-honeywell-fire-detector.src) | [![Xiaomi Aqara Leak Sensor](images/aqarawater.jpg)](./devicetypes/bspranger/xiaomi-aqara-leak-sensor.src) |
| **Xiaomi mijia Honeywell Fire Alarm Detector** | **Xiaomi Aqara Leak Sensor** |
| [![Xiaomi Zigbee Outlet](images/outlet.jpg)](./devicetypes/bspranger/xiaomi-zigbee-outlet.src) | |
| **Xiaomi Zigbee Outlet**<br>**Note:** We do not recommend this outlet as they may make SmartThings less stable. | |

Model WXKG02LM (2-button) Function Chart
Action	Side	2016 rev (old FW)*	2016 rev (new FW)	2018 revision
Single press	Left	button 1 pushed	button 1 pushed	button 1 pushed
Single press	Right	button 1 pushed	button 2 pushed	button 2 pushed
Single press	Both	button 1 pushed	button 3 pushed	button 3 pushed
Hold **	Right			button 1 held
Hold **	Right			button 2 held
Hold **	Right			button 3 held
Double-click	Left			button 4 pushed
Double-click	Right			button 5 pushed
Double-click	Both			button 6 pushed
