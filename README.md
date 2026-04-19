# frameworkLTE
yet another custom made framework expansion card - hoping to get high speed LTE on your Framework Laptop!

## what?
well I think this project is pretty self explanatory! this would be a simple expansion card that by simply connecting it via USB-C (and having a SIM card inserted inside) would give you (up to) LTE connectivity with access to calls and texts! this would both work on Windows and Linux.

## why?
well I got a Framework Laptop with the Hack Club siege event. AND I LOVE IT SO MUCH! but one thing that always pisses me off is when i have my laptop in my backpack after leaving school, and my phone just dried dead, leaving me with no way to listen to music on the way back home, or text friends, or read some article on the internet! with this, this would almost never happen again! the point would be to kinda have a "always ready to be connected" machine, and it's a quite trending topic on the Framework forums!

## 3D model renders

![blender_IPzTZ7QsCJ](https://stasis.hackclub-assets.com/images/1776632943862-26svzr.png)

![blender_xah0X6ovwA](https://stasis.hackclub-assets.com/images/1776632943855-nbi1tp.png)

![blender_WcQUzrBij6](https://stasis.hackclub-assets.com/images/1776632943848-hbcgpn.png)

## wiring diagram
well considering we're using a donor PCB from a LTE USB modem card, our only wiring here is the USB A of the PCB to the USB C for the framework laptop's mobo (i don't have a soldering iron so i can't actually make a proper USB C output on the PCB, sorry!!! maybe one day? pinecil?)

[ PCB (Modem) USB A output ] -> USB A to USB C convertor -> USB C input of the Framework Laptop motherboard

## BOM (bills of materials)
change to your liking! parts found entirely from aliali!

| Name                         | Purpose                                                                                     | Quantity | Total Cost (USD) | Link                                                                                     | Distributor                         |
|------------------------------|---------------------------------------------------------------------------------------------|----------|-------------------|------------------------------------------------------------------------------------------|--------------------------------------|
| enclosure (expansion card)   | actually housing all the components (like the stripped modem)                               | 1        | 5.00              | https://printlegion.hackclub.com/                                                        | hackclub printlegion                 |
| USB-A to USB-C ribbon cable  | link the modem's USB port onto the framework USB-C interface on the mobo                    | 1        | 5.68              | https://www.aliexpress.com/item/1005003510149476.html                                   | AliExpress FR                        |
| 1mm thermal pad              | thermal pad to cool down the modem (shouldn't run that hot anyway)                          | 1        | 2.00              | https://www.aliexpress.com/item/1005011996909943.html                                   | AliExpress FR                        |
| 5mm Kapton Tape              | to properly shield between the modem and the actual framework frame itself                  | 1        | 1.16              | https://www.aliexpress.com/item/1005007518587827.html                                   | AliExpress FR                        |
| ZTE MF79U dongle             | donor PCB: LTE modem to be placed inside the Expansion Card                                 | 1        | 35.72             | https://www.aliexpress.com/item/1005005844914823.html                                   | AliExpress FR                        |
