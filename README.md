# Perspective_Transformation_opencv_python

################# ENPM- 673 PROJECT_1 ####################

**********************************************************
               Python version - 2.7.12
             Opencv Version - '3.3.1 - dev'
**********************************************************


NOTE: IF you are using Python3, please remove the first parameter returned by the function cv2.findContours()

For example: 
In python2,
p, contours, hierarchy = cv2.findContours(thresh, cv2.RETR_TREE, cv2.CHAIN_APPROX_SIMPLE)

In python3,
contours, hierarchy = cv2.findContours(thresh, cv2.RETR_TREE, cv2.CHAIN_APPROX_SIMPLE) 




PART 1 - DETECTION OF THE APRIL TAG AND ITS ENCODING SCHEME:

Without Kernelized Correlation Filters Tracker:

Step 1: Run the part1_without_tracking.py file
Step 2: Make a choice to run different videos
Step 3: The detected ID from the tag and the corresponding corners of the tag are printed in the Terminal.

With Kernelized Correlation Filters Tracker:

Step 1: Run the part1+tracking.py file
Step 2: Make a choice to run different videos
Step 3: The detected ID from the tag and the corresponding corners of the tag are printed in the Terminal.

You can notice the improvement in the detection and the removal of unnecessary noises in the Frame.



PART 2 a) - SUPERIMPOSING AN IMAGE ONTO THE TAG:

Without Kernelized Correlation Filters Tracker:

Step 1: Run the part2_without_tracking.py file
Step 2: Make a choice to run different videos

With Kernelized Correlation Filters Tracker:

Step 1: Run the part2+tracking.py file
Step 2: Make a choice to run different videos


PART 2 b) - PLACING A VIRTUAL CUBE ON THE TAG 

Step 1: Run the part2b.py file
Step 2: Make a choice to run different videos 








