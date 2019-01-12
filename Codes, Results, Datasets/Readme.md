# Content Aware Rotation - A work by Kaiming He and others at ICCV 2013 
This is an independent implementation of thier work, done as a part of a course project at the Indian Institute of Technology Gandhinagar. The implementation has been, in part, inspired by the iRotate repository in GitHub. 

Dependencies

1. OpenCV 3.4.2
2. Python 3.6.6
3. MATLAB R2017a

For running the program, go to terminal, then do the following:
1. python main.py
2. The terminal will prompt for Image Number from Dataset. 
3. Choose a number from 1 to 9. 
4. Choose the rotation angle, corresponding to that image
	from the file called RotationAngles.txt from the Dataset Directory.
5. The program runs for 10 iterations. Kindly wait till this procedure is over.

After the python program exits,
1. Open the main.m program in MATLAB.
	a. Rename the filepath accordingly as the image number that you
		gave as in input to the python program.
	b. It is by default set to image 6 - Please change it if you want
		to test on other images.
	c. Image 9 is in jpg format. Kindly change the filepath to
		'Dataset/image9.jpg',when using image9.
2. Make sure you set the local path of the directory as the current
	directory; Otherwise, there might be an error.
3. One can always use absolute path.
4. Output will be the rotated image.

The output image is stored in the same directory as image.png in this directory.

