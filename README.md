# ios-decal-final-proj

163
===

Authors
-------
* Julie Chen
* Bryan Tran

Purpose
-------
To entertain, challenge, and stimulate players. The purpose of the game is, given 6 random cards from a deck, to get 163 by using only the addition, subtraction, multiplication, and division operators on the numbers each card represents. 


Features
--------
* Ability to play the game in various modes
* Ability to view high scores from previous plays
* Ability to adjust volume of background sound

Control Flow
------------
* Splash screen with title and 3 buttons: Play, High Scores, Options
* Clicking "Play" takes you to screen with 2 modes of play: Practice and Challenge
* Practice mode lets you play as long as you want
* Challenge mode gives you a 2 minute timer that counts down. Every set you finish adds 10 seconds to your time. Try to finish as many sets as possible before time runs out. The top scores are recorded in the High Scores page.
* Any difficulting setting takes you to game, each adjusted for difficulty
* High Scores displays list of top 10 global highest scores and date achieved as well as personal high score
* Options takes you to page where you can adjust music and SFX

Implementation
--------------
### Model
* CardClass
* CardSlotClass
* DeckClass

### View
* SplashScreenTableView
* DifficultySelectTableView
* PracticeGameView
* ChallengeGameView
* HighScoreTableView
* OptionsView

### Controller
* SplashScreenTableViewController
* DifficultySelectTableViewController
* PracticeGameViewController
* ChallengeGameViewController
* HighScoreTableViewController
* OptionsViewController
 
