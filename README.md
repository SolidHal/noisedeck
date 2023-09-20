# emdeck

an rk3588 powered cyberdeck, combined with a btrfld



## Size constraints

btrfld:
- 129mm deep
- 215mm wide

rk3588 board:
- 60mm deep
- 95mm wide
- 25mm tall

10.1 1920x1200 display:
(rough underestimate)
- 218mm x 136mm
one such lcd: https://www.aliexpress.us/item/3256804526649221.html?spm=a2g0o.productlist.main.1.73c72bd4YTE0hf

pointing device:
trackpad https://shop.mntre.com/products/mnt-reform-capacitive-trackpad-module
trackball? https://shop.mntre.com/products/mnt-reform-optical-trackball-module

## parts
hinges:
- 43mmx36mm 4 Countersunk Holes Plastic Adjustable Torque Position Control E6-10-301-20 Series Hinge Black Door Hinges
- https://www.amazon.com/gp/product/B07GX8LQCX/

mipi lcd:
troubleshooting:
https://wiki.t-firefly.com/en/ROC-RK3588S-PC/usage_display.html#mipi-dsi
decided to avoid using mipi since debugging it is annoying

lcd:
https://www.aliexpress.us/item/2255800186757029.html
Active Area:217.44(H)×135.9(V) mm

Configuration:RGB Vertical Stripe

Outline Dim.:228.86(H)×152.5(V) ×4.18(D) mm

1.75mm thick aluminum sheet for bottom case

### Battery
- want to use usb-c port for charging
- batteries/screen/board need 12v
- most usb pd chargers give 15, 9, 5v @ 3amps
- need converter from those, to 12v

can only power cpu board from the 12v barrel jack
using 3 x 3.7v  lithium batteries
like
https://www.amazon.com/dp/B07TXLHLFW?psc=1&smid=A132D7PL1YID8X
5.7mm thick, 58x104mm
need a 3s, 3-4 amp, 12v bms like
https://www.ebay.com/itm/383857553644
buck/boost converter like
https://www.amazon.com/dp/B07NTXSJHB?psc=1&smid=A2TKGQERXRZT6A
usb c power delivery controller
https://www.sparkfun.com/products/15801


## features
- btrfld keyboard
- rk3588
- trackpad
- webcam(?)
- mic(?)


## Notes
Armbian
https://bbs.stationpc.com/forum.php?mod=viewthread&tid=323&extra=page%3D1%26filter%3Dauthor%26orderby%3Dlastpost

Theres usb 2.0 on the gpio?
https://bbs.t-firefly.com/forum.php?mod=viewthread&tid=3198&extra=page%3D2

consider design of mnt reform pocket:
https://www.crowdsupply.com/mnt/pocket-reform

TODO:
find countersunk m3 bolts for hinges, figure out nut placement

angled and magnetic(is this a feature?) usb cable for btrfld

figure out long bolts and holes to hold together the case

place ports:
usbc power delivery controller
ethernet
audio jack
