MooseAPC is a variant of the classic Atari Punk Console 555-based noisebox (see http://www.jameco.com/Jameco/PressRoom/punk.html for a good example).

The goal here was to make something fun for my kid to play with. Specifically:

- I wanted to be able to toggle between pots and photoresistors for controlling the two timers
- Volume knob with a not-obnoxious total volume
- I wanted some kind of blinky lights
- I wanted a toggle between a continous tone and a button-press.

The lights trigger off the first timer (which provides the main pulse). We route though two decade counters to drop the frequency by a factor of 100, turning the AF into something visible on LEDs. One LED is on the 1 and the other on the 5, creating a nice pattern.

(schematic in progress)