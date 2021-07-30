# PowderShaker -- vibratory addon for Dillon 550/650/750 powder measures

PowderShaker is a small add-on device for Dillon powder measures that helps with uniform powder drop.

It's activated on every drop and uses micro-USB cable to power itself. All components are widely available and the total cost would be around $10.

There are three 3D-printed parts that provide the housing for components and the mount. You'll also need the following components, a soldering gun, and a little bit of skill to assemble it all together:

* Mitsumi R14 mini M20 vibration motor with eccentric wheel ([example](https://www.ebay.com/itm/123180653659))
* USB-powered delay relay ([example](https://smile.amazon.com/dp/B0832MW9L4/)) 
* Micro roller switch ([example](https://www.ebay.com/itm/303542468171))
* 220uF - 330uF electrolytic capacitor (other capacity will work too but you'll need to adjust the timer, larger capacity means longer vibration time)
* 4.7k - 5.6k resistor (other values may work too)
* 5 M4x20 bolts
* 5 M4 nuts
* 2 M2x12 bolts (you can also use M2x16 bolts)
* 2 M2 nuts
* wires

## Assembly instructions:

[See all pictures of major steps in this gallery](https://imgur.com/a/fLLn6EH)

1. Print three parts using PLA+ or similar plastic with the following settings:
    * Layer height: 0.2mm
    * Infill: 20%
    * Support: yes
    * Support join distance: 1mm (only matters for the mount part)

2. Connect V+ to the middle relay connection (COM)
3. Solder the capacitor and resistor in parallel
4. Solder a wire to the negative electrode of the capacitor and connect it to the motor
5. Connect the other motor electrode to NO (normally open) connection
6. Connect the positive electrode of the capacitor to the switch (normally open)
7. Solder the negative electrode of the capacitor to V-
8. Connect TRIG to the switch (common)
9. Affix the switch using two M2x12 bolts with the roller directed outwards
10. Place the relay and the motor in their respective slots
11. Connect the USB cable and verify everything is working correctly. 
12. Adjust the potentiometer on the relay to keep the time when the relay is active around 1.5 or 2 seconds
13. Place the cover on and use two M4x20 bolts and nuts to affix it. Don't apply too much torque.
14. Use two M4x20 bolts and nuts to affix the base to the mount. Nut holes should be looking downwards when everything is assembled.
15. Put the assembled PowderShaker on a Dillon powder measure. Keep in mind that the top part is slightly wider than the bottom.
16. Make sure the powder bar activates the switch on the upstroke.
17. Use M4x20 bolt and nut to tighten the PowderShaker to the powder measure.
18. Connect the USB cable and, using a case, activate the powder drop and check if everything is working correctly.

Use several drops before you start loading to make sure the powder drop is more uniform. If you want to stop using it, simply disconnect the USB cable.

## Visuals

* [This is how it looks like on the press](https://i.imgur.com/fNcFmbQ.jpg)
* [This is another picture from the side](https://i.imgur.com/8c4y25w.jpg)
* [This is my lousy soldering job](https://i.imgur.com/DSIlx3z.jpg) that shows how it's assembled inside the box
* [This is a gallery of pictures of major assembly steps](https://imgur.com/a/fLLn6EH)
* And finally, [a video of everything in action with powder drop measurings](https://www.youtube.com/watch?v=0ZiXqV_TVxc)

## License AKA **You cannot sell it**

This project is released under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License. What it means to you in just four words?

***You cannot sell it***

You can share and adapt it freely. I cannot revoke these freedoms as long as you follow the license terms, specifically:

* Attribution - you must give appropriate credit
* Non-Commercial - you cannot profit from it
* ShareAlike - if you change something, you must use the same license terms

Full license text can be found at https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode

Copyright (c) 2021 sttek.com
