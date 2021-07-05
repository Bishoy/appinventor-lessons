We'll be teaching this lesson on Three stages :

1- Create a regular Drawing Game

2- Add The storage + storage monitoring capabilities to the Game

3- Add the capability to join whichever key (player) you want to watch Sketching
Create a regular Drawing Game

1- Add a Vertical Alignment , make it fill width and height , align horizontal and vertical to center

2- Add Button btnPlay ( make it oval for a change ) , label ( your Name ) , textbox , label (or) , and a button  ( Watch )

3- Go to the blocks

     When btnPlay is Clicked Go to Screen "Game"
    When Watch is clicked go to screen Watch

4- Create a new Screen Game , add a vertical arrangement make fill, Also create a Screen Watch and leave it empty

5- Add a Canvas make fill , then add horizontal Arrangements with two buttons , one for Back , other for Clear

6- In the blocks of Game Screen

1- Whenc BtnBacl Click , Close Screen

2- When BtnClear Click Call Canvas Clear

3- When Canvas Dragged call Canvas Drawline → prevX prevY currentX CurrentY


Complete
Add The storage + storage monitoring capabilities to the Game

Explain a bit firebase which is like a Folders on the computer and show them from firebase

1- In the Game Screen Add FirebaseDB1 , name the Project bucket to : sketch  , and put the URL AS : https://sketchnguess-cd.firebaseio.com/

2- in the blocks :  

1- In the dragged Event , add FirebasDB Store Value with tag of The Student Name  with a value  Make list of all the values in the DrawLine

2-In the Clear Event , Store to the Student Name Tag → Create an Empty List

3- Handle Screen Game BAck Pressed as Call FirebaseDb.ClearTag with the student Name


==== Demo and Show DB ====