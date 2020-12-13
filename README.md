# the_lights_project
## the what now?
A socially distanced set of Christmas lights in multiple incarnations and multiple locations. Change the lights on one set, and the rest of the lights update to match. Yes it's Cheerlights, but for people that I know not the whole world.
## how
Neopixels, Wemos D1 Minis, MQTT via Adafruit IO and a few buttons.
## expected behvaiours
### Incarnation 1 - the Little House
* On first powerup the house will turn red and then set up a wifi access point. 
* Once connected to the world wide web, the house will turn green. 
* The house connects to Adafruit and then get the current global colour (which could be green).
* To change the colour, hold the button until the house changes colour (it could change to the same colour).
### Incarnation 2 - the Tree Lights and Gift Controller
#### The Tree Lights
* When powered up, the lights will begin to twinkle white.
* On first powerup, the Tree Lights will set up a WiFi Access Point.
* On a successful connection to the world wide web and Adafruit IO, the lights will change to the current global colour (which could be white).
