
Add the clearing condition

put the DrawLine inside else block of an If else and handle if the value was an Empty list , you'll clear the canvas , else we'll still draw

[CoderDojo > Lesson 10 - Sketch N Guess ( Cont'd ) > image2020-2-5_15-24-47.png]

From the Game Screen

Add A game screen. backpressed to clear Tag ( with the student name tag he used elsewhere ) , that will clear the tag data completely

now try again and clear the data it should clear from the students phones

======= demo ==========

add screen, call it "Player List"

in Player List screen----
1) Add list view (fill parents)

2) add button, "join" button. This button needs to be disabled 

3) add firebase to the screen and set the project url to the same we have been using and Project bucket as sketch.

--- in the blocks

1) grab initialize event from the screen and call firebase.GetTaglist

2) When firebase.TagList, set listview Elements to value from tag list.

3) When Listview.Afterpicking, set join button to true.

4) when button clicked and put open another screen with value, screen is "watch" and start value is the selected item.( list view) 

--- Watch screen
1) initialize global variable, initialize it to the get start value.
2) use the global variable instead of the hard coded key.

-- Screen 1

1) change the watchButton value from watch screen to "playerList" screen.


-- DEMOOOO

-- After Demo


Add the capability to join whichever key (player) you want to watch Sketching

Will Turn the student name to a variable passed from the first screen :

Screen1:
1) add notifier to the screen.

Screen 1 blocks: 

1) Add if and else block to play button , if text is empty then call notifier show alert and add text in notice "Name field cant be empty"

2) else open another screen, "Game" and send value Textbox text.

Go to game blocks
1) Create global value, add start value. use get global name replace it with hardcoded one.

-- Playerlist Screen

Add Refresh Button
In blocks , refresh button. click , call firebase . get tag list


==== END DEMO =====