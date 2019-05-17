# Project 3 Generative Audio

Ryan Bez, rbez@ucsd.edu


## Abstract

After stumbling upon oscilloscope music, audio that when played on an oscilloscope displays imagery, during a late night YouTube rabbit hole I've been fascinated with it. Simple constant frequencies can be used to display basic geometry, but the possibilities are endless and there are some amazing audiovisual projects that exist out there and are included in my references below. I was curious, however, if given the simple frequencies whether or not using the NSynth tool from class if it would be able recreate them and display the original image, or interpolate between two images and produce what looked like a shifting image from one shape to another. I was both successful and unsuccessful in achieving my goals. It was unsuccessful because the generated audio does not clearly recreate and represent the source image. It was also a success because working on this project allowed me creative freedom to dig into oscilloscope music, which is something I have been wanting to do for a while, and because I think the generated interpolation starts off looking more like a bunch of squares and then transitions into a bunch of triangles, but perhaps I have been staring at this too long.

## Code

- P3 NSynth Makes Oscilloscope Music.ipynb: This is used to interpolate between two tones used to create simple objects to display on an oscilloscope.

## Model/Data

- This project used the premade checkpoints included in NSynth example notebook used in class.

## Results
- `Oscilloscope.exe`: Available under an open source license, this is used to display my audio files as images in lieu of an analog oscilloscope
- `30crossfade.wav`: When played on the oscilloscope this displays the interpolation between the square and pyramid shapes. Does it look like squares transforming into pyramids to you?
- `P3FinalComp.wav`: When played on an oscilloscope it shows the video for my project with an intro, the display of the cube, the interpolated audio, and finally the pyramid. This was edited together using Ableton Live 10 and unfortunately due to the way they export audio any definition of the interpolation was lost and displays only as a diagonal line. The interpolation must be played separately to view as something other than the diagonal line.
- `simplecube.wav`: A short 4 second sample that displays a square when played on an oscilloscope.
- `gen_simplecube.wav`: An NSynth generated recreation of a 4 sec sample that originally generated a square when played on an oscilloscope. unfortunately the recreation has lost all definition.
- `pyramid.wav`: A longer 30 second sample that when played on an oscilloscope displays a flat pyramid. This was used as a sample to interpolate between.
- `shuttle.wav`: A longer 30 second sample that when played on an oscilloscope displays a flat space shuttle. This was used as a sample to interpolate between.
- `square.wav`: A longer 30 second sample that when played on an oscilloscope displays a square. This was used as a sample to interpolate between.

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- This project requires an analog oscilloscope or the included Oscilloscope.exe program to display the full breadth of the project. Otherwise, it just sounds like a lot of awful nonsense noise. Refer to https://oscilloscopemusic.com/tech.php for an in depth look at setting up on an analog oscilloscope. Simply hit the folder button and load the .wav from the project directory to play on the Oscilloscope.exe
- I used Ableton Live 10 in addition to the "text" Max for Live patch to generate the audio that makes up the "Welcome to ECE 188 Project 3 :)" intro. Ableton was also used to edit together the various audio files used in the project. Ableton is not required to replicate this project, and most modern audio production software could be used in place of it if you wanted to make or edit your own oscilloscope music projects.
- OsciStudio is available for ~$40 and was used to generate the simple shapes used to interpolate between. The software is very complex and with more time and knowledge of how to use it could be used to generate more complex things such as Jerobeam Fenderson's "Oscilloscope Music" series which is linked in the references below.
- There are a few third party software alternatives listed on the oscilloscope music website that could also be used in place of OsciStudio, but are not as feature dense.

## Reference

- Jerobeam Fenderson, and his oscilloscope music album on youtube
- https://www.youtube.com/watch?v=4dUmfV1DW_8&list=PLFgoUhNvMLrr8izq38HX6rjFR-nkfklxw
- https://www.youtube.com/watch?v=rtR63-ecUNo
- Oscilloscopemusic.com and the assorted softwares available there, primarily Oscilloscope, OsciStudio, and the test Max for Live patch
- https://oscilloscopemusic.com/index.php


