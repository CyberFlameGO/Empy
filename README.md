# Empy

Empy is a plugin for a wide range of lossy distortion sounds, drawing inspiration from lossy audio compression codecs like MP3. Empy can sound bubbly and metallic. It can resemble a bitcrusher. It can freeze sound at spots, like a choppy phone connection. An any setting, Empy gives sound distinctive lossy distortion.

I made Empy as a part of my undergraduate thesis at the University of Oregon.

[See Empy in action](https://youtu.be/RhrXB1W7zAI)!

[Read the manual](https://github.com/ArdenButterfield/Empy/blob/main/User%20Manual.md).

## Build instructions

Building Empy requires the JUCE library. Open `Empy.jucer` in Projucer. If Necessary, update the path to JUCE in Projucer. If building in XCode, click the "Save and Open in IDE" button; otherwise, create a new build target for the build system you are using. In the IDE, run the build scheme.

Now, if you check the user plugin directory (`~/Library/Audio/Plug-Ins` on Mac), you should see both Empy.vst3 and Empy.component. Now, when you launch your DAW, Empy should show up in the list of plug-ins, under the manufacturer name Arden Butterfield.
