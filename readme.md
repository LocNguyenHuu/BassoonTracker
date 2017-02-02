# Bassoon Tracker

Browser based old-school Amiga Music Tracker in plain old javascript.

![Bassoon Tracker](./skin/screenshot.png?raw=true)

Plays and edits 4-track Amiga Mod files.  
Live demo at [http://www.stef.be/bassoontracker/](http://www.stef.be/bassoontracker/)

If you have ever heard of [Protracker](https://en.wikipedia.org/wiki/Protracker) or [Fasttracker](https://en.wikipedia.org/wiki/FastTracker_2), then you know the drill,   
if not, then you are probably too young :-)

It needs a modern browser that support WebAudio.
It's tested to work on Chrome, Firefox, Safari, Edge, Chrome on Android, mobile Safari and the Samsung Android Browser.
it works best in Chrome.

Features  
- load, play, edit and save Protracker compatible module files  
- most audio effects are supported (but probably not 100% accurate)
  - Frequency slides (Effect 1, 2, 3 and 5)
  - Vibrato (Effect 4 and 6)
  - Tremolo (Effect 7)
  - Arpeggio (Effect 0)
  - Sample offsets (Effect 9)
  - Volume slides and settings (effect A and C)
  - Position jumps (effect B)
  - Speed settings (Effect F)  
- mute/solo tracks  
- edit pattern data and sample properties  
- import 8bit WAV, 8SVX and RAW samples (as well as any other format AudioContext can read, like .mp3 and .ogg) 
- includes the historic ST-01 and ST-02 sample disks, released in 1987  
- export to .wav and .mod

Missing features and bugs
 - Not much disk operations yet, you can load new modules and samples by drag-dropping them on the interface  
 - The various "E" effects are not implemented yet  
 - The sample editor needs fleshing out.
 
Note: if you use an AZERTY keyboard, you can set that option in the settings to have the correct octave layout when playing notes on your computer keyboard.
