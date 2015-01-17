# PSKFreqMonitor
Code for an Electric Imp that provides a visual indicator of the relative quality of PSK on various ham radio bands.

The project is the result of a homebrew challenge to build something ham-related that fits in an altoid tin.

Electric Imp is an electronics component that lets you drive electronics from the cloud (see http://electricimp.com/)

In this case, we have an agent that checks PSKReporter.info's web service for the top ten (most active) band/freq for PSK, and translates it into a 10 point scale that can be displayed on a ten-LED bar indicator.

A 3-part 7-segment display displays the frequency, and a button toggles between the frequencies and values. Two decade counters drive 2 of the 7-segment displays, as the first digit just needs to be 1 or off. A third decade counter is hooked up to drive the ten-LED bar indicator.

Currently in prototype mode!
