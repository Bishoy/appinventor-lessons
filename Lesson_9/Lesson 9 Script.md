==========================

--- recap and explain the database -----

==========================

2- In The Watch Screen , put a Vertical Arrangement , fill , put a Canvas , make fill and a button for back, Add FirebaseDB1 , with same url and same project bucket

3- in the blocks:

1- Handle only Firebase DB 1 –>Data Changed

2- inside DataChanged , Check if the GetTag (from changed) == A friend's name ( ask kids to give the names they used to make it interesting ), 

the game that way will listen to changes made by classmate

3- inside the if make a DrawLine where x1 is select list item at index 1 from get value , x2 index 2 select list item from get value, so on ... ( have a look at DrawLine at the image below )

=== Demo and make kids play against each other ===

4- Game Screen  : in the blocks :  

1- ( Already done ) firebase store in the tag of The Student Name a value  Make list of all the values in the DrawLine

2-In the Clear Event , Store to the Student Name Tag → Create an Empty List

3- Handle Screen Game BAck Pressed as Call FirebaseDb.ClearTag with the student Name