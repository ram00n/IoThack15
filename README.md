# Play! aka IoThack15
Our goal at the #IoThack15 is to play around with technology, get some insights and have fun. Learning by doing.
This is the collection of all the small projects.

# 1) LoRa to IFTTT Forwarder (Status: done, PoC working)
Runs on AppCloud, forwards LoRa packets from ThingPark to IFTTT.
<http://iot.dribd.at/project/7>

# 2) LoRa to ThingSpeak Forwarder (Status: done, PoC working)
Runs on AppCloud, forwards LoRa packets from ThingPark to ThingSpeak
One practical application, where we used this building block was the LoRaLei (see below).
<http://iot.dribd.at/project/21>

# 3) LoRaLei (Status: done, PoC working)
Measuring the Limmat temperature and transmitting data over LoRa. The data is then forwarded via IFTTT to ThingSpeak (<https://thingspeak.com/channels/64458>).
Source: <https://developer.mbed.org/users/ramun/code/New_Seeed_Test/>

# 4) Dumpster Diving Sensor (Status: Design fiction, no code, just pictures.)
LoRaWAN => Cheap, anonymous connectivity => Monitoring for everybody => More efficient dumpster diving.
Bruce Sterling called that anticonventional objects (see e.g. <http://www.wired.com/2013/10/design-fiction-anticonventional-objects/>).

# 5) Hello Beacon! (Status: done, PoC working)
A first app using Interactor (<interactor.swisscom.ch>) and some iBeacons. Triggers a notification on the iPhone, as soon as one gets close to a beacon.
Basically, just using the code from here (<https://developer.interactor.swisscom.ch>), updating to the latest Xcode, adjusting the API-key, compiling and downloading it to an iPhone.
To configure the beacons, we used <https://interactor.swisscom.ch/>.

# 6) Wo ist Walter? (Status: done, PoC working)
An offline indicator that shows the current location of a person, using beacons for localization. 
Here we used previous work (IoT-gauge <http://www.instructables.com/id/IoT-Gauge-with-Arduino-Yaler-IFTTT/>) and combined it with an iPhone app. The app is based on the "Hello Beacon"-app but calls an URL in the background.
Source: <http://ramun.ch/IoThack15/Interactor.zip>

In the end, we combined these bits & pieces into a new project: Fill My Basket (<http://iot.dribd.at/project/24>).

