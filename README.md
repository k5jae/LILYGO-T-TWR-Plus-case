# LILYGO-T-TWR-Plus-case

License: GPLv2

## Rationale

The T-TWR Plus has some unique features that made this case desirable. Since LILYGO has released the OpenEdition, we now have a unique M17 capable device. For more information go to M17 (https://m17project.org) and OpenRTX (https://openrtx.org). This case was designed in support of those projects. It was designed in FreeCAD Link branch version 2023.321.

Note: The audio speaker is behind the display shell and audio quality and levels have not yet been determined when the device is fully encased. Testing will take place by 15JUL23. Also, there is currently no battery cover which is still TBD.

## Printing Steps

Print the following (from the stl directory of this repository):
1. LILYGO-T-TWR-Plus-case-bottom.stl*
2. LILYGO-T-TWR-Plus-case-top.stl*
3. LILYGO-T-TWR-Plus-case-buttons_lg.stl
4. LILYGO-T-TWR-Plus-case-buttons_sm.stl
5. 2x Spacer_8_5mm.stl (Only if not using the Pogostick)

\* Pogostick USB port is not exposed in these files use the following instead:
* LILYGO-T-TWR-Plus-case-bottom_pogostick.stl
* LILYGO-T-TWR-Plus-case-top_pogostick.stl

The spacers are to hold the space for the missing PogoStick board, which will be available to program the T-TWR Plus.

Note: The tolerances are fairly tight, so make sure you are using 0.2 mm layer height with high quality settings.

Testing so far:
* Prusa i3 MK3S with PLA and PETG, 100% infill, (supports only for counterbores which pop out with a small screwdriver)

## Assembly Steps

### Prepare the T-TWR Plus
Prepare the T-TWR Plus for assembly by removing the two screws holding the display shell and drilling all of the holes with a 1/8" drill bit. This is due to the board using M2.5 screws, and the case is defined as using M3 screws. M3 nylon screws are more secure than M2.5. The drilling steps are easy if you take your time. Normally using a sharp drill bit in reverse is gentle enough to cause no damage.

For the lower holes, drill to the halfway point and flip the board over to finish (this keeps it nice and clean)
For the upper holes (with the display shell), use start at the back (PCB on top) and drill in reverse until through PCB and then switch to forward direction through the acrylic. Fast speed, low pressure

### Assembly
The button pairs are different lengths. This is due to the placement of the buttons on the LILYGO T-TWR Plus PCB. 
1. The shorter length are the two closest to the sma connector.
2. The longer length are the two closest to the wheel button.

The spacers are to be used when the Pogostick programming board is not installed. The spacers go between the top case and the PCB next to the Wifi/BT module. When installing the Pogostick board, install with USB port down (ie all components underneath). Also ensure that the STL file you are printing has the USB port exposed.

The screws are defined as Nylon M3, with a minimum length of 25 mm. The upper screws should go through the display shell, T-TWR Plus PCB, and bottom case. The lower screws should go all the way through the top case, Pogostick (or spacers), T-TWR Plus PCB, bottom case. The bottom case has a counter bore for a nylon hex nut.

## Views

<img src="https://github.com/k5jae/LILYGO-T-TWR-Plus-case/blob/main/views/real_top.png" width="400">

|<img src="https://github.com/k5jae/LILYGO-T-TWR-Plus-case/blob/main/views/front_left.png" width="300">|
<img src="https://github.com/k5jae/LILYGO-T-TWR-Plus-case/blob/main/views/front_right.png" width="300">|

<img src="https://github.com/k5jae/LILYGO-T-TWR-Plus-case/blob/main/views/rear_right.png" width="300">
