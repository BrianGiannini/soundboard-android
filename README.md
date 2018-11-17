Boîte à Philippe
======
(Some french insults for your pleasure !)

Use this app to make a Soundbox app

Beginner tutorial :
- Change sounds in app/res/raw with your own sounds (soundsX1_X2 where X1 is column and x2 is row) 
- Put your custom header image by replacing those in app/res/drawable (imageTopLeft/TopRight)
- Add more buttons by adding them in the gridLayout (activity_main -> GridLayout)
- android:layout_column="0" or "1" for the left or right column
- To add an additionnal column: android:layout_column="2" + in GridLayout: android:columnCount="3"
- To add an additionnal row:  android:layout_row=4 + in GridLayout: android:rowCount="5"
- To add button on multiple row set android:layout_rowSpan="x"
- To add button on multiple column set android:layout_columnSpan="x"


Made by Brian Giannini