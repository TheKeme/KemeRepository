# KemeRepository
Heakeme Williams

# DMX Board For Crystal Fountains Build Instrutions
                                                         
                                                          

### Background Knowledge

The crystal fountain uses a DMX-Generator which produces the DMX differential signals, this then travels to the DMX-Sender board through the XLR cables in which it is translated into single-ended signal for data in the module. The signal then travels to the DMX-Receiver board via the antennae. The receiver board then converts this single-ended signal back to differential using one the chips and then plugs it right back into the light, which results in the different light sequence based on what is being produced from the generator device.

### Materials\Components Needed

* Linx Module 900
* Resistor (120 Ohms & 100K Ohms)
* XLR Connector
* SMA Cable
* SMA Antenna
* SMA Adapter Cable
* UFL SMT Antenna Connector
* Female 16 pos Header
* Conn Header 100 pins
* Con IC Dip Socket 16 pos
* IC MC3486N
* Conn Audio Male 3 COND


### Boards Needed 

Designing the boards can be quite an annoying process, however, I have designed these boards and they are available for download if needed. 
* To download the DMX Sender board, please click [HERE](https://github.com/TheKeme/SensorEffector/blob/master/ZIP%20FILES/DMX%20Sender.zip)
![Image of the FInal Board](https://github.com/TheKeme/SensorEffector/blob/master/IMAGES/DMXSENDERFINAL.PNG)

* To download the DMX Breakout Board, please click [HERE](https://github.com/TheKeme/SensorEffector/blob/master/ZIP%20FILES/Linx%20Breakout.zip) 


### Components Needed For Testing

* DMX Generator
* Receiver 
* Lights
* Power Adapters


### Soldering Materials Bought to Board

Soldering is quite simple, once you follow the board layout and schematic in Eagle, however some major soldering points will be made, so you dont make the same mistake I did.

1. First Rule is make sure you solder the Con Audio Male 3 COND last.

2. The IC MC3486N is mirrored on the board as you can see, this is to allow all the soldering/routing to be done at the bottom of the board. There when soldering the 16 Pos dip socket, You need to bend the pins, then clip them short enough and solder it on the bottom of the baord. Make sure it is centerd enough to cover the hole. 

3. When soldering the 16 Pos Female Header, solder the ends where no connection is made and then slightly reheat and orient it correctly.

4. The resistors are easy to solder and can be done so anytime. However, make sure they have the right configuration or else it will cause a shortage in the ciruit.

5. Last point when soldering to the Con Header 100 pins to the break out board it is easier to do so on a bread board.


### Implementing Everything Together / Testing.

1. Connect the power adapter to the DMX Generator and provide 12 volts towards it, however do not emanate the voltage just yet.

2. Connect the XLR cable to the DMX Sender board, Remember to read the pin out.

3. Connect the SMA Adapter cable to the Antenna and one to the UFL SMT Antenna Connector.

4. Plug in the Break out board with the module to the DMX Sender Board.

5. Connect the fully connected antenna to the module on the breakout board.

6. Connect a 5 volts to the DMX Sender board however do not power on the supplier yet.

7. Connect the antenna to the receiver board.

8. Supply 12 volts to the receiver board, but dont power on the supply yet.

9. Connect the lights but don't power on yet.

10. Power on all supplies and observe.

### Cautionary Measures
* Do Not place your hands between Antenna when powered on.
* Do not supply higher voltage than necessary.
* Avoid jamming the antennae since that may cause disfunction in the signal.

