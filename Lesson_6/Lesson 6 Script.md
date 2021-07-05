-- Ui elements
1)  Make the screen size responsive, drag vertical arrangement and make it fill parent in height and width.
2) Drag a canvas and make height 70%, width as fill parent.

3) Add horizontal arrangement at the bottom and then add 2 labels one for the score text and one for the actual score.

4) Name the labels score and the other 0 as a default value. Rename the label with text as txtScoreLabel and the one with value as txtScoreValue.

5) Change background colour to green.

6) Drag image sprite and also upload the assets, both mole.png and the hole.png.

7) rename the first sprite as hole1 and go in sprite's properties and choose hole.png in picture. Repeat the process for other 5 holes.

8)  Add the clock sensor and sound from media (for vibration). Call the sound module as buzzer and call the clock as Clock.


-- Code Blocks

-- Basic setup

1) We will initialise the score global variable to 0. We will create a holeList and will use "make a list" from lists menu.

2) Drag all the available holes in the hole list.

3) Initialise global variable CurrentMileSprite and set it to hole1.

3) Now we need to show the mole in different holes so we will use the clock.Use the clock timer event and Set global currentMoleSprite to random item from the list.To do that use use "pick random item from the list " from Lists. 

4) Then in the clock Set Image Sprite enabled of component "get global currentMoleSprite" to a text "mole.png".

-- Ask them to run and it will fill all the holes in 3 seconds.

-- Reset the mole image

5) add in the clock, Set Image sprite of component "Current Mole" to "hole.png "(to Reset).

-- run it again

-- Successfully hitting the mole and infringement the score