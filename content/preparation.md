### What you need for implementation is, a

- computer device with an Ethernet and serial TTL connection
- TFTP server and Console client running on your computer
- Sercomm NA502(s) gateway with the cover/housing removed
- 3-pin serial connection to the unpopulated 4-pin solder pads near the LEDs
  - with the front of the device facing you, the pinout is as follows: `GND - TXD - n.a. - RXD`
  - the serial interface settings are `57600 8N1`
- direct LAN cable connection between computer and gateway. It is the safest to: 
  - manually assign your computer an IP address in the `192.168.x` range, 
  - enter `192.168.1.1` for the router and 
  - use `255.255.255.0` as the network mask.
