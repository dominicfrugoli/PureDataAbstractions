# Pure Data Abstractions

A location for storing all my Pure Data abstractions. Most are quite versatile, but some are made for specific projects so they aren't as easily usable. Take a look at the help patches for each object to see how to use the abstraction. Thanks for taking a look and hopefully some can be of some use!


# List of Objects

#### Signal Objects
- [asrenv~] -  A 3-stage envelope generator with an attack, sustain, and release input
- [basictape~] - a basic tape-style delay with modulation and filtering
- [chorus~] - a chorus/vibrato with rate, depth, and mix controls
- [crossfade~] - a simple linear crossfade for two signal inputs
- [feniverb~] - a reverb object using the [jon~] reverb (link to github project at bottom of page)
- [grain~] - an object for reading a grain of audio from an array, based off code from QCGInteractive Music (link to video at bottom of page)
- [modalf~] - a resonant bandpass filter with randomization for use in a modal synthesis engine
- [reso~] - a bank of 6 resonant band-pass filters for creating a modal synthesis voice
- [saturation~] - a basic mono saturation overdrive, based on code from Toxonic (link at bottom of page)
- [saw~] - a full-scale sawtooth oscillator that has forward and reverse saw
- [spdt~] - a toggle switch for routing an audio signal between two locations

#### Message Objects
- [boolswitch] - a simple switch for sending a boolean value (0 or 1) to one of two outlets
- [counter] - A no-frills counter for counting either positive or negative by any interval
- [dec] - a decremental counter for negative counting by one
- [inc] - an incremental counter for positive counting by one


## Download Instructions
    1. Download the full code from github
    2. Unzip and store the folder somewhere
    3. Open Pure Data and go to the Path Preferences
    4. Then make a new path that leads to both the "message_objects" and "signal_objects" folder
    5. Test out the paths by using some of the objects in a patch
    6. Have some fun!

Pure Data (at least on Mac) seems to only be able to read one folder deep so just making a path for the abstractions folder doesn't seem to work. This is why I talk about making a path for both the message_objects folder and signal_objects folder since Pd seems fine with that. This should let you use the abstractions in any patch without issues.


## Authors

- [@dominicfrugoli](https://github.com/dominicfrugoli)
    - https://www.dominicfrugoli.com


## Acknowledgements

 - [QCGInteractiveMusic](https://www.youtube.com/watch?v=QX_saH55cks) - code from this video used in [grain~]
 - [Anton Hornquist](https://github.com/antonhornquist/jon-pd) - jon-pd code used in [feniverb~] (jon~ likely must be installed in order to use [feniverb~])
 - [Toxonic](https://forum.pdpatchrepo.info/topic/2722/saturation) - saturation code used in [saturation~] 


## License

[MIT](https://choosealicense.com/licenses/mit/)

