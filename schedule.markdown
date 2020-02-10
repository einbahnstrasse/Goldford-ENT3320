---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Schedule
_This page will be updated each week with example patches, links to new resources, and occasional ASSIGNMENTS._   
_Check back frequently!_

* * *

### Week 1: January 27th & 29th
#### Orientations, Introduction to the _bach_ Library, and Review of poly~
##### Start-of-Semester Business
* [Personal Info Form DUE NOW!](https://forms.gle/ZCrtqVX8SvHbbXPD6)
* [Intro. Survey Due by end of Week #1!](https://forms.gle/ojTR48sR8exrum5V9)
* Review [Syllabus + course policies.](index.html)
* Review [Detailed Breakdown of Grading.](grading.html)

##### Ice-Breaker + Discussion
* [Godzilla, Kubrick, and Ligeti: How Do We Hear this Music?](/Goldford-ENT3320/resources/week.01/ligeti.html)

##### Voice Allocation in Max Using the _bach_ Library
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.01/Goldford.Voice.Allocation.with.poly.pdf)
* <a href="/Goldford-ENT3320/resources/week.01/tutorial.01a.bach.poly~.zip" download>Download the Starter Patches Here</a>
* review of a basic & dirty monophonic synthesizer
* a Max poly~ template
* the bach.roll editor
* making bach.roll speak to poly~

* * *

### Week 2: February 3rd & 5th
#### Continuation of Work with `poly~`

##### Ice-Breaker + Discussion
* _What sorts of sounds do you remember?_
* _What sorts of sights do you remember?_
* Brainstorm — e.g. create a wordcloud, Venn diagram, etc.! 

### [Assignment #1: Due Tuesday 2/18!](/Goldford-ENT3320/resources/week.02/assignment.01.html)
* Finish building patches from Week 1.  
* Work on assignment and finish projects for next week!

##### Reading: Assigned for Monday 2/10
[Ritchey, Marianna. "Intel Beethoven: The New Spirit of Classical Music." In _Composing Capital: Classical Music in the Neoliberal Era_, 114-139. Chicago: The University of Chicago Press, 2019.](/Goldford-ENT3320/resources/week.03/Ritchey.Chs.4.pdf)

* * *

### Week 3: February 10th Only 
#### Introduction to _RTcmix~_ + Connecting _RTcmix~_ to _bach_
<p class="redish">No Class Wednesday; <i>City Tech is closed for Lincoln's Birthday.</i></p>

##### Drivers for Oxygen 8 USB/MIDI Keyboards
* [Thanks for these, Alberto!](https://m-audio.com/support/download/drivers/midi-usb-driver-v3.5.3-mac)

##### Ice-Breaker + Discussion
* Group discussion of the Ritchey chapter assigned on 2/10
* [Intel Beethoven _Experience Amazing_ Ad #1](https://youtu.be/JOkpg_MC6Vc)
* [Intel Beethoven _Experience Amazing_ Ad #2](https://youtu.be/JU9LoDd_5bo)

##### Assignment #1 Prep
* Finish bach slots patches in PDF
* Review Assignment #1 page one last time...
* [New Computer Keyboard MIDI patches, when a real MIDI keyboard is unavailable](/Goldford-ENT3320/resources/week.03/lg.computer.midi.keyboard.zip)

##### Introduction to _RTcmix_
* Overview of [RTcmix.org](http://rtcmix.org/)
* [Scorefile commands + functions](http://rtcmix.org/reference/scorefile/) vs. [RTcmix instruments](http://rtcmix.org/reference/instruments/)
* the RTcmix~ Max external
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.03/Goldford.First.steps.in.RTcmix.pdf)
* <a href="/Goldford-ENT3320/resources/week.03/tutorial.02a.basic.rtcmix.zip" download>Download the Starter Patches Here</a>

##### Some Basic Patches + RTcmix Scripts
* the [STRUM](http://rtcmix.org/reference/instruments/STRUM.php) and [WAVETABLE](http://rtcmix.org/reference/instruments/WAVETABLE.php) instruments
* Using a `for loop` to generate a sequence of notes

* * *

### Week 4: February 19th Only
#### Intermediate _RTcmix~_
<p class="redish">No Class Monday; <i>City Tech is closed for Presidents' Day.</i></p>

##### Ice-Breaker + Discussion
* Listening + Review of [Assignment #1](/Goldford-ENT3320/resources/week.02/assignment.01.html) Patches (on Wed 2/19)

### [Assignment #2: Due Sunday 3/1!](/Goldford-ENT3320/resources/week.04/assignment.02.html)

##### MIDI Sequence —> RTcmix~
* Continue patching the examples in our PDF from last week...
* `bach.roll` as a MIDI sequencer / DAW / Event Manager
* `RTcmix~` for Synthesis + Voice Allocation: in place of poly~ 

* * *

### Week 5: February 24th & 26th 

##### Assignment #2 Prep
* Finish bach-to-RTcmix connections, then onto Treatments PDF (below...)
* Review Assignment #2 page one last time.

##### Sound File Treatments with `RTcmix~` (C3)
* [Download a library of audio samples for testing](https://drive.google.com/file/d/1PQGkOrSoLyr3BhetR9fqzwEQ-ya11g5J/view?usp=sharing)
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.04/Goldford.Sound.Treatments.pdf)
* Introduction to the [STEREO](http://rtcmix.org/reference/instruments/STEREO.php) and [MIX](http://rtcmix.org/reference/instruments/MIX.php) Instruments
* the [TRANS](http://rtcmix.org/reference/instruments/TRANS.php) Pitch-Transposition Instrument
* the [MOOGVCF](http://rtcmix.org/reference/instruments/MOOGVCF.php) 24dB/octave Resonant Lowpass Filter
* the [GVERB](http://rtcmix.org/reference/instruments/GVERB.php) Gigaverb-type and [FREEVERB](http://rtcmix.org/reference/instruments/FREEVERB.php) Schroeder/Moorer Reverb Models
* the [PVOC](http://rtcmix.org/reference/instruments/PVOC.php) Phase Vocoder
* [AM](http://rtcmix.org/reference/instruments/AM.php), i.e. apply amplitude or ring modulation to an input source

* * *

### Week 6: March 2nd & 4th 
#### Sampling and Physical Modeling Synthesis Using _Modalys~_ 

##### Ice-Breaker + Discussion
* Listening + Review of [Assignment #2](/Goldford-ENT3320/resources/week.04/assignment.02.html) Patches (on Monday 3/2)

### [Short Assignment #3: Due Sunday 3/8!](/Goldford-ENT3320/resources/week.05/assignment.03.html)

##### Introduction to _Modalys~_
* `modalys~` for physical modeling synthesis in Max/MSP
* _ModaLisp_ for creating + naming batch samples

##### A Logic Sampler Made from _Modalys~_
* [Keymap our samples in Logic's EXS24 Sampler](https://www.youtube.com/watch?v=GZ58AQXYZOI)
* Compose a sequence in Logic's [MIDI piano roll editor](https://www.youtube.com/watch?v=Jf-SrVhcxiU)

* * *

### Week 7: March 9th & 11th 
#### The _Unity_ Environment + Algorithmic Composition

### [Midterm Assignment #4: Due Sunday 3/22!](/Goldford-ENT3320/resources/week.08/assignment.04.html)

##### Introduction to Sound in _Unity_
* Overview of basic tools for scene creation
* Overview of basic tools for sound manipulation
* Create a basic scene, add a user perspective asset, an Audio File asset, add an 'invisible wall.'
* When the user crosses a threshold, i.e. where the wall has been drawn, trigger the soundfile playback. 

##### Simple Algorithmic Composition (C4)
* Basic algorithmically-generated musical sequences
	* Scale generation
	* Loops
	* Random notes from a reservoir (array of notes)
	* automated FX — e.g. moving filters
	* real-time control over FX

##### Connecting Your _RTcmix_ Scores to _Unity_ : Introduction to uRTcmix
* [uRTcmix Video Tutorials](http://sites.music.columbia.edu/brad/uRTcmix/video-tutorials.html)
	* [Basic Installation, Setup and Use of uRTcmix](https://youtu.be/V7HoD03Fmas)
	* [Repeating/Re-Triggering Scores with MAXBANG()](https://youtu.be/he7rEYICnAg)
	* [Reading RTcmix Scores into Unity](https://youtu.be/8yfFbqZX-Og)
	* [Reading Soundfiles](https://youtu.be/8HldSxQZzxA)
* Scoralizer for <a href="/Goldford-ENT3320/resources/week.09/scoralyzer.zip" download>MAC</a> or <a href="/Goldford-ENT3320/resources/week.09/scoralyzer-windows.zip" download>Windows</a>

* * *

### Week 8: March 16th & 18th 
#### Chaos, Motion, and Density

##### Advanced Algorithmic Composition (C4+)
* More intricate algorithmically-generated musical sequences
	* Simple Quadratic Note Generation
	* Arpeggiator with real-time timbre control
	* Chaotic Attractors
		* Henon Map
		* Lorenz — 2D flow of fluid, uniform depth
		* Logistic Map (a.k.a. Population Growth) 
* Introduction to the noise types + colors:
	* [NOISE, i.e. white noise](http://rtcmix.org/reference/instruments/NOISE.php) 
	* [PINK](http://rtcmix.org/reference/instruments/PINK.php)
	* [BROWN](http://rtcmix.org/reference/instruments/BROWN.php)
	* [CRACKLE, i.e. chaotic](http://rtcmix.org/reference/instruments/CRACKLE.php)
	* [DUST, i.e. random impulses](http://rtcmix.org/reference/instruments/DUST.php)
	* [LATOOCARFIAN](http://rtcmix.org/reference/instruments/LATOOCARFIAN.php)
	* [HENON](http://rtcmix.org/reference/instruments/HENON.php)
	* [IINOISE, i.e. IIR filtered noise](http://rtcmix.org/reference/instruments/IIR.php#IINOISE)
	
##### Using Max and `RTcmix~` to prototype generative music processes for _Unity_ 
* real-time control over density parameters 
* modeling real-world motion and noise

##### Advanced Synthesis Tools in _RTcmix_
* Physical Modeling (i.e. in _RTcmix_)	
	* [MBLOWBOTL, i.e. simple Helmholtz resonator](http://rtcmix.org/reference/instruments/MBLOWBOTL.php)
	* [MBLOWHOLE, i.e. waveguide clarinet](http://rtcmix.org/reference/instruments/MBLOWHOLE.php)
	* [STRUM, i.e. Karplus-Strong ("plucked string") + distortion + feedback](http://rtcmix.org/reference/instruments/STRUM.php)
	* [MBANDEDWG, i.e. bars/modal things, struck & bowed](http://rtcmix.org/reference/instruments/MBANDEDWG.php)
	* [MMODALBAR, i.e. modal-bar physical model](http://rtcmix.org/reference/instruments/MMODALBAR.php)
	* [MSITAR, i.e. sitar model](http://rtcmix.org/reference/instruments/MSITAR.php)
* Granular synthesis:
	* [GRANSYNTH](http://rtcmix.org/reference/instruments/GRANSYNTH.php)
	* [JGRAN, i.e. FM or wavetable granular synthesis](http://rtcmix.org/reference/instruments/JGRAN.php)
	* [SGRANR, i.e. stochastic granular synthesis](http://rtcmix.org/reference/instruments/SGRANR.php)
	* [STGRANR, i.e. decomposing an input soundfile or real-time sound source](http://rtcmix.org/reference/instruments/STGRANR.php)
* Modulation Synthesis:
	* [AMINST, i.e. amplitude modulation](http://rtcmix.org/reference/instruments/AMINST.php)
	* [FMINST, i.e. frequency modulation](http://rtcmix.org/reference/instruments/FMINST.php)	
	* [MULTIFM, i.e. multi-oscillator FM synthesis instrument](http://rtcmix.org/reference/instruments/MULTIFM.php)
	* [WAVESHAPE, i.e. waveshape distortion synthesis](http://rtcmix.org/reference/instruments/WAVESHAPE.php)
* Additive + Subtractive Frequency-Based Synthesis:
	* [MULTIWAVE, i.e. additive synthesis](http://rtcmix.org/reference/instruments/MULTIWAVE.php)
	* [FILTERBANK, i.e. multi-band resonator](http://rtcmix.org/reference/instruments/FILTERBANK.php)

* * *

### Week 9: March 23rd & 25th 
#### 3D Audio Spatialization
<p class="redish">Midterm grades will be available by 3/26.</p>

##### Spatialization in _spat~_
* [spat~ for Max/MSP: download is NOW FREE!](https://forum.ircam.fr/projects/detail/spat/)
* simple binaural spatialization of a single sound source in Max/MSP

##### Spatialization in _RTcmix~_
* [LOCALIZE](http://rtcmix.org/reference/instruments/LOCALIZE.php), i.e. distance-based amplitude panning (DBAP)
* Quick demo of how to do DBAP spatialization inside of _Unity._

##### Ice-Breaker + Discussion (3/25)
* Feedback on Midterm projects _(time permitting...)_
* Brainstorming, Revisited...
* Further consider as a group how these advanced audio tools might be used in conjugation with our theme of "memory," towards our final project. 

* * *

### Week 10: March 30th & April 1st 
#### Storyboarding + Project #5 Prep
<p class="redish">Prof. Goldford will be absent on April 1st; a substitute professor will be present.</p>

##### Ice-Breaker + Discussion
* Develop a _storyboard_ for any number of elements + short scenes that our collective project might include.
	* [Video Tutorial: How to draw A-grade storyboards (even if you can't draw!)](https://youtu.be/NPrkxj2MyZI)
	* [Video Tutorial: Create wireframes and mockups in draw.io](https://youtu.be/UDZsjP4a7Tw)
	* _Other Ideas for Storyboarding Apps or Utilities?_
* Decide on a "divison of labor" among team members: 
	* Who will compose? 
	* Develop sounds? 
	* Develop characters? 
	* Lanscapes? 
	* Shoot/edit video content?

### [Assignment #5: Due Sunday 4/19!](/Goldford-ENT3320/resources/week.10/assignment.05.html)
* Create a simple Unity 'scene' using our recently-acquired synthesis and spatialization tools.
* As a "test" of the basic setup for our final project.
* Note: These will be SHORT sketches in which EACH STUDENT writes a short scene in Unity and attaches their own sounds to it. 
* Students may begin to collaborate and consult one another, but this project is still individual. We will work on teams towards our final project.

* * *

### Week 11: April 6th Only
#### _Unity_ Particle Systems, Chroma Keying, and Video Assets

##### Ice-Breaker + Discussion
* Listening + Review of [Midterm Assignment #4](/Goldford-ENT3320/resources/week.08/assignment.04.html) (on Monday 3/23)

##### Particle Systems in _Unity_
* [Unity Tutorials: Particle Systems](https://www.raywenderlich.com/138-introduction-to-unity-particle-systems)
* [Unity Documentation: Particle Systems](https://docs.unity3d.com/Manual/class-ParticleSystem.html)
* [Unity Scripting API: Particle Systems](https://docs.unity3d.com/ScriptReference/ParticleSystem.html)

##### Chroma Keying + Video Assets
* A Walkthrough: Simple Video Shoot —> Keying —> Semi-Transparent Video in _Unity_ 
* [_Unity_ Chroma Key Shader: $8](https://assetstore.unity.com/packages/tools/chroma-key-shader-60917)
* [Video Tutorial: AR Video with alpha channel: Premiere CC 2017, Unity3D 2017.3, Vuforia 7](https://youtu.be/4W5e6-TSpW0)
* [Vuforia Blog on Alpha/transparent video](https://developer.vuforia.com/forum/unity/alphatransparent-video)

#### AR in _Unity_ (Time Permitting) + Teamwork Towards Final Project... 
<p class="redish">Spring break Wednesday 4/8 — Thursday 4/16. (<i>Skip next week!</i>)</p>

##### Creating Augmented Reality in _Unity_
* [Creating AR Content With Vuforia](https://learn.unity.com/tutorial/recorded-video-session-creating-ar-content-with-vuforia#) 
* [Getting Started with Vuforia Engine in Unity](https://library.vuforia.com/articles/Training/getting-started-with-vuforia-in-unity.html#digital-assets)
* [Building an AR app for mobile](https://learn.unity.com/tutorial/building-for-mobile#)

* * *

### Week 12: April 20th & 22nd 
#### Teamwork Towards Final Project... 

* * *

### Week 13: April 27th & 29th 
#### Teamwork Towards Final Project... 

* * *

### Week 14: May 4th & 6th
#### Teamwork Towards Final Project... 

* * *

### Week 15: May 11th & 13th
#### Teamwork Towards Final Project... 
* Talkback and Evaluation After Launch?

* * *