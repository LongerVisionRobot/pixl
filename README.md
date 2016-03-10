# pixl
Pixl is a small board made for using Dynamixel XL-320 motors on a Raspberry Pi.
The board is made with [circuitmaker](circuitmaker.com), a EDA software tool from Altium available as freeware for any kind of projects.

To modify the board or export the last production files, [follow this link](http://workspace.circuitmaker.com/Projects/78A4FE38-92CD-4DAB-9B5A-15E9EAD0FAC1). An account on CircuitMaker is needed to download documents.

This GitHub repository is only made for keeping a copy of productions files without having to log in circuit maker.

## Features
* It powers up the Raspberry Pi from the 7,5V motor power with an embedded voltage converter.
* It provides a conversion from the 5V TTL half duplex bus of Dynamixel motors from the 3.3V UART ports of the Raspberry Pi.
* You can power up your motors and the Raspberry Pi from a 7.5V as well as with Robotis batteries (LBB-040.

## Precautions
**You need to swith off the power supply of the pixl before to put in or to take off the pixl of the Raspberry pi**. Otherwise, there is a small risk to burn the power converter of the pixl board.

## Contributing
You can share your experience, new design, ideas or questions on the [Poppy project forum](https://forum.poppy-project.org/).

## Pictures
![](images/rpi_pixl.jpg)
![](images/pixl_battery.jpg)

## Licence
This board is licenced under the [Creative Commons Attribution-ShareAlike 3.0](https://creativecommons.org/licenses/by-sa/3.0/) (CC-BY-SA) licence.
