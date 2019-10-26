# Over_Temperature_Detector
Device sounds a buzzer if temperature rises above a threshold. The project utilizes Simulink and an Arduino Uno. The motivation for this project was the loss of a freezer full of food due to a door left ajar. 

# Introduction
The project was inspired by the loss of most of the food in a freezer after the door was left ajar. If the freezer would have alerted the home occupants shortly after the door was left ajar a lot of expensive meat could have been saved. An online search for freezer over-temperature alarms uncovered some commercial products, but I wasn't satisfied with any of them. They appeared to either be of low quality or require some sort of subscription. I decided to make my own. I was already looking for a small hobby project that involved both Simulink and Arduino. This was a good fit.   

# Materials
* Arduino Uno with headers
* Temperature-humidity sensor (Adafruit, [AM2302 wired DHT22](https://www.adafruit.com/product/393))
* Solid state relay, 600 mA, 0-60 V  (Digi-Key, [CLA274-ND](https://www.digikey.com/product-detail/en/ixys-integrated-circuits-division/CPC1218Y/CLA274-ND/1277129))
* Buzzer, 3-20 V (Digi-Key, [668-1350-ND](https://www.digikey.com/product-detail/en/pui-audio-inc/AI-3135-TF-LW100-R/668-1350-ND/1745459))
* 9V 1A Arduino Power Supply Adapter 110V AC (Amazon, [Adapter](https://www.amazon.com/gp/product/B018OLREG4/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1))
* 10 Kohm resistor
* Various jumper wires
* 22 Gauge wire of various colors
* Wago 221-413 LEVER-NUTS 3
* Half-size breadboard
* Plastic project box, 7.6" L x 4.51" W x 2.95" H 
* Hook and loop fasteners with adhesive backing
* Gorilla tape, duct tape

# Tools
* Simulink 2019b with Stateflow
* Arduino Additional Sensors Library (DHT, LPS331) for Simulink [Library](https://www.mathworks.com/matlabcentral/fileexchange/62878-arduino-additional-sensors-library-dht-lps331)
* Drill and bits

# Assembly 
![Schematic](images/overtemp_schematic.JPG | width=100)
<img src="https://github.com/travis23/Over_Temperature_Detector/blob/master/images/overtemp_schematic.JPG" width="100">
