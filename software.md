# Software

A list of softwares used in our workshop + recommendations and tips on other software relevant for digital art.

## Video playback

### [Avenue](https://resolume.com/download) *// Resolume*
*paid software, MacOS/Windows, video playback, video effects, audio playback* <br>

Arena stripped of features like layer groups and mapping. A capable entry-level VJing software.

---

### [Arena](https://resolume.com/download) *// Resolume*
*paid software, MacOS/Windows, video playback, video effects, audio playback*

The gold standard for VJing, due to it's active development, crossplatform status and large community.

>**DKVJ Weapon of Choice** for VJing. In the workshop we currently use [Resolume Arena version 7.22.9](https://resolume.com/download/file?file=Resolume_Arena_7_22_9_rev_47596_No_Footage_Installer.exe)

---

### [Lumen](https://lumen-app.com) // Paracosm
*paid software, video synthesizer, MacOS*

An impressive emulator of analog visual synthesis, with cables and a fixed aspect ratio of 4:3. A much cheaper alternative to buying modular video synthesizers.

---

### [MadMapper](https://madmapper.com) *// GarageCube*
*paid software, MacOS/Windows, projection mapping, video playback, audio playback, shader playback, DMX*

The gold standard in projection mapping software.

>**DKVJ Weapon of Choice** for projection mapping and installations

---

### [Modul8](https://modul8.com) *// GarageCube*
*paid software, MacOS, video playback*

VJing software by the team behind MadMapper. Not that commonly used.

---

### [Synesthesia](https://synesthesia.live/#download) // Gravity Current

*paid software, video synthesizer, MacOS/Windows*

Instrument for making generative visuals with inputs from video sources. 
A capable and fun instrument, but for its price you can get more advanced tools.

---

### [TouchViz](https://hexler.net/touchviz) *// Hexler Heavy Industries*
*paid software, iPad*

VJing software for the iPad. NDI output, or direct output using the right dongles.

---

### [VDMX](https://vidvox.net) *// VidVox*

*paid software, MacOS, video playback, video effects, shader playback*

VJing software with a modular interface. Not that commonly used.

---

### [VLC](https://videolan.org) // VideoLAN
*open source, Linux/MacOS/Windows, video playback, audio playback*

The gold standard in simple video playback. Plays almost every type of video. Cross-platform, will run on a potato.

>**DKVJ Weapon of Choice** for video playback on installations.

---

## Video editing

### [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) *// BlackmagicDesign*
*free software, MacOS/Windows, video editing, capture* <br>

Resolve is BlackmagicDesigns colorgrading software turned full linear editing suite. They offer a free tier with restricted features. Most notably, their plug-and-play effects are not available in the free version, but most basic post-processing effects can be made using their node-based compositing tool Fusion.

**Resolve version 17+ requires a minimum of 16GB RAM to work, because of enshittification.** Older versions are available [at their support site](https://www.blackmagicdesign.com/support/). KDEnLive is a good alternative.

>**DKVJ Weapon of Choice** for video editing.

---

### [KDEnlive](https://kdenlive.org) *// KDE*
*open source software, MacOS/Linux/Windows, video editing* <br>

Full video editing suite, more advanced and stable than other open source competitors.

---

## Plugins

### [Stoatworks Labs](https://stoatworks-labs.com/software/) // Stoatworks
*FFGL, MacOS, Windows*

Free plugins, especially FFGL effects and generators, for Resolume.
Install: Download and unpack the zip archive for your platform. Put the file (.dll or .bundle) in ```/Documents/Resolume Arena/Extra Effects``` and reopen Arena.

**Recommendations:**
[Luma Keyer](https://stoatworks-labs.com/software/resolume-luma-keyer/)<br>



---

## Video utilities


### [Alley](https://resolume.com/download) *// Resolume*
*free software, MacOS/Windows, video conversion, codecs* <br>

Video converter mainly used for converting to Resolumes own codec DXV.

**Alley is bundled with Resolume Arena or Avenue**

---

### [BlackSyphon](https://docs.vidvox.net/blacksyphon/) *// Vidvox*
*free software, MacOS, capture*

Utility for routing signals from BlackmagicDesign hardware through the Syphon protocol.

---

### [Desktop Video Setup](https://www.blackmagicdesign.com/support/) *// BlackmagicDesign*
*free software, MacOS/Windows, video capture*

Utility for configuring BlackmagicDesigns own capture card hardware.

---

### [FFmpeg](https://ffmpeg.org) *// the FFmpeg team*

*Open source software, MacOS/Linux/Windows, command line interface*

FFmpeg is a project aimed at making video conversion and editing free for all. It is a very capable tool, but as it is based around the command line it will scare of some people.

For using FFmpeg with a more user-friendly interface, look to Shutter Encoder.

---

### [Logitech G Hub](https://www.logitechg.com/en-us/software/ghub) *// Logitech*

*free software, MacOS/Windows, capture*

Utility for settings for the Logitech Stream cam. Sometimes necessary for control over focus/exposure.

---

### [NDI Tools](https://ndi.video/tools/)

*free software, NDI, signal testing* <br>

Tools for NDI video sources. Can be used to test which NDI signals are present on the network or to share your computer or webcam through NDI.

---


### [Shutter Encoder](https://shutterencoder.com) *by Paul Pacifico*
*Open source software, MacOS/Linux/Windows, video conversion, video download* <br>

Tool for converting video, downloading video from various online sources, simple editing. Based on FFmpeg, but with a friendly user interface.

>**DKVJ Weapon of Choice** for conversions.

---

## Frame-by-frame animation

### [BOATS Animator](https://help.boatsanimator.com/en/stable/)

*open source software, stop motion animation, video capture*

Simple and easy cross-platform software for capturing a webcam feed into a frame-by-frame animation. A bit simpler than Eagle Animation, but still capable.

---

### [Eagle Animation](https://brickfilms.com/eagle-animation) *by BrickFilms*

*open source software, stop motion animation, capture*

Simple and easy cross-platform software for capturing a webcam feed into a frame-by-frame animation. Has features like onion skinning and simple controls for exposure and cropping.

>**DKVJ Weapon of Choice** for stop motion animation
---

## Node-based programming


### [Max/MSP](https://cycling74.com/downloads) *// Cycling74*
*paid software, MacOS/Windoes, node-based programming*

Programming environment meant for audio, visuals available through external libraries like Jitter.
PureData is an open-source alternative.

---

### [VVVV](https://vvvv.org) *// vvvv Group*
*paid software, Windows, node-based programming*

VVVV (or 4V) is a node-based programming environment, like TouchDesigner.

---

### [PureData](https://puredata.info) *// Miller Puckette*
*open-source software, MacOS/Linux/Windows, node-based programming*

Programming environment meant for audio, visuals available through [external libraries]((https://github.com/MikeMorenoDSP/awesome-puredata)).

---

### [TouchDesigner](https://derivative.ca) *// Derivative*
*paid software, programming*

Node-based programming environment. Works in the free version, restricted to 1 CPU core and max resolution of 1280x1280.

>**DKVJ Weapon of Choice** for node-based programming of visuals.

---

### Wire *// by Resolume*
*paid software, MacOS/Windows*

Wire is the engine behind Arena/Avenues effects and generative sources. It is a full node-based programming environment that can run stand-alone or make and edit effects and generators for use in Arena/Avenue.

---

## Text-based Programming

### [KodeLife](https://hexler.net/kodelife) // Hexler Heavy Industries
*shaders, iOS/Linux/MacOS/Windows*

Editor for GLSL shaders, doubling as a realtime performance tool (if you know how to livecode shaders, that is).

---

## [Processing IDE](https://processing.org) // Processing Foundation
*free software, MacOS/Linux/Windows*

Programming framework based on Java. Easy to learn, active development. Support for Syphon/Spout, MIDI and OSC through libraries.

> **DKVJ Weapon of choice** for text-based programming of applications running locally.

---

## [p5.js](https://processing.org) *// Processing Foundation*
*free software, web*

Programming framework based on Java. Easy to learn, active development. Editor runs directly in the browser.

> **DKVJ Weapon of choice** for text-based programming for web and running visuals in the browser.

---

## [Hydra](https://hydra.ojack.xyz) *// Olivia Jack*
*free software, web, livecoding*

Text-based video synth in the browser.

---

## 3D

### [SketchUp Make 2017](https://archive.org/details/sketchup-make-2017) *// Last/Google/Trimble*

*3D modelling*

SketchUp is a 3D modelling tool made for simple and easy use for makers. The software allows for quickly sketching and measuring rooms and stage elements.

SketchUp was made by a software company called Last in 1999, then purchased by Google in 2006, then sold of to Trimble in 2012. Trimble then continued the software as a web-based app. The last functioning offline version is SketchUp Make 2017. While the core functions work, it can no longer access the popular built-in online model database.

---

## Various

### [Chataigne](https://github.com/benkuper/Chataigne)
*open source software, MacOS/Windows/Linux, show control*

Made for controlling other software, Chataigne can be used as a central command center for processing MIDI, OSC, audio, DMX, SMPTE and a long list of other protocols. It can be used to synchronize two or more pieces of software (even between computers on a network), working as the "conductor" of an interactive installation or a show.

---

### [Protokol](https://hexler.net/protokol) *// Hexler Heavy Industries*

*free software, Linux/MacOS/Windows, signal testing*

App for testing for incoming MIDI, OSC, various game controllers.

---

### [TouchOSC](https://hexler.net/touchosc) *// Hexler Heavy Industries*
*paid software, Linux/MacOS/iPad/Android/SteamOS/Windows*

Customizable touch interface for controlling other software through OSC.

---

### [K-Lite Codec Pack](https://www.codecguide.com/download_kl.htm)

*codecs, Windows*

If you're on Windows, install this codec pack in order play a wide variety of codecs natively.

**Install the Basic pack for codecs only.**

---