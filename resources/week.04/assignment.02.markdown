---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# Assignment #2: 10 points
## Connecting _bach_ to _RTcmix~_ 

* Instantiate at least 2 of your own `RTcmix~` objects running separate RTcmix scripts:
	* You'll be using `RTcmix~` in place of `poly~` as a synthesis engine for this assignment.
	* Consider tweaking any of the RTcmix instruments or scripts we've demonstrated in class.
	* Your script should employ the use of at least one `maketable` or `makegen` function. These can be used to modulate a note's amplitude envelope, FM depth, filter cutoff frequency, or any other synthesis parameter of your choosing.
* Write another short musical sequence stored in a `bach.roll`, different from Assignment #1:
	* Your sequence should have only 1 voice. (This has been changed, since we didn't cover multiple RTcmix~ objects.)
	* Consider how your chosen sound and sketch of material might be used in our final project about memory.
	* _Some excerpts may be chosen for inclusion in, or for development towards, our final project._
* Write a text file that translates your bach sequence into RTcmix code:
	* Each note of your `bach.roll` must be written as a separate line of code with its own function call to an RTcmix instrument, parsing the correct pitch, onset, duration, and/or velocity data received from bach.
	* Use our last patches from the PDF "First Steps in RTcmix" to see how this works. This is the poly~ that writes a text file...
	* Use Max's `sprintf` and `text` objects to create and increment each line of your text file, as demonstrated in class.
* Your composition should include one or more of the _RTcmix_ treatments we discussed;
	* Either those covered in class in our demo patches, or
	* Any treatment or combination/chain thereof you can imagine, using bus_config() to combine them.

### LENGTH
Between 1 and 2 minutes of material maximum.

### DOCUMENTATION
* Record a soundfile of your score playing back from your `RTcmix~` objects using the Quickrecord patch, and export a text file (.txt) from your `bach.roll` to preserve your score.  
* Include your main patch, bach score in text format, RTcmix score in text format, and short audio recording in a folder and make it into a .zip file.
* Audio recordings should be lossless .WAV or .AIFF files in 48kHz/24-bit (i.e. sampling rate / bit rate).
* Email me the .zip file _(or send me a link to it if the archive is too large)._

### DEADLINE
* <p class="redish">Due on Tuesday night, March 10th, at 11:59 PM.</p>
* As you will be presenting your work the following day (Wednesday 3/11), **no late work will be accepted.**
* We moved the deadline to Wednesday to make sure you can use the Open Lab hours earlier in the week. 

### GRADING
Subject to the **GENERAL GRADING RUBRIC** located in our <a href="/index.html">Course Syllabus.</a>  
_Scores will be given out of 10 points. Your grade will be based on:_
* Elegance, simplicity, and readability of technical solutions in your Max patching; esp. communication between `bach.roll` and `RTcmix~`.
* Inventiveness of the sound-producing engine inside your `RTcmix~` subpatcher.
* Quality of the sound produced by your `RTcmix~` and as captured in your sound file.
* Creativity and thoughtfulness of your musical ideas as recorded in your `bach.roll` MIDI composition.

### FEEDBACK
We will listen to and discuss your work as a group next Wednesday 3/11.

* * *