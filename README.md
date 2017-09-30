# 1-2-Switch
 *1-2-Switch* recreation project using Microsoft Small Basic.

# Requirements
* PC or laptop
* Bluetooth receiver
* Two Wii Remotes
* GlovePIE
  * Minor understanding of GlovePIE

# Minigames
* Telephone
* Quick Draw
* Fake Draw
* Soda Shake
* Samurai Training
  * Few issues
  
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
  * Menu now returns to selected game from title screen
  * Replaced "Press the Home Button" with "Play Again" and "Game Select"
  * Added more words to Fake Draw
  * Randomised time between words in Fake Draw
  * Quick Draw and Fake Draw now detect whether or not you lower your gun
  * Added game tips
  * Removed many bugs
  * Further improvements to overall stability and other minor adjustments have been made to enhance the user experience
* [v2.1](https://www.reddit.com/r/nintendo/comments/6dlnvh/12switch_simulator_v21/)
  * Added Samurai Training
  * Forced window size to 1280x720 due to graphics sizes and to avoid issues on other PCs
* [v2.2](https://gbatemp.net/threads/release-1-2-switch-simulator.485016/)
  * Minor changes
  
## Download
https://gbatemp.net/threads/release-1-2-switch-simulator.485016/

## What next?
I'm currently working on adding pitch detection for Quick Draw and Fake Draw (meaning it detects where the Wiimote is pointing, to enable DQ for "Shot the dirt"), and making Samurai Training more accurate. Additionally of course, I'm researching more games to add to the simulator!

For future releases, an auto updater will be available. Otherwise, the new files on their own will be there to download, as likely will a full archive of the software.
  
## About this project
I began this project at the beginning of April 2017 with the idea in mind to create the minigame "Quick Draw" for Wii Homebrew, playable with Wii Remotes. However, I later realised this would be easier to do on PC. I chose Small Basic as my programming choice due to it's simplicity and my knowledge of the language. (However, it's probably the worst program to do such a thing in.) 

After creating a buggy and innaccurate version of Quick Draw, I set out to remake the main menu of *1-2-Switch* in my game, and also added the two games "Soda Shake" &ndash; which was unplayable for a time as I set out to properly figure out ways to achieve it &ndash; and "Fake Draw" (of course, copying some code from Quick Draw).

After completing those two, along with creating a functional Soda Shake game, I set out to more accurately represent these games, working hard to add animations in Small Basic, a tedious task, and making the menus and sounds more alive. After this great achievement, I added Telephone, whilst still continuing to update all four games more accurately, more fun, and with less glitches.

Finally, I added "Samurai Training" after thinking of games that are possible in Small Basic due to its graphics limitations (still holding out to add Milk soon!), and with limited on-screen events and logic required.

While some updates to fix bugs and improvements to make the games more accurate are required, this is where the game is at currently, and as far as it goes I'm quite happy with the process I've made on my project! As a 16 year old without a Switch or the game, it's great!

Thanks for visiting! For any and all enquiries, please email me at Ep8Script@gmail.com! :D
