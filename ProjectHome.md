## Welcome ##

<a href='http://code.google.com/p/pandoroid/downloads/detail?name=pandoroid.apk'><img src='https://www.google.com/chart?chs=150x150&cht=qr&chl=//pandoroid.googlecode.com/files/pandoroid.apk&chld=L|1&choe=UTF-8&nonsence=download-pandoroid.png' align='right' /></a> An open-source application for Android-based devices to interface with the Pandora Radio service. Due to failings in the proprietary application provided by Pandora Radio themselves, this application is being designed with three focuses in mind: _stability_, _intuitiveness_, and _configurability_ (in that order).  At this stage, those are more "goals" then an actual reality.

This project also includes a Java library that aims to be totally detached from Android so that any other Java project can interface with Pandora Radio.

## Current Status ##

This project started not that long ago but has been moving along quite rapidly, thanks to the work of other open source Pandora Radio clients and the capabilities of the Android API.

As it stands right now, this is what I at least claim that the app can do with at least a reasonable level of success:
  * Connect to your pandora.com account
  * Retrieve a list of your stations
  * Play tracks from a chosen station
  * Continue to play in the background until stopped
  * Submit ratings (ban/love) for a song that is playing
  * Status bar notification while playing
  * Pause on command and when a call happens
  * Pre-fetch the next playlist segment before it is needed
  * Switch stations
  * Log out
  * Respond appropriately to all settings currently presented to the user:
    * Pandora.com account information
    * Audio format
    * Skip to next track when "thumb-down" a song `[`Y/n`]`
    * Automatically resume playback when a call ends `[`Y/n`]`

This list is just the parts of functionality that I have intentionally implemented. Some of the things on that list work better then others.  As more functionality is added, it will be added to this list.  Items that are unique to this application and not the standard Pandora application will be highlighted.

This application is at an "alpha" release level of stability. In my own brief testing, things seem to mostly work as intended.  Much more testing is still needed by my own extended use, and others using it on their own devices with their own habits and preferences.  Once a version of the code is deemed stable enough and basically feature-complete, this project will fork to maintaining a stable version (on the Android Market) and a development version (here).

## Credits ##

Unless otherwise noted in comments, all Java source code and XML resources were written by me or other members of this project.  However, there are several parts that were simply ported to the Android/Java platform based on other open source projects that also interact with Pandora Radio:

  * [Pithos](http://kevinmehall.net/p/pithos/)
  * [Pianobar](http://6xq.net/html/00/17.html) ([github](https://github.com/PromyLOPh/pianobar/))

Without the work done by these two fine projects, none of my work would of been possible.

## Disclaimer ##

I am not affiliated with nor authorized by Pandora Media(tm).  This is not a challenge to their copyrights or trademarks in any way.