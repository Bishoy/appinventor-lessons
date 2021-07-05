

-- Scoring system

1) Rename labelscore to labelText and the other one as labelScore.

2) create global variable, call it "score" and set it to 0

3) Set Global score in collided event as current global score + 1.

4) Set LabelScore- text to the value of global variable (score) -- Reset Game

5) Set Global variable to 0 and Set LabelScore - text to 0 

-- Game Over screen 

6) add new Screen.

7) Add label to screen and name it "final score text" as a text.   

8) Add another label for the actual score and name it "final score", fill parent with height and width.

9) Add button and name it " Restart". 

10) go back to screen 1 and go to blocks.

11) add an if condition in EdgeReached event comparing Edge to -1, if true set ball enabled to false.

12) add new control "Open another screen with start value", pass the name of screen (screen 2) and start value as global score variable. 

-- configuring Game Over Screen

13) Go back screen 2 and its blocks

14) When screen 2 initialized, set the labelScore - text to "get start value" from control.

15) When button click then use "Open another Screen" and pass in "Screen1".
Like
Be the first to like this