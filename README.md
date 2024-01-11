# Python Games

I followed a handy tutorial compilation video from freeCodeCamp.org to make each of the following games. The code has been retyped as per each tutorial in an effor to further my knowledge of the Python language by using pygame.

Reference Video: https://www.youtube.com/watch?v=XGf2GcyHPhc&t=116s

## Installation

It's suggested to clone the entire github repo for playing locally, however it is possible to pull some of the individual games. Pong, Snake, and Connect Four will all work independently.

### Tetris

For Tetris to function properly, you will need to ensure the 'tetris_scores.txt' file has also been downloaded to the same local folder. Alternatively, a text file with the same name will need to be created and a single integer value placed in the first line. If you'd like to change the name of the file, please review the code itself, however it should be noted that without fulfilling this requirement Tetris will not work correctly.

### Online_Game_v1

This is not quite a 'game' so much as an experiment in creating online connectivity through Python via sockets. The code works, but will require some configuration to run locally. If interested, please reference the comments within the ***server.py*** and ***network.py*** files and insert your appropriate local IPv4 address before executing. This folder should be cloned in its entirety to ensure full functionality. To run, simply start an instance of ***server.py***, followed by two instances of ***client.py***.

### Rock_Paper_Scissors

This game may or may not work. In any case, it will require some tweaking of proper IP addresses in both the ***server.py*** and ***network.py*** files, just as with the experiment for *Online_Game_v1*. A far more complex experiment, this should work with multiple connections for multiple games, but I have yet to achieve functionality as expected.

### What Did We Learn?

To put it simply, coding a game via pygame is way more difficult than working with the Unity Engine and C# programming language. While these projects were a fun dive into the world of Python, I find the language to be more applicable in for more analytical use-cases. If I ever were to return to the world of game development, I am certain it would be within either C# or C++ in Unity or Unreal. Firstly, those games produce far more satisfying graphical results, and required less confusing code (albiet not as effecient code). Either way, these were enjoyable learning experiences, and I'd recommend following the reference video above if you find yourself curious about the potential ability of python for video game development. Project closed.