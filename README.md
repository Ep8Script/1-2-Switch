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
* Quick Draw
* Fake Draw
* Telephone
  
# Changelog
* v1.0 (*Initial release*)
  * Added Quick Draw
  * Created GlovePIE script
* v1.1
  * Created *1-2-Switch* title screen and menu
  * Player must now move the Wii Remote to shoot in Quick Draw
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
  * Version number now appears in title
  * Changes to Fake Draw randomiser
    * Less likely to repeat the same words
    * Shorter time between random words
    * Word read aloud before image shows up
  * Added "Quick Draw" voice when selected
  * Fixed bug in Quick Draw where the timer would begin too late
* v1.4
  * Soda Shake is now fully playable
    * Vibration and animations still to be added
  * Files for Telephone minigame added
* v1.4.1
  * Some animations added to Soda Shake <!-- Regarded, unfortunately, as "good enough", otherwise speed would slow down significantly -->
  * Vibrations when soda bursts
  * Telephone minigame added to menu
* v1.5
  * Added Telephone
  * Minor bug fixes
* v1.5.1
  * Gave slightly higher priority to "Fire" in Fake Draw
  * Removed debugging related messages in the Text Window
* [v1.5.2](https://www.reddit.com/r/nintendo/comments/65pbmm/12switch_microsoft_small_basic_v152/)
  * Window can no longer be resized
* v1.5.3
  * Scrolling through games is now faster
  * Added a few more touch controls
* v2.0
  * Added title screens on load
  * Main *1-2-Switch* title screen is now animated
  * Fixed bug where first game would open immediately from title screen
  * Updated images for Telephone and Soda Shake
  * Swapped positions of Telephone and Soda Shake on menu
  * Replaced "Press the Home Button" with "Play Again" and "+ Game select"
  * Added more words to Fake Draw
  * Randomised time between words in Fake Draw
  * Quick Draw and Fake Draw now detect whether or not you lower your gun
  * Added game tips
  * Removed many bugs
  * Further improvements to overall stability and other minor adjustments have been made to enhance the user experience
