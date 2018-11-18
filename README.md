soundbox-android
======
Use this app to make a Soundboard app

This app is called "Boîte à Philippe", a soundbard app that parodies the awfull french voice of the actors of the film called "Hitman Cobra". This film is known as a "nanar" type of film in France, like B-movies.

Beginner tutorial :
- Change sounds in `app/res/raw` with your own sounds (soundsX_Y where X is column and Y is row) 
- Put your custom header image by replacing those in `app/res/drawable` (imag_top_left/imag_top_right)
- Add more buttons by adding them in the gridLayout (activity_main -> GridLayout)
- android:layout_column="0" or "1" for the left or right column
- To add an additionnal column: android:layout_column="2" + in GridLayout: android:columnCount="3"
- To add an additionnal row:  android:layout_row=4 + in GridLayout: android:rowCount="5"
- To add button on multiple row set android:layout_rowSpan="x" where x is the number of row you want to span
- To add button on multiple column set android:layout_columnSpan="x" where x is the number of row you want to span


Made by Brian Giannini
