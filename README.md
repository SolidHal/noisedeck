# noisedeck

a cyberdeck for music creation

## Size constraints

btrfld:
- 129mm deep
- 215mm wide


## parts
hinges:
https://www.amazon.com/gp/product/B0BFWNJMCY/

hinge fasteners:
M3x8 countersunk fasteners: https://www.amazon.com/HanTof-Countersunk-Machine-Wrenches-Threaded/dp/B0B9HWVV61
M3x10 countersunk fasteners
M3 threaded, DIN 562 flat square nuts: https://www.amazon.com/M3nS-Printers-Stainless-Conform-Quantity/dp/B0BD2N9KTV

dac power switch:
https://www.amazon.com/dp/B075RC6TFB

apple pencil charging cradle:
https://www.amazon.com/Paiholy-Compatible-Generation-Lightweight-Convenient/dp/B0BMB7362T

midcase fasteners (plastic to plastic):
m2x5 and m2x6 tapered flat head self taping screws

cheap ipad magnetic folio case

btrfld keyboard: https://github.com/SolidHal/btrfld

usbc to 3x usbc (2 data, one power): https://www.amazon.com/gp/product/B09PFR2J82

usbc to 4x usbA : https://www.amazon.com/dp/B09N36LZSQ

usbA dac: https://www.amazon.com/dp/B01DLY3IW8

usbc right angle extension: https://www.amazon.com/dp/B0B71BZ4YF


## features
- btrfld keyboard
- trackpad
- headphone jack
- mic jack
- 1x usb c ports
- 2x usb a ports
- ipad
- ipad pencil + charging space
  - use https://www.amazon.com/Paiholy-Compatible-Generation-Lightweight-Convenient/dp/B0BMB7362T in the deck

future:
- extra keys in topcase for common hotkeys(?)
- choc key one octave keyboard in topcase(?)
- pitch joystick/wheel that snaps back to the center


## Notes

dac needs a power switch, otherwise the ipad will always use it by default and never allow usage of the speakers

TODO:

- holes in midcase/topcase and lid for latch(?)

- extra keys in topcase for common hotkeys(?)
- choc key one octave keyboard in topcase(?)


## Assembly notes

case:
- use 52 gauge drill bit to clean out midcase holes for the m2 screws
- use 46 gauge drill bit to clean out topcase holes for the m2 screws
- use chamfer bit on bottomcase holes screws sit flush
- glue eyeglass nosepads to bottomcase for feet
- hinges need to be filed/ground shorter on the side that would otherwise stick out through the bottom case
- cleaning out the hinge holes in the ipad enclosure is annoying. Recommend using a 46 gauge drill bit
- tear down the ipad folio case to just the parts required to hold the magnets in place. lets call this the "case core"
  - attach a thin film to the side of the case core that magnetizes to the ipad
  - superglue the case core into the ipad enclosure so that the ipad is held into the ipad enclosure magnetically

wiring:
- cut one usbA and solder to btrfld
- cut one usbA and solder it to the trackpad
- cut one usbA. solder power to the switch. solder the switch to both the pencil charging cradle and the dac. solder all 3 grounds together. solder data from the cut usbA to the dac
- super glue one usbA into the midcase

ipad -> extension -> usbc/usbc 3 way splitter -> one usbc charging port, one usbc data port, and the usbc to usbA splitter