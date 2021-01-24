# Deploy on Raspberry Pi without Docker

Tested on `Raspbian Stretch (4.19.66-v7+)`

Install npm Registry
```
sudo apt install npm
```

Clone this repo:
```
git clone https://github.com/odolezal/MQTT-TPLink-Bridge.git
cd MQTT-TPLink-Bridge/
```
Edit files:
1.  [`mqtttplinkbridge.js`](mqtttplinkbridge.js#L88)
2.  [`config.json`](config/config.json)

Install packages
```
npm install
```

Start app
```
npm start
```

Example output:

```
> mqttTPLinkBridge@1.0.0 start /home/pi/MQTT-TPLink-Bridge
> node mqtttplinkbridge.js

mqttTPLinkBridge started...
IN>>tplinkbridge/plug/hs100: 1
IN>>tplinkbridge/plug/hs100: 0
```
