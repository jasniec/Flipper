# Various SUB files I've found or created. Some tested, some not.

Special thanks to [FalsePhilosopher](https://github.com/FalsePhilosopher) for organization help and everyone else that shares files!

## NOTE: The deBruijn and OpenSesame files have moved to the [Garages subfolder](https://github.com/UberGuidoZ/Flipper/tree/main/Sub-GHz/Garages/deBruijn).

You can generate MANY of your own SUBs, such as MegaCode and Firefly, over at [Flipper Maker](https://flippermaker.github.io/).

Looking to mess with garage doors? You can try the OpenSesame/deBruijn files above.<br>
(Also check out more info at [RemoteDup](https://www.ifoedit.com/RemoteDup.html), [GarageHack](https://www.ifoedit.com/garagehack.html), and [Learn Button coding](https://support.dealer.liftmaster.com/articles/Knowledge/Determine-the-Color-of-the-Learn-Button-on-Your-Garage-Door-Opener).

# Frequency limitations and caveats

Officially supported frequencies: 300-348 MHz, 387-464 MHz, and 779-928 MHz (from [CC1101 chip docs](https://www.ti.com/product/CC1101))<br>
Unofficially supported frequencies: 281-361 MHz, 378-481 MHz, and 749-962 MHz (from [YARD Stick One](https://greatscottgadgets.com/yardstickone/) CC1111 docs)

No mainstream firmware (Official, Unleashed, or RogueMaster) currently allow anything outside of the officially supported CC1101 specs.

**NOTE: Going outside the supported frequencies may DAMAGE YOUR FLIPPER AMP.<br>
Please understand what you're doing if trying to break out of official frequencies.**

You'll need to edit some code and recompile if you want to break outside of the officially supported frequencies. ([Hint here...](https://github.com/flipperdevices/flipperzero-firmware/pull/1287/files))

`Allowed to transmit (MHz):`<br>
`R01: 433.05-434.79; 868.15-868.55`<br>
`R02: 304.10-321.95; 433.05-434.79; 915.00-928.00`<br>
`R03: 312.00-315.25; 920.50-923.50`<br>

`Shipped to:`<br>
`R01: EU, UK, RU, UA, BY, BA, PF, VA, IS, KZ, LI, MD, MK, NO, RS, CH, TR`<br>
`R02: US, CA, AU, NZ, MX, BR, CL, AR, UM`<br>
`R03: rest of the world`
