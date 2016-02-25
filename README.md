# CSCI5239_HW6
Android and iOS
Diana Southard
CSCI 5239 Spring 2016

#### Directions

Create a program that allows a scene to be viewed in 3D from any direction
under user control that can be run on the iPhone/iPod/iPad or Android.

You must build some solid 3D objects yourself using OpenGL ES.  In particular,
there are a number of frameworks such as GLKit on the iPhone that permits you
to write applications without using OpenGL ES.  In this assignment I would like
you to get some exposure to the nuts and bolts of OpenGL ES, so using such
frameworks is prohibited.

You may want to start with my simple application and explore features such as
lighting and textures, gestures, and so on.  However, you do NOT have to follow
my example (borrowed from Rideout's iPone 3D programming) and develop the core
code in C++ and only providing a native wrapper.  You may want to  stick with 
Objective C on the iPhone or Java on the Android throughout your program. The
Android SDK contains examples that are pure Java.

You may also want to explore the Qt for Android or Qt for iPhone approach.  If you do, I need you to improve the examples provided in their tutorials.


#### Android Application Description
This app shows a cube rotating on its axis with colored faces against a black background with a light point rotating about the cube. The app utilizes per-fragment lighting in its shaders. Based on Lesson 3 from [LearnOpenGLES](http://www.learnopengles.com/android-lesson-three-moving-to-per-fragment-lighting/) with shapes from the [Android Tutorials](http://developer.android.com/training/graphics/opengl/projection.html)

#### Program Use Instructions
- Compiled on AndroidStudio running on Ubuntu
- Import project to AndroidStudio and run either on emulator or device
**Time To Complete Assignment:** ~ hours


