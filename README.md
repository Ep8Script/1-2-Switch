# 1-2-Switch
*1-2-Switch* recreation project using Microsoft Small Basic.

# Requirements
* PC or laptop
* Bluetooth receiver
* Two Wii Remotes
* GlovePIE
  * Minor understanding of GlovePIE

# Minigames
* Soda Shake
  * Unplayable/WIP
* Quick Draw
  * Completed (minor bugs)
* Fake Draw
  * Almost playable/WIP

# Changelog
* v1.0
  * Added Quick Draw
  * Created GlovePIE script
* v1.1
  * Created *1-2-Switch* title screen and menu
  * Player must move Wiimote to shoot in Quick Draw
  * Added misfire screen in Quick Draw to prevent B from being held down <!-- Thanks for the beta testing, dad -->
  * Added Soda Shake, unplayable
  * Minor bug fixes
* [v1.2](https://www.reddit.com/r/nintendo/comments/64aq9o/12switch_partially_recreated_in_small_basic/)
  * Added Fake Draw
  * Hid mouse in game window
  * Forced both players to press B before playing minigame
    * Added "OK" text
  * Added Wiimote vibration when shooting in certain minigames using GlovePIE
  * Changed "Misfire" to "Quick trigger" in Quick Draw
  * Added lower.mp3
  * Added early.mp3
  * Bug fixes
* v1.3
  * Removed vibration effects from GlovePIE
  * Detected specific mouse movement in GlovePIE script
  * Now frequently change mouse position in SB script, triggering vibration in Wiimotes at important moments in GlovePIE
  * Added animations for smoother experience
    * Win/Lose screen more closely represents actual game
    * Disqualified screen animation added
    * "Fire" appears more vibrant
    * Various other places
  * Changed some images
  * Added version number in title
  * Changes to Fake Draw randomiser
    * Less likely to repeat the same words
    * Shorter time between random words
    * Word read aloud before image shows up
  * Added "Quick Draw" voice when selected
