# Ground Station Hardware & Bill of Materials (BOM) 

Real world Ground Station designs are often based on a standard baseline Bill of Materials with options for customization to meet user needs. In this tutorial, you'll find two hardware builds. If you make a custom build, please feel free to submit your build pictures! We'd love to hear from you.  

All figures in the BOM are in USD.

## Baseline Items | Cost: $431

| Item      | Description | Cost | Quantity | Total | Link | Notes |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| GOES Kit      | This is our RF ground station kit       | $199       | 1       | $199       | [Nooelec Goes Bundle](https://www.amazon.com/dp/B07K25Y1JW)         |  Comes with antenna, LNA and RTL-SDR       |    
| Tripod   | Tripod to mount the antenna         | $52       | 1       | $52       | [Tripod](https://www.amazon.com/Tripod-Satellite-Mount-Antenna-Network/dp/B0B2213CV7)       | NA      |    
| Raspberry Pi 4   | This is our edge compute housing all our containerized RF and monitoring solutions        | $180       | 1       |   $180     | TBD       | Currently, there is a raspi shortage.       | 


## Case Option 1

| Item      | Description | Cost | Quantity | Total | Link | Notes |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Header      | Title       | Title       | Title       | Title       | Title       |  Title       |    
| Header   | Text        | Title       | Title       | Title       | Title       | Title       |    

## Case Option 2 | Cost: $57

| Item      | Description | Cost | Quantity | Total | Link | Notes |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Enclosure      | Weatherproof enclosure 11.4"×7.5"×5.5"       | $35       | 1       | $35      | [Enclosure](https://www.amazon.com/gp/product/B09SLJY6RV)        |  NA      |    
| SMA connector   | SMA connectors to connect RF LNA in enclosure to antenna through a bulkhead        | $8       | 1       | $8       | [SMA Connectors](https://www.amazon.com/dp/B00AA2HE34)     | NA       |       
| USB connector   | USB Bulkhead connector to power the Raspi        | $14       | 1       | $14       | [USB Bulkhead connector](https://www.amazon.com/dp/B07RPW5XGB)       | NA       |   


## Lightning Protection & Grounding (Optional) | Total: $70

Lightning protection and proper grounding are important. In this tutorial, the reccomendation is that you only use the ground station during clear sky conditions. Store it during other times. The portability of the kit to take to schools is a benefit of the tripod setup. However, for permanent installations, check with your local rules and/or facilities manager for proper grounding techniques. 

The ARRL has a nice description on grounding that can be found at: <http://www.arrl.org/grounding>

In a home installation, typical options include SMA lightning arrestors and grounding to a rod located at least 15 feet from the home. This is typical with setups for satellite TV such as "DirecTV."

| Item      | Description | Cost | Quantity | Total | Link | Notes |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Antenna Grounding Wire (12ga)      | Antenna to mount grounding       | $12       | 1       | $12       | [Grounding Wire](https://www.amazon.com/Feet-7-5-Meter-Residential-Commerical/dp/B07JBQT8LY/)       |    Connect from the antenna to the mount     |    
| SMA Lightning Arrestor   | SMA lightning arrestor           |  $18    | 1       | $18       | [SMA Lightning arrestor](https://www.amazon.com/dp/B07K25Y1JW)       | These have a life span due to the gas used in them.        | 
| Grounding rod   | Grounding rod to ground antenna mount        | $40       | 1       | $40       | [Grounding rod kit](https://www.amazon.com/Electric-Satellite-Instruments-Generator-Grounding/dp/B09BLZ2M58/)       | If the install is a roof of a facility, there may be ground paths already that you can connect to. Grounding rods are meant to go into the ground of your backyard.       | 


## Misc Hardware (Optional, some of this you may want to testing and/or building)

| Item      | Description | Cost | Quantity | Total | Link | Notes |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Sockitbox      | Enclosure for cables and power supples       | $30       | 1       | $30       | [Box](https://www.amazon.com/gp/product/B006EUHT2W)  |  TBD       | 
| SMA Cables   | Various SMA cables for interconnects        | $13       | 1       | $13       | [SMA cables](https://www.amazon.com/SDTC-Tech-Coaxial-Assembly-Extender/dp/B07NCLZWHH/)       | Depending on your install, you might need Misc SMA Cables    |
| Step Drill Bit Kit   | Step Bits to help create the openings in the enclosure box        | $20       | 1       | $20       | [Step Bit Kit](https://www.amazon.com/gp/product/B09GXP5WSH)       | Step Bits are the easiest way to modify plastic enclosures       |   
| USB A to USB A   | A cable to extend the RTL-SDR away from the Raspi        | $3       | 1       | $3       | [USB A to USB A](https://www.amazon.com/gp/product/B00CJG2ZYM/)       | Extends RTL-SDR from Raspi       | 
| USB to Micro USB   | The cable needed for the LNA if you wish to use the Raspi for power        | $8       | 1       | $8       | [USB to Micro](https://www.amazon.com/gp/product/B01FSYBQ9Q/)       | Power LNA from Raspi       | 
| Long USB Cable    | Long USB cable to provide power        | $10       | 1       | $10       | [USB Cable](https://www.amazon.com/gp/product/B00NH12O5I/)        | For USB powered enclosure       | 
| GPS Unit   | A GPS unit to setup a time server at your gateway        | $20       | 1       | $20       | [GPS](https://www.amazon.com/gp/product/B01EROIUEW/)          | Not covered in the first release of this tutorial but a good option for GPS based NTP       | 


