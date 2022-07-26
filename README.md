# Light-intensity-monitor
**Light intensity monitoring** 
### Overview
Light Intensity Monitoring System
The resistance of an LDR varies inversely with light, i.e., the resistance decreases as the intensity of light falling on the LDR increases.
You can access the data here: [](https://cloud.boltiot.com/control?name=BOLT8023130)

### Things used in this product

- 1 x Bolt IoT Module
- 1 x Micro USB Cable
- 1 x LDR (2 legged device with a red wave pattern disk on top)
- 1 x 10k Ohm Resistor (brown black orange color code)

### Steps for hardware connections:
Steps 1:Insert one lead of the LDR into the Bolt Module's 3v3 Pin.

Steps 2:Insert other lead of the LDR into the A0 pin

Steps 3:Insert one leg of the 10k Ohm resistor into the GND pin

Steps 4:Insert the other leg of the resistor also into the A0 pin

![image](https://user-images.githubusercontent.com/98824642/180957283-e535c4e9-83af-469b-a61d-5db06678b7ab.png)

Code:
`plotChart("time_stamp",` "light");
