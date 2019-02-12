# Project 2 - Making 3D Images
Due: Thursday, October 22, 2015 at 11:59 pm
For this assignment, you are to combine two images into a single 3 dimension image. These images will be viewed using red/blue glasses to give the 3D effect. The final image will attempt to be a grayscale of the object in the original original images. However with the red/blue glasses, one eye will only see the red color while the other eye will see the green/blue color.

The two images will need to be pictures of the same thing taken from a slightly different view point. The first image will view the object just to the left of the view of the second image. The left image will be converted to a red-scale image. The right image will be converted to a green/blue-scale image.

Once the red-scale and green/blue-scale images have been created, they can be combined into a single image. At each pixel in the final image, the amount of red will come from the corresponding pixel in the red-scale image; while the amount of green and bluee will come from the corresponding pixel in the green/blue-scale image.

You are to verify that the two images have the same width and height before attempting to create the 3D image. If the images do not match, print out an error message and exit the program.

Check out the following images of UIC (courtesy of Google Earth):



These two combine to create the following 3D image:


The intermediate versions of the images are as follows. Note that there is no reason to actually create and save these intermediate versions. You should be able to go from the two original images directly to the 3D image.



Other source images are:
The 3D result can be seen here.

The 3D result can be seen here.

  
The 3D result can be seen here.

Your code is to prompt the user for the left image first, then the right image. The final image is to be displayed and you are to prompt the user for a name to store the resulting image.
