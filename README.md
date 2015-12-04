# Lissajous-Offline
An offline application implementation of <a href="https://github.com/kylestetz/lissajous">Lissajous</a>, a project by <a href="https://github.com/kylestetz/">Kyle Stetz</a> for browser-based live-coding.
<br> Lissajous-Offline was built using the <a href="https://github.com/atom/electron">Electronjs framework</a>. If you'd like to build from source use the <a href="https://github.com/maxogden/electron-packager">Electron Packager</a>.
<br>For more information on Lissajous <a href="https://github.com/kylestetz/lissajous/blob/master/README.md">click here</a>.
<h4><br> <a href="https://drive.google.com/file/d/0B2-2tiw_8BS_TEgxTWFmcXl5SE0/view?usp=sharing">Download Lissajous-Offline </a></h4><h6>(OSX/Linux)</h6>
<br>
<h4>Quick Start</h4>
-Launch the application and go to the console tab<br>
-Drag a .wav file into the main window<br>
-You should see a message similar to `The AudioBuffer 'THENAMEOFYOURSAMPLE' is ready for you to use.`<br>
-In the console, enter `a = new track(), a.sample(THENAMEOFYOURSAMPLE)` <br>
-You should see a message similar to:<br> 
`track {_destination: ChannelSplitterNode, _leftChannel: GainNode, _rightChannel: GainNode, _final: ChannelMergerNode, _schedulers: Array[2]...}`<br>
-In the console, enter `a.beat(4).nl(3).speed(0.5).vol(1)`<br>
-Your sample will now play every 4th 1/16th note, for a duration of three 1/16th notes, at half the speed, with the volume set to 1<br>
-You can adjust these values in realtime, try running `a.beat(3).speed(0.75)`
<br><br>
For more indepth information on using Lissajous, <a href="https://github.com/paullucas/lissajous-offline/blob/master/Tutorial.md">visit the tutorial</a>.
