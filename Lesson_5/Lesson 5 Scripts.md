screen 1:

 Ui elements:

1) add vertical alignment and fill parent in both width and height. Align horizontal and vertical to centre.

2) add 1 label for score text , 1 label for game name and 1 label for score. set default value to 0 

3) Increase font size of all the labels.

Code: 

1) Add tinyDb and set namespace and remember it!!!!!!

2) add when screen initialize.

3) Set Score text and call GetValue, add tag a tag for high score.

-- make the play button work

1) when button click and get logic open screen name and add the screen name for the game.

done with main menu screen

Screen 3 : game over screen

ui elements:

1) add tiny Db name it the same as first screen.

2) add vertical alignment and add another button for main menu align it to centre like the first screen.

code:

1) when button 2 clicked go to screen 1 or main menu.

2) add if and add logic which compares more than equal to values. math operator "greater than".(logical comparision)

3) first value is get start value and compare it to the highscore value in database by getting the "highScore" value from Db.

4) then .StoreValue HighScore as get start value.

Procedures:

Screen 2: the game

code:

1) we are setting the global variable to 0 and setting hte labelScore text to 0 twice. so use procedures.

2) Grab toProcedure call it SetScore.

3) use inputs in the settings icon and call that input score.

4) grab set Global variable and labelScore text and set it to get score in procedure.

5) call set score and replace it wherever there are both set global score and labelscore.(in 2 places Colidded with and button reset)