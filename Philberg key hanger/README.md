# Philberg key hanger

This project was meant as a birthday present for a friend of mine. The build was an idea I had for some years in which you could plug in your keys into a knock-off synthesizer panel. There would be a makeshift hanger for your keychain with a 6.3mm jack. You could then plug in the jack into the female connectors on the panel.

## What's in the package
I made a panel using front-panel designer and converted it to `dxf`, but you could do this directly in KiCad. I imported this into KiCad to make it a PCB. I made some graphics using Illustrator and assigned this to the silkscreen layer. The PCB contains no traces or routing, but you could use the copper layers to add gold plated effects if you want to go fancier.

## How to order this as a panel
I used JLCpcb to order a 1.6mm thick aluminium panel with black color. The silkscreen is white and makes for a good combo. There are other colors available, and your boardhouse may or may not provide other options as well.

## How to build it
Order parts in function of the hole sizes. I had to post-drill mine because of sizing issues. Check the datasheet for the right sizes and change the hole sizes in KiCad. I had the following parts planned for my panel:

* 4 6.3mm female jack connectors for the bottom four holes
* 4 red LEDs right above the jacks (double check clearance for the nuts of the female connectors)
* 1 middle hole for the potentiometer
* 1 hole next to the potentiometer for a switch

## Extras
I went the extra mile to actually wire the electronics up, and make the LEDs illuminate when the jack was removed, but the behavior could easily be reversed. I used the potentiometer as a dimmer for the LEDs and the switch to turn everything on or off. There were also two AA batteries keeping everything powered. I encased the panel in some birch multiplex and colored it with a dark stain. The result was a very unique gift.

## Alternatives
While building this, I was surprised to find that Marshall also had a similar idea and gadget themed around guitar amps. However, I'm not a guiter fan and neither is my friend. We're synth buddies, so this version had to be made. You could of course check out those other things as an alternative.
