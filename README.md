<img src="https://github.com/AmruthPillai/Reversify/raw/master/app/src/main/res/drawable-nodpi/reversify_icon_logo.png" width="256px" />  
<img src="https://github.com/AmruthPillai/Reversify/raw/master/app/src/main/res/drawable-nodpi/reversify_text_logo.png" width="512px" />

--

### Introduction
*Reversify* is my answer to the plethora of ad-riddled apps out there that were supposed to do one simple thing, and that's reverse a video. I got interested in this type of video the second I saw it, it felt magical to be transported back in time, backwards.  

Things looked more beautiful backwards... writing on paper, water dropping from a distance, birds flying, and even eating (dare you not try that!). Watching video in backwards is a magical art by itself, and I want to simplify it, and thus, '*Reversify*' was invented.

--

### Version
0.8 beta

--

### Bugs / Feature Requests
I'm still learning the building blocks of Android and wanted to take this app up as a playground to innovate and learn. This app isn't perfect, I know it very well, but I'd love to make it perfect with your help!  
Raise a issue on this repository if you find a bug, and let me know... I'll tackle it ASAP (or at least try to!)  

  - Works only for SD Quality Videos (due to phone computation limitations)  
  - Doesn't show a finite progress bar, replaced with infitineSpinner for now  
  - Doesn't load videos with (spaces) in their path  
  - Processing a video takes a lot of time, so find a way to make it run in background  

Some of these are easily implementable, but I just don't know how... so if you would like to help me out, please do send me a private message on GitHub and we'll talk :)

--

### Installation
Just head over to the [Releases](https://github.com/AmruthPillai/Reversify/releases) tab and grab the latest APK. Once the app takes better form, I'll be sure to put it up on the Google Play Store.

**Permissions Required:**
  - Read & Write External Storage
    - Allows the application to grab video files and store them on your SD Card or Internal Storage.

--

### Open Source Projects
  - [FFmpeg-Android-Java](https://github.com/WritingMinds/ffmpeg-android-java)
    - the library that makes all the magic happen, the video library that is capable of reversing the video seamlessly.
  - [MillSpinners](https://github.com/DevLight-Mobile-Agency/MillSpinners)
    - used to load the fancy spinner animation while processing a video.
