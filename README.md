# How to use almost any tuya "cloud unsupported" device with home assistant (Without flashing tasmota)


Recently i have purchased a smart kettle named Profi Cook PC-WKS 1167G (picture below)
Unfortunatly, this device does not support tuya cloud therefore it cant be used with tuya integration.

![alt proficook](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/kettle.png?raw=true)
![alt proficook](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/mainscreen.jpeg?raw=true)

## First, if you havent done it already,[ install the tuya integratuin to HA](https://www.home-assistant.io/integrations/tuya/)


## The simplest solution Ever!

1. Open your tuya app, click the "plus" on top of your app and select Create Scene

![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/plus.jpeg?raw=true)

2. Select Tap-to-Run

![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/ttr.jpeg?raw=true)

3. Click Add Task on the "Then" section and select "Control Single Device"

![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/single.jpeg?raw=true)

4. Select your device and choose action type and action itself
   
![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/action.jpeg?raw=true)

5. Click next and save. Now actions should be visible ion the main screen of Tuya.
    
![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/tuyafin.jpeg?raw=true)

6. Go to your homeassistant, select settings -> integrations -> tuya and you will see 2 scenes has been added.
Now you can easily use this scenes to create buttons, automations and expose them to google, alexa, yandex and more!

![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/hatuya.png?raw=true)
![alt plus](https://github.com/dimagoltsman/homeassistant-with-unsupported-tuya/blob/master/ha.png?raw=true)
