---
layout: default 
title: ----Project 7 (3dof)
nav_order: 13
---



## Project 7:  Approximate motion planning with translation and rotation 


*** 
* __Assigned:__ 
* __Due:__  Wednesday December 18th
* Group policy: Partner-optional 
* Collaboration policy: Level 1


### Overview

In this project you will implement approximate motion planning for a
polygonal robot moving among polygonal obstacles in 2d with
translation and rotation (3dof) using one of the following approaches:
A*, RRT or PRM .


### Interface 

When the program starts the user will enter the polygons using the
mouse (in a manner similar to previous projects), then once the scene
is done, the user will enter the robot. Then the user will click on
the start and end position of the robot.

Whichever planner you chose to implement, use it to find a path from
start to end.  Then draw the path and animate the robot traveling
along the path.





### Deliverables/What to turn in

You will receive the assignment on GitHub; it contains no code. Your github repository shoud contain:

* your code 

* The README file is the landing page for the repository and should
contain: (1) a one-sentence description of what the code is doing. and
(2) instrutions on how to run it. Totally fine to keep it minimal, but
anyone shoud be able to run your code after looking at your
README. It's also good practice to include there the bugs or
limitations of the project, so that users are aware.

* A brief report showcasing your project, containing:
    	* (1) which planner you implemented and the basic choices you made 
    	* (2) images of scenes and paths.  There isn't a required number of images, include what you consider a representative sample. 
	* (3) if your code does not work in all cases, explain.
	* (4) Time you spent in: Thinking; Programming; Testing; Documenting; Total.
	* (5) Brief reflection prompts (you don’t need to address all): how
challenging did you find this project? what are some things you learnt
by doing this project? Is there anything you wish you did differently?
If you worked with a partner, how did that go? Is there anything you would like  like to
explore further?

* Capture a movie of the screen while you demo your code and upload it
  to github as `demo.mov`. To demo, no voice, just run your code and
  show what it can do (To capture a movie on a Mac press
  `shift+command+5` and then choose the option that says `record
  selected portion`).


From the beginning, design your code knowing that you will spend 90%
of the time debugging it. If you approach your algorithm with a
theoretical mindset and think before you start coding, you will be a
lot more effective.

Enjoy! 

### Examples from previous semesters

<a href="https://github.com/bowdoin-compgeom-f24/bowdoin-compgeom-f24.github.io/edit/main/Projects/7-planning/demo-annadanielle.mov">A* demo1</a>  | <a href="https://github.com/bowdoin-compgeom-f24/bowdoin-compgeom-f24.github.io/edit/main/Projects/7-planning/demo-caspian.mov">A* demo2</a> 

<a href="https://tildesites.bowdoin.edu/~ltoma/teaching/cs3250-CompGeom/fall21/Assignments/A7-motionPlanning/kevinwill_rrt_demo1.mov">RRT demo1</a> | <a href="https://tildesites.bowdoin.edu/~ltoma/teaching/cs3250-CompGeom/fall21/Assignments/A7-motionPlanning/kevinwill_rrt_demo2.mov">RRT demo2</a>

