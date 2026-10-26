# kxnStopFuelBurning - 7 days to die (v3.4)

a small mod to stop fuel waste in forges, campfires and
chemical stations. this mod will stop burning fuel when production or melting
is finished.

this mod is not eac compatible, so turn it off.

## download and install

1. place the "kxnstopfuelburning" folder in your 7 days to die mods folder
2. make sure you have harmony mod installed (0_tfp_harmony)
3. launch 7 days to die with eac disabled

## compatibility

built and tested on v3.4.0 b6.

version 1.1.0 and newer only work on v3.x. for v1.x / v2.x, use version 1.0.1.

## credits

this mod is based on the original "ocb stop fuel waste" mod by ocbmaurice,
updated and modified for 1.3 compatibility.

## changelog

### version 1.1.0
- updated for 7 days to die v3.x (tested on v3.4.0 b6)
- rebuilt against the v3 game assemblies; the old dll crashed on v3 because
  `ItemStack.itemValue` and `ItemValue.type` changed from fields to properties
- no longer compatible with v1.x / v2.x

### version 1.0.1
- initial version didn't work with workstations (ie forge). this fixes that.

### version 1.0.0
- initial version for 1.3 b9
- fixed compatibility issues with newer game version
