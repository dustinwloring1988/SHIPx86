# SHIPx86
![Case Render](case_render.png)

Files for the SHIPx86 console and cartridges.

## About

The SHIPx86 is a small LattePanda Iota power computer which uses retro style cartridges to store movies, games, and whatever else. These messy files are shared with no warranty for those who wish to try to recreate the device!

This repo contains...

* `automon` - The code to automatically monitor and run carts. Pull this repo down and run `./install.sh` on the Iota and it should install it into the background.
* `cart_reader` - The files required to manufacture the USB SD card reader PCB. Note that the 40-pin edge connector will need to be bought and soldered seperately. (see parts list).
* `carts` - The files required to manufacture a cart PCB and an STL for the plastic cover.
* `case` - The STLs for the device case.
* `case_pcb` - The files required to manufacture the internal PCBs used in the case.

## Tips

### Where should I order PCBs from?
[NextPCB.com](https://www.nextpcb.com/) has sponsored my videos for years and I've always found their work to be high quality. The included BOMs for the cartridge and reader are formatted for their service, however any fabrication house should be capable of producing these simple boards. For the boards used internally in the case, since they do not acquire PCB assembly I've placed an order with OSHPark to see if that is a good manufacturer - I will update here once I verify them as a good option.

### Why is my case wobbly?
When you screw a bunch of 3D printed parts together, it's easy to over-tighten screws which causes warping. If you find your baseplate doesn't sit flat, loosen all the base screws half a turn, wait 10 minutes, and see if it relaxes to be flat.
