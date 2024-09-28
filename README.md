# pcileech-fpga-RW1C

# Credits:

Ufrisk (https://github.com/ufrisk/pcileech-fpga)

spicyninja (discord: spicy_ninja) (UC: spicyninja800)

Ice (discord: ice_1c)

Clincy (discord: cincyyy) (server: https://discord.gg/clincy) 

Modified version of stock pcileech for bypassing the drvscan targeted at detecting RW1C bits.

this is an upgrade to the current Writemask that adds RW1C bits in a .coe mask. Currently only the Device status register is being masked correctly as an example of how to use it and in order to bypass the current ekknod Drvscan method. I would advise learning how to use writemask and then RW1C mask, as it if it is implemented correctly, it should lead to a perfect replica of the device configuration space, without any R/W or R/O detections
