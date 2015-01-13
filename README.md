# PSKFreqMonitor
Code for an Electric Imp that provides a visual indicator of the relative quality of PSK on various ham radio bands.

The project is the result of a homebrew challenge to build something ham-related that fits in an altoid tin.

Electric Imp is an electronics component that lets you drive electronics from the cloud (see http://electricimp.com/)

In this case, we have an agent that checks PSKReporter.info's web service for the best (most active) band/freq for PSK, and translates it into a simple 5 point scale that can be displayed on a ten-LED bar indicator.
