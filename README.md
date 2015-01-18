# PSKFreqMonitor
Code for an Electric Imp that provides a visual indicator of the relative quality of PSK on various ham radio bands.

The project is the result of a homebrew challenge to build something ham-related that fits in an altoid tin.

I decided to go with the following constraints beyond the altoid tin:

* Use a Kingbright BC56-11EWA for the display (floating around my junk drawer)
* Drive the display using two 4026 decade counters (also floating around my junk drawer)
* No microcontroller beyond the electric imp
* Buildable on an Adafruit perma-proto half-size perfboard (so that I can prototype right on a small breadboard and move it over).

The display and the two decade counters _just_ fit on the protoboard, if IC sockets are used to raise up the display. This means there's not yet a place to mount the electric imp, solution there TBD.

The device function as follows: 

- The agent fetches data from pskreporter.info every 30 minutes
- The agent then sends the best frequency to the device, as megahertz + one decimal place (eg 143->14.3)
- The device displays the provided frequency.

That's it! Simple.
