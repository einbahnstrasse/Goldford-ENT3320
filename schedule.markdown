---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<!-- source: https://youtu.be/MOlaldp1Fv4 -->
<div class="splash">
	<div class="fade-in">
		<h1>Our SCHEDULE page is under site maintenance!</h1>  
		<!-- <h5><em>This page is currently under revision to accurately reflect our updated syllabus for Spring 2022.</em></h5>   -->
		<!-- <h6>For now, please refer to the <a href="https://einbahnstrasse.github.io/Goldford-ENT3320/index.html#sched">General Schedule of Topics</a> and please check back here for updates soon!</h6>   -->
	</div>
</div>

<script>
	const splash = document.querySelector('.splash');
	document.addEventListener('DOMContentLoaded', (e)=>{
		setTimeout(()=>{
			splash.classList.add('display-none');
		}, 6000);
	})
</script>

# Schedule
_This page will be updated frequently with example patches, links to new resources, video tutorials, and occasionally new or altered ASSIGNMENTS. Our schedule follows the [CityTech Spring 2022 Schedule](https://www.citytech.cuny.edu/registrar/docs/spring_2022.pdf){:target="_blank"}. The following topics and their precise order may change. Check here for updates!_   
**Skip to:** <a href="#w1">Week 1</a> <a href="#w2">Week 2</a> <a href="#w3">Week 3</a> <a href="#w4">Week 4</a> <a href="#w5">Week 5</a> <a href="#w6">Week 6</a> <a href="#w7">Week 7</a> <a href="#w8">Week 8</a> <a href="#w9">Week 9</a> <a href="#w10">Week 10</a> <a href="#w11">Week 11</a> <a href="#w12">Week 12</a> <a href="#w13">Week 13</a> <a href="#w14">Week 14</a> <a href="#w15">Week 15</a>  

* * *

<a id="w1"></a>
### Week 1: February 1st
#### Orientations, Introduction to the _bach_ Library, and Review of poly~
##### Start-of-Semester Business
* [Personal Info Form DUE NOW!](https://forms.gle/ZCrtqVX8SvHbbXPD6){:target="_blank"}  
* [Intro. Survey Due by end of Week #1!](https://forms.gle/ojTR48sR8exrum5V9){:target="_blank"}  
* Review [Syllabus + course policies.](index.html){:target="_blank"}  
* Review [Detailed Breakdown of Grading.](grading.html){:target="_blank"}  

##### Ice-Breaker + Discussion
* [Godzilla, Kubrick, and Ligeti: How Do We Hear this Music?](/Goldford-ENT3320/resources/week.01/ligeti.html){:target="_blank"}  

##### Voice Allocation in Max Using the _bach_ Library
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.01/Goldford.Voice.Allocation.with.poly.pdf){:target="_blank"}  
* <a href="/Goldford-ENT3320/resources/week.01/tutorial.01a.bach.poly~.zip" download>Download the Starter Patches Here</a>
* review of a basic & dirty monophonic synthesizer
* a Max poly~ template
* the bach.roll editor
* making bach.roll speak to poly~

* * *

<a id="w2"></a>
### Week 2: February 15th
#### Continuation of Work with `poly~`
<p class="redish"><i>Week 2 has skipped 1 week! 2/8 is on Friday schedule, so we resume Week 2 on 2/15. See <a href="https://www.citytech.cuny.edu/registrar/docs/spring_2022.pdf" target="_blank">CityTech Spring 2022 Schedule.</a></i></p>

##### Ice-Breaker + Discussion
* _What sorts of sounds do you remember?_
* _What sorts of sights do you remember?_
* Brainstorm — e.g. create a wordcloud, Venn diagram, etc.! 

### [Assignment #1: Due Tuesday 2/18!](/Goldford-ENT3320/resources/week.02/assignment.01.html){:target="_blank"}  
* Finish building patches from Week 1.  
* Work on assignment and finish projects for next week!

##### Reading: Assigned for Monday 2/10
[Ritchey, Marianna. "Intel Beethoven: The New Spirit of Classical Music." In _Composing Capital: Classical Music in the Neoliberal Era_, 114-139. Chicago: The University of Chicago Press, 2019.](/Goldford-ENT3320/resources/week.03/Ritchey.Chs.4.pdf){:target="_blank"}  

* * *

<a id="w3"></a>
### Week 3: February 22nd 
#### Introduction to _RTcmix~_ + Connecting _RTcmix~_ to _bach_
<!-- <p class="redish">No Class Wednesday; <i>City Tech is closed for Lincoln's Birthday.</i></p> -->

##### Drivers for Oxygen 8 USB/MIDI Keyboards
* [Thanks for these, Alberto!](https://m-audio.com/support/download/drivers/midi-usb-driver-v3.5.3-mac){:target="_blank"}  

##### Ice-Breaker + Discussion
* Group discussion of the Ritchey chapter assigned on 2/10
* [Intel Beethoven _Experience Amazing_ Ad #1](https://youtu.be/JOkpg_MC6Vc){:target="_blank"}  
* [Intel Beethoven _Experience Amazing_ Ad #2](https://youtu.be/JU9LoDd_5bo){:target="_blank"}  

##### Assignment #1 Prep
* Finish bach slots patches in PDF
* Review Assignment #1 page one last time...
* [New Computer Keyboard MIDI patches, when a real MIDI keyboard is unavailable](/Goldford-ENT3320/resources/week.03/lg.computer.midi.keyboard.zip){:target="_blank"}  

##### Introduction to _RTcmix_
* Overview of [RTcmix.org](http://rtcmix.org/){:target="_blank"}  
* [Scorefile commands + functions](http://rtcmix.org/reference/scorefile/){:target="_blank"} vs. [RTcmix instruments](http://rtcmix.org/reference/instruments/){:target="_blank"}  
* the RTcmix~ Max external
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.03/Goldford.First.steps.in.RTcmix.pdf){:target="_blank"}  
* <a href="/Goldford-ENT3320/resources/week.03/tutorial.02a.basic.rtcmix.zip" download>Download the Starter Patches Here</a>

##### Some Basic Patches + RTcmix Scripts
* the [STRUM](http://rtcmix.org/reference/instruments/STRUM.php){:target="_blank"} and [WAVETABLE](http://rtcmix.org/reference/instruments/WAVETABLE.php){:target="_blank"} instruments
* Using a `for loop` to generate a sequence of notes  

* * *

<a id="w4"></a>
### Week 4: March 1st
#### Intermediate _RTcmix~_
<!-- <p class="redish">No Class Monday; <i>City Tech is closed for Presidents' Day.</i></p> -->

##### Ice-Breaker + Discussion
* Listening + Review of [Assignment #1](/Goldford-ENT3320/resources/week.02/assignment.01.html){:target="_blank"} Patches (on Wed 2/19)

### [Assignment #2: Due Sunday 3/9!](/Goldford-ENT3320/resources/week.04/assignment.02.html){:target="_blank"}  

##### RTcmix~ Topics
* Control RTcmix~ scripts with a bang from within your Max patch
* Using MAXBANG()
* Creating variables in RTcmix~ scripts, and linking them to Max variables
* Using the maketable() function to control amplitude envelopes

* * *

<a id="w5"></a>
### Week 5: March 8th 

##### Assignment #2 Prep
* Finish bach-to-RTcmix connections, then onto Treatments PDF
* Review Assignment #2 page.

##### MIDI Sequence —> RTcmix~
* Addititve synthesis using parallel WAVETABLE() calls
* Continue patching the examples in our PDF from last week...
* `bach.roll` as a MIDI sequencer / DAW / Event Manager
* `RTcmix~` for Synthesis + Voice Allocation: in place of poly~ 

* * *

<a id="w6"></a>
### Week 6: March 15th 
#### Sound Treatments

##### Assignment #2 Prep
* Returning to small teams (pairs) for exchange of creative ideas and sharing of labor.
* We will practice this collaboration by building the patches below mostly on small teams.

##### What is a "Treatment" Anyway?!
* [PDF of Patches as Screenshots](/Goldford-ENT3320/resources/week.04/Goldford.Sound.Treatments.pdf){:target="_blank"}  
* See PDF pg. 3 for an explanation...

##### Use of Audio Samples in Our Projects
* [Download a library of audio samples for testing](https://drive.google.com/file/d/1PQGkOrSoLyr3BhetR9fqzwEQ-ya11g5J/view?usp=sharing){:target="_blank"}  
* Where to find free sounds:
	* [freesound.org](http://www.freesound.org/){:target="_blank"}  
	* [The Internet Archive](https://archive.org/){:target="_blank"}  
	* [The National Parks Service](https://www.nps.gov/index.htm){:target="_blank"}  
	* [NASA Celestial Sounds](https://www.nasa.gov/connect/sounds/index.html){:target="_blank"}  
	* Others? As long as you are [licensed](https://creativecommons.org/use-remix/){:target="_blank"} to download, distribute, adapt, arrange, remix, or otherwise appropriate. 
* Importance of properly **attributing credit** to your sources (i.e. when a license is required!)
* Best to record your _own sounds_ using your phone or any microphone/recording device you may have access to

##### Sound File Treatments with `RTcmix~` (C3)
* Break out into small groups and create some of the patches featured in our PDF.
* Introduction to the [STEREO](http://rtcmix.org/reference/instruments/STEREO.php){:target="_blank"} and [MIX](http://rtcmix.org/reference/instruments/MIX.php){:target="_blank"} Instruments
* the [TRANS](http://rtcmix.org/reference/instruments/TRANS.php){:target="_blank"} Pitch-Transposition Instrument
* the [MOOGVCF](http://rtcmix.org/reference/instruments/MOOGVCF.php){:target="_blank"} 24dB/octave Resonant Lowpass Filter
* the [GVERB](http://rtcmix.org/reference/instruments/GVERB.php){:target="_blank"} Gigaverb-type and [FREEVERB](http://rtcmix.org/reference/instruments/FREEVERB.php){:target="_blank"} Schroeder/Moorer Reverb Models
* the [PVOC](http://rtcmix.org/reference/instruments/PVOC.php){:target="_blank"} Phase Vocoder
* [AM](http://rtcmix.org/reference/instruments/AM.php){:target="_blank"}, i.e. apply amplitude or ring modulation to an input source

##### Wednesday (3/4): Ice-Breaker
* Recap on the direction of the final project
* Where do you see these new sounds and techniques being useful in the context of our theme: creating a virtual memory space?
* Are you getting a sense from our patches, demonstratons and your own creations about which sounds will be most useful for creating such a virtual environment? 
* What sorts of visual imagery do these sounds suggest? 
* What sorts of sounds would you _like to create_ in service of our final project?

* * *

<a id="w7"></a>
### Week 7: March 21st 
#### The _Unity_ Environment  
<p class="redish"><i>Midterm grades reported via email by 3/24. See <a href="https://www.citytech.cuny.edu/registrar/docs/spring_2022.pdf" target="_blank">CityTech Spring 2022 Schedule.</a></i></p>  

##### Ice-Breaker + Discussion
* Listening + Review of [Assignment #2](/Goldford-ENT3320/resources/week.04/assignment.02.html){:target="_blank"} Patches (on Monday 3/9)

### [Midterm Assignment #4: Due Sunday 3/22!](/Goldford-ENT3320/resources/week.08/assignment.04.html){:target="_blank"}  

##### Introduction to Sound in _Unity_
* Overview of basic tools for scene creation
* Overview of basic tools for sound manipulation
* Create a basic scene, add a user perspective asset, an Audio File asset, add an 'invisible wall.'
* When the user crosses a threshold, i.e. where the wall has been drawn, trigger the soundfile playback. 

##### Connecting Your _RTcmix_ Scores to _Unity_ : Introduction to uRTcmix
* [uRTcmix Video Tutorials](http://sites.music.columbia.edu/brad/uRTcmix/video-tutorials.html){:target="_blank"}  
	* [Basic Installation, Setup and Use of uRTcmix](https://youtu.be/V7HoD03Fmas){:target="_blank"}  
	* [Repeating/Re-Triggering Scores with MAXBANG()](https://youtu.be/he7rEYICnAg){:target="_blank"}  
	* [Reading RTcmix Scores into Unity](https://youtu.be/8yfFbqZX-Og){:target="_blank"}  
	* [Reading Soundfiles](https://youtu.be/8HldSxQZzxA){:target="_blank"}  
* Scoralizer for <a href="/Goldford-ENT3320/resources/week.09/scoralyzer.zip" download>MAC</a> or <a href="/Goldford-ENT3320/resources/week.09/scoralyzer-windows.zip" download>Windows</a>

* * *

<a id="w8"></a>
### Week 8: March 29th 
#### Algorithms: Chaos, Motion, and Density

##### Simple Algorithmic Composition (C4)
* Basic algorithmically-generated musical sequences
	* Scale generation
	* Loops
	* Random notes from a reservoir (array of notes)
	* automated FX — e.g. moving filters
	* real-time control over FX

##### Advanced Algorithmic Composition (C4+)
* More intricate algorithmically-generated musical sequences
	* Simple Quadratic Note Generation
	* Arpeggiator with real-time timbre control
	* Chaotic Attractors
		* Henon Map
		* Lorenz — 2D flow of fluid, uniform depth
		* Logistic Map (a.k.a. Population Growth) 
* Introduction to the noise types + colors:
	* [NOISE, i.e. white noise](http://rtcmix.org/reference/instruments/NOISE.php){:target="_blank"}   
	* [PINK](http://rtcmix.org/reference/instruments/PINK.php){:target="_blank"}  
	* [BROWN](http://rtcmix.org/reference/instruments/BROWN.php){:target="_blank"}  
	* [CRACKLE, i.e. chaotic](http://rtcmix.org/reference/instruments/CRACKLE.php){:target="_blank"}  
	* [DUST, i.e. random impulses](http://rtcmix.org/reference/instruments/DUST.php){:target="_blank"}  
	* [LATOOCARFIAN](http://rtcmix.org/reference/instruments/LATOOCARFIAN.php){:target="_blank"}  
	* [HENON](http://rtcmix.org/reference/instruments/HENON.php){:target="_blank"}  
	* [IINOISE, i.e. IIR filtered noise](http://rtcmix.org/reference/instruments/IIR.php#IINOISE){:target="_blank"}  
	
##### Using Max and `RTcmix~` to prototype generative music processes for _Unity_ 
* real-time control over density parameters 
* modeling real-world motion and noise

##### Advanced Synthesis Tools in _RTcmix_
* Physical Modeling (i.e. in _RTcmix_)	
	* [MBLOWBOTL, i.e. simple Helmholtz resonator](http://rtcmix.org/reference/instruments/MBLOWBOTL.php){:target="_blank"}  
	* [MBLOWHOLE, i.e. waveguide clarinet](http://rtcmix.org/reference/instruments/MBLOWHOLE.php){:target="_blank"}  
	* [STRUM, i.e. Karplus-Strong ("plucked string") + distortion + feedback](http://rtcmix.org/reference/instruments/STRUM.php){:target="_blank"}  
	* [MBANDEDWG, i.e. bars/modal things, struck & bowed](http://rtcmix.org/reference/instruments/MBANDEDWG.php){:target="_blank"}  
	* [MMODALBAR, i.e. modal-bar physical model](http://rtcmix.org/reference/instruments/MMODALBAR.php){:target="_blank"}  
	* [MSITAR, i.e. sitar model](http://rtcmix.org/reference/instruments/MSITAR.php){:target="_blank"}  
* Granular synthesis:
	* [GRANSYNTH](http://rtcmix.org/reference/instruments/GRANSYNTH.php){:target="_blank"}  
	* [JGRAN, i.e. FM or wavetable granular synthesis](http://rtcmix.org/reference/instruments/JGRAN.php){:target="_blank"}  
	* [SGRANR, i.e. stochastic granular synthesis](http://rtcmix.org/reference/instruments/SGRANR.php){:target="_blank"}  
	* [STGRANR, i.e. decomposing an input soundfile or real-time sound source](http://rtcmix.org/reference/instruments/STGRANR.php){:target="_blank"}  
* Modulation Synthesis:
	* [AMINST, i.e. amplitude modulation](http://rtcmix.org/reference/instruments/AMINST.php){:target="_blank"}  
	* [FMINST, i.e. frequency modulation](http://rtcmix.org/reference/instruments/FMINST.php){:target="_blank"}  
	* [MULTIFM, i.e. multi-oscillator FM synthesis instrument](http://rtcmix.org/reference/instruments/MULTIFM.php){:target="_blank"}  
	* [WAVESHAPE, i.e. waveshape distortion synthesis](http://rtcmix.org/reference/instruments/WAVESHAPE.php){:target="_blank"}  
* Additive + Subtractive Frequency-Based Synthesis:
	* [MULTIWAVE, i.e. additive synthesis](http://rtcmix.org/reference/instruments/MULTIWAVE.php){:target="_blank"}  
	* [FILTERBANK, i.e. multi-band resonator](http://rtcmix.org/reference/instruments/FILTERBANK.php){:target="_blank"}  

* * *

<a id="w9"></a>
### Week 9: April 5th 
#### 3D Audio Spatialization
<!-- <p class="redish">Midterm grades will be available by 3/26.</p> -->

##### Spatialization in _spat~_
* [spat~ for Max/MSP: download is NOW FREE!](https://forum.ircam.fr/projects/detail/spat/){:target="_blank"}  
* simple binaural spatialization of a single sound source in Max/MSP

##### Spatialization in _RTcmix~_
* [LOCALIZE](http://rtcmix.org/reference/instruments/LOCALIZE.php){:target="_blank"}, i.e. distance-based amplitude panning (DBAP)
* Quick demo of how to do DBAP spatialization inside of _Unity._

##### Ice-Breaker + Discussion (3/25)
* Feedback on Midterm projects _(time permitting...)_
* Brainstorming, Revisited...
* Further consider as a group how these advanced audio tools might be used in conjugation with our theme of "memory," towards our final project. 

* * *

<a id="w10"></a>
### Week 10: April 12th 
#### Storyboarding + Project #5 Prep
<!-- <p class="redish">Prof. Goldford will be absent on April 1st; a substitute professor will be present.</p> -->
<p class="redish"><i>Spring Recess 4/15-4/22. After today's class, we resume on 4/25. See <a href="https://www.citytech.cuny.edu/registrar/docs/spring_2022.pdf" target="_blank">CityTech Spring 2022 Schedule.</a></i></p>

##### Ice-Breaker + Discussion
* Develop a _storyboard_ for any number of elements + short scenes that our collective project might include.
	* [Video Tutorial: How to draw A-grade storyboards (even if you can't draw!)](https://youtu.be/NPrkxj2MyZI){:target="_blank"}  
	* [Video Tutorial: Create wireframes and mockups in draw.io](https://youtu.be/UDZsjP4a7Tw){:target="_blank"}  
	* _Other Ideas for Storyboarding Apps or Utilities?_
* Decide on a "divison of labor" among team members: 
	* Who will compose? 
	* Develop sounds? 
	* Develop characters? 
	* Lanscapes? 
	* Shoot/edit video content?

### [Assignment #5: Due Sunday 4/19!](/Goldford-ENT3320/resources/week.10/assignment.05.html){:target="_blank"}  
* Create a simple Unity 'scene' using our recently-acquired synthesis and spatialization tools.
* As a "test" of the basic setup for our final project.
* Note: These will be SHORT sketches in which EACH STUDENT writes a short scene in Unity and attaches their own sounds to it. 
* Students may begin to collaborate and consult one another, but this project is still individual. We will work on teams towards our final project.

* * *

<a id="w11"></a>
### Week 11: April 25th
#### _Unity_ Particle Systems, Chroma Keying, and Video Assets

##### Ice-Breaker + Discussion
* Listening + Review of [Midterm Assignment #4](/Goldford-ENT3320/resources/week.08/assignment.04.html){:target="_blank" (on Monday 3/23)

##### Particle Systems in _Unity_
* [Unity Tutorials: Particle Systems](https://www.raywenderlich.com/138-introduction-to-unity-particle-systems){:target="_blank"}  
* [Unity Documentation: Particle Systems](https://docs.unity3d.com/Manual/class-ParticleSystem.html){:target="_blank"}  
* [Unity Scripting API: Particle Systems](https://docs.unity3d.com/ScriptReference/ParticleSystem.html){:target="_blank"}  

##### Chroma Keying + Video Assets
* A Walkthrough: Simple Video Shoot —> Keying —> Semi-Transparent Video in _Unity_ 
* [_Unity_ Chroma Key Shader: $8](https://assetstore.unity.com/packages/tools/chroma-key-shader-60917){:target="_blank"}  
* [Video Tutorial: AR Video with alpha channel: Premiere CC 2017, Unity3D 2017.3, Vuforia 7](https://youtu.be/4W5e6-TSpW0){:target="_blank"}  
* [Vuforia Blog on Alpha/transparent video](https://developer.vuforia.com/forum/unity/alphatransparent-video){:target="_blank"}  

#### AR in _Unity_ (Time Permitting) + Teamwork Towards Final Project... 
<!-- <p class="redish">Spring break Wednesday 4/8 — Thursday 4/16. (<i>Skip next week!</i>)</p> -->

##### Creating Augmented Reality in _Unity_
* [Creating AR Content With Vuforia](https://learn.unity.com/tutorial/recorded-video-session-creating-ar-content-with-vuforia#){:target="_blank"}  
* [Getting Started with Vuforia Engine in Unity](https://library.vuforia.com/articles/Training/getting-started-with-vuforia-in-unity.html#digital-assets){:target="_blank"}  
* [Building an AR app for mobile](https://learn.unity.com/tutorial/building-for-mobile#){:target="_blank"}  

* * *

<a id="w12"></a>
### Week 12: May 3rd 
#### Teamwork Towards Final Project... 

* * *  

<a id="w13"></a>
### Week 13: May 10th 
#### Teamwork Towards Final Project... 

* * *

<a id="w14"></a>
### Week 14: May 17th
#### Teamwork Towards Final Project... 

* * *

<a id="w15"></a>
### Week 15: May 24th
#### Teamwork Towards Final Project... 
* Talkback and Evaluation After Launch  

* * *