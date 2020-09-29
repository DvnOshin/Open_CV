# Open_CV
Introduction to OpenCV with a basic project using Python

INTRODUCTION
WHAT IS COMPUTER VISION?

Computer vision is an interdisciplinary field that deals with how computers can gain a high-level understanding from digital images or videos. 
The idea is to automate tasks that the human visual systems can do. Therefore, a computer should be able to recognise that this is the face of a human being; 
this is what a lamppost looks like; this is a statue, etc.

HOW A COMPUTER READS AN IMAGE?

A computer does not see a real image, they see a matrix of numbers between 0-255. So for a coloured image, there will be 3 channels red, green and blue with a matrix associated 
with each of these channels and each element of this matrix represents the intensity of brightness of that pixel. These channels will have their separate matrices and 
are stacked on to each other to create a 3-dimensional matrix. So, a computer will interpret a coloured image as a 3d matrix. 
So if it is said that the size of an image is 500*500 and it's a coloured image, then it means that there are 500 rows and 500 columns and 3 channels.
One thing to note is that for greyscale or of a black-and-white image, there is only one channel.

1.) For a coloured image, it will be 3d matrix and for a greyscale image it will be 2d matrix
2.) To calculate the number of pixels - just multiply no. of rows, no. of columns and the number of channels.

WHAT IS OpenCV?

OpenCV is the library used for computer vision. First developed in the year 1999 at Intel by Gary Bradski and the first release came out in 2000. 
OpenCV supports a wide variety of programming languages such as C++, Java, Python etc. and also supports different platforms such as Windows, Linux etc. 
In OpenCV, all the images are first converted to a NumPy array which makes it easy to integrate it with other libraries that use NumPy like SciPy and Matplotlib.
It is an opensource computer vision library. It’s a python library that is used for real-time computer vision

Applications of OpenCV

1. Building GUI
2. Video analysis
3. 3-D reconstruction
4. Image processing operations
5. Feature extraction
6. Object detection
7. Machine learning
8. Face and object recognition
9. Text recognition and detection
10.Shape analysis

Future scope

The scope of computer vision and that of OpenCV is huge. 
Object (human and non-human) detection in both commercial, as well as governmental space, is huge and already happens in many ways.
