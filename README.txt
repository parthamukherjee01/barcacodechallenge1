Run Command given below to run from command line. Copy the collinear.jar in a path then run.

Two different approaches. 
Inputs need to be passed from commandline argument as x1,y1 x2,y2......xn,yn

1>
This is to find collinearity of any unique combinations of points:
java -cp collinear.jar com.exercise.collinear.FindCollinearForAnyPoints 1,1 9,8 2,2 -1,-1 0,2 -6,2 -10,-10 30,21 77,77
java -cp collinear.jar com.exercise.collinear.FindCollinearForAnyPoints 0,0 1,1 2,2 3,3 4,2 5,1 3,2

2>
This is to find collinearity of three unique combinations of points:
java -cp collinear.jar com.threepoints.collinear.FindCollinearForThreePoints 1,1 9,8 2,2 -1,-1 0,2 -6,2
java -cp collinear.jar com.threepoints.collinear.FindCollinearForThreePoints 0,0 1,1 2,2 3,3 4,2 5,1 3,2