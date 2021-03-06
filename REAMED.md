Sometimes you want to try out some gamming idea or technique, like how to make the trajetory for a jumping movement, or how to draw a scenery with multiple layers, or something else. But to start doing anything, you will need first to build some basic system structure/modules for the game. I believe that the most basic module that you will ever need is a video processor. This work was made up from this need, based on my previous gamming project. It try to explain how to build a video processor module and some basic concepts that you will need to understand how to implement and use it. This processor is aimed for 2D games and was designed with a structured language (C language) in mind.

Just to keep clear, i believe that all the idea drafted here can be found in books or forums and, with a high probability, you will find more advanced technics - also complex - for the task that this work proposes.

In the second section were defined and explained the data types and functions used to get the video processor on work. Also, there is some basic video definitions and concepts for 2D game programming. In the third section there is an implementation design that i've proposed and called Moth Processor. Both, the implementation idea and the implementation design are based on the use of the Allegro library library, but i strongly believe that it could be easily replaced by another resource of your choice.

I suggest you to start doing just an overview of the "Basic Data" section and return to read it more carefully when some data type is mentioned in the text.

This documentation was entirely made by me (except by some of the illustration images, that i have found around the internet) and is free to read and redistributre. Its files can be found at [1], and an implementation for Oriented Object Programming, based on this work (also made // by me), can be found at [2].//

[1] https://github.com/dendriel/Moth

[2] https://github.com/dendriel/games/tree/master/Cpp

----

ATTENTION! You can download the projet in HTML format directly from the wirar file "video_processor_html.tat" and open with your browser.

----

Introduction
1.1. Glossary and Standards
Interface Overview
2.1. Basic data
2.1.1. Structures
2.1.2. Types Definitions
2.1.3. Enumerations
2.1.4. Constants
2.2. General Functions
2.3. Working on Visual Elements
2.3.1. Create
2.3.2. Update
2.3.3. Remove
2.3.4. Visibility
2.3.5. Layers Facility
2.4. Working on View data types
2.4.1. Create
2.4.2. Update
2.4.3. Destroy
2.5. Screen Positioning Concepts
2.5.1. Relative and Absolute positioning
One Level Bellow
3.1. What initialization initializes?
3.2. Interface Thread
3.3. Updater Thread
3.3.1. Control Flags
3.3.2. Update Screen
3.3.3. Sleep Interval
3.4. Memory Access Control
References
