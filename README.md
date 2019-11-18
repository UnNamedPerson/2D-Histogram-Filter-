# 2D-Histogram-Filter-
This project uses c++ to make a 2d Histogram Filter. The filter uses basics of robotics localization to be able to give the right probablity when the robot makes a movement to a certain direction.

the fllowing files are the important ones in the project:

. maps: folder that contains files of different representation of 2D matrices to test the program and see if works with different matrices. 

. Test.cpp: a testing file that checks if different functions within the other files are working correctly.

. Helpers.cpp: contains the functions normailze (makes all the probablities sum to 1) and blur (the function works as to "spread" the probablities all over the matrix, so that no value is zero in the matrix.)

. Localizer.cpp: makes use of initilize_beliefs sense (a function that aims to update the probablity within cells of the matrix currently, which is usually used after moving the robot.) and move (a function that shows the new probablity after the robot moves in the matrix a certain step) functions. 

