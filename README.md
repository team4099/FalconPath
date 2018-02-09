# FalconPath
A version of Team 254's [Cheesy Path](https://github.com/Team254/FRC-2017-Public/tree/master/cheesy_path) with a few key modifications.

## What's new
* The field diagram and dimensions have been updated for 2018, as well as the size of the robot displayed
* Kotlin has been added as an option for the generated path code
  * The Kotlin code is designed for use with Team 4099's [Power Up repository](https://github.com/team4099/PowerUp-2018), whereas the Java code meshes with Team 254's [Steamworks code](https://github.com/Team254/FRC-2017-Public)
* There is now caching for the waypoints so that if you accidentally refresh or close the page your path isn't destroyed
  * Accordingly there's also a reset button now
* Waypoints can now be manipulated through drag-and-drop
