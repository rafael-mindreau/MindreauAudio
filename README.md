# Mindreau Audio Octane

8-way mixing attenuverter/utility for Eurorack

## Features
- 8 inputs and outputs
- 8 potentiometers to attenuvert incoming signals. CW is positive, CCW is inverted. Middle is mute.
- If input is not plugged, acts as a constant voltage utility +10V/-10V
- If output is not plugged, chains signal to the next channel below it (daisy-chained)

In short, this allows you to:

- Control parameters on other devices that only have CV and no knobs (like an Ornament & Crime)
- Mix signals together
- Fix phase problems by inverting signals
- Attenuate hot signals
- Offset signals from 0V if any device requires this

> I was looking for an open-source utility that packed a lot of attenuverters in less HP. I couldn't find one right off the bat, and what really got the ball rolling is the daisy-chaining/mixing capabilities such a module can potentially have. I started designing this with the idea to share it to the community. This is very similar to the Antumbra ATN-8 module, which I wanted, but it was not open-source. This module also cuts back on LEDS, which saved space, spared some extra devices and even power consumption.

## CC BY-NC-SA 3.0
