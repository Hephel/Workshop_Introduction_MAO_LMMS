# Workshop_Introduction_MAO_LMMS

The purpose of this workshop is to learn basics about music composing in computer. We'll se that with using LMMS, an amazing open-source DAW.
During this workshop, you have to remake a music that I made in LMMS. Don't panic ! Every step will be explained, and Internet is full of answer ;)

Don't hesitate to check the doc -> https://docs.lmms.io/user-manual/

## Step 0 - Install packages

Ubuntu -> sudo apt-get install lmms

Fedora -> sudo dnf install lmms

## Step 1 - Git clone and listen!

Okay. Inside this repository, you will find a package.zip, with differents files who are useful for next steps.
First, listen carefully the result.mp3 file.

Have you done ? Ok, we can start. Open LMMS.

## Step 2 - Let's begin with chords

### 2.1 - Basic importation

-> import the chords.mid file

-> import the pluck1.xpf preset : you create a _Progressive Pluck_ instrument. Combine it with chords midi pattern.

Ok. Listen that. Have you noticed ? Tonality is not good. Change it.

_Hephel's tip : Find how to loop the pattern, it's really handy !_

### 2.2 Add effects

Add some effects in the effects chain tab, inside the instrument window :

-> _Amplifier_ ; gain = 6,6

-> _StereoEnhancer_ ; wide = 54 samples

-> _C* Plate2x2_ ; bandwith = 0,50 ; tail = 0,41 ; damping = 0,25 ; blend = 0,19

Ok ! You have your chords pattern. Sounds amazing, isn't ?

## Step 3 - Add some drums

In the package.zip, you will find three .wav files : a kick, a clap and a hat.
Create two patterns : first with only a kick, and second with three drums. Listen carefully to find how second pattern is agenced !

_Hephel's tip : the second pattern is a classic house drums pattern. You've heard it so many times before..._

## Step 4 - Sidechain compression

Ok. Let's a create a real amazing effect : a sidechain compression. The principle is quit simple : each time the kick will hit, the chords sound will be compressed, and sound less loud. The sidechain effect allows to create a really great dynamic.

So, create a sidechain and apply it on the chords.

_Hephel's tip : you will find many videos on youtube about that._

## Step 5 - Arrangement

Now, arrange your music. Copy and paste the chords patterns, superpose the drums patterns. Be careful about drums cut. 

_Hephel's tip : listen to the music several times, to be sure of the arrangement._

## Step 6 - Automation

You surely noticed it, but there is still something missing. In fact, the sound texture of _Progressive Pluck_ chords change throughout the music. This is done thanks to automations, who are automating of a parameters of an effect applied in _Progressive Pluck_  instrument.
Alright. You have to create two automations :

-> First will be applied in a _Glame Highpass Filter_ effect. Start with add this effect, then automate it.

-> Second will be applied in FREQ parameter, inside the _Progressive Pluck_ instrument, and will increase throughout the second part of the music, in the same time of second drums pattern.

_Hephel's tip : automations are very powerful ! They allow you to make many amazing effects._

## Step 7 - To go further....

Ok, listen the given music and yours. Do they sound the same ? If no, you probably forgot some steps... If yes, congratulations ! You are now familiar with many basics in music composition.
To go further, you can now add others instruments : a lead, to create a melody, a bass, etc...

Or just create your own music, from a to z !