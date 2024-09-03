---
layout: default 
title: Syllabus
nav_order: 1
---


## Computational Geometry, Fall  2024


## Syllabus


__Instructor:__ Laura Toma (she/her)
__Email:__  ltoma at bowdoin.edu
__Office:__ Searles 219 
__Class time:__  MW 1:15-2:40
__Classroom:__  Searles  126 


### Prerequisites

csci 2200 (Algorithms) and csci 2330 (Systems). In other words, basic knowledge of:

- Analysis (asymptotic notation, growth, recurrences); basic algorithms and data structures (searching, sorting, binary search trees, priority queues) and algorithm design techniques (divide-and-conquer, greedy)
- Programming in C/C++, Unix terminal commands and Makefiles


### Overview

Computational geometry studies algorithms for problems that involve
geometric data -- sets of points, line segments, polygons and
polyhedra --- and is a field driven by applications in e.g. graphics,
robotics and databases. Some classical examples of geometric problems:
Is a point inside or outside a given polygon? Given a set of points in
the plane, what is the closest pair of points? What is the smallest
convex polygon that contains a set of points in the plane?  What are
all the points that fall in a given query range? What is visible from
a point in a polygon?  Do two polygons intersect?  Given a set of
points, what is the smallest circle that encloses them? Given a set of
polygonal obstacles and a polygonal robot moving in 2D with
translation and rotation, what is an efficient path between a start
and end location? And many more. This class is an introduction to
computational geometry and will cover some fundamental problems and
techniques in the field.

### Learning goals 

- Understand  fundamental problems and techniques in computational geometry
- Gain experience implementing geometric algorithms, including designing test cases, handling special "degenerate" inputs, and visualization
- Gain coding skills in C/C++  and work on larger projects 
- Gain experience with the interplay between theory and practice and
  the importance of efficient algorithms
- Improve communication and writing skills through presentations and project reports


### Syllabus overview

The class will draw from fundamental topics: 

- Introduction (collinear points, closest pair of points)
- Geometric primitives (area of triangle, orientation, segment intersection)
- Convex hulls in 2D  (naive, gift wrapping, quickhull, Graham scan, incremental, divide-and-conquer; lower bound)
- Convex hulls in 3D
- Segment intersection (Bentley-Ottman sweep)
- Art gallery problem. Fisk's sufficiency proof.
- Polygon triangulation (quadratic, based on ear removal algorithm;  triangulation of monotone polygons; polygon triangulation in O(n lg n) via trapezoidalization).
- Geometric searching (orthogonal range searching with kd-trees and range trees).
- Voronoi diagrams and Delaunay triangulations.
- Combinatorial motion planning in 2D (C-space and C-obstacles; planning via graph search; visibility graph)
- Heuristical motion planning (grid-based techniques, sampling, PRM, RRT)


 
### Textbooks

There is no required textbook. The course is based on two classical textbooks, below. You can find them in Searles 224 (you're more than welcome to read them, but please do not take them out of 224).

- [Computational geometry in C](https://www.amazon.com/Computational-Geometry-Cambridge-Theoretical-Computer/dp/0521649765/ref=sr_1_3?ie=UTF8&qid=1389985599&sr=8-3&keywords=computational+geometry). J. O'Rourke.
- [Computational geometry: algorithms and applications](https://www.amazon.com/Computational-Geometry-Applications-Mark-Berg/dp/3540779736/ref=pd_bxgy_b_img_z). Mark de Berg, Otfried Cheong, Mark van Kreveld, Mark Overmars.

### Communication

Class communication will be entirely on Slack. You will need to
monitor Slack for class updates, including possible cancellations or
delays (in case there are any). The link to join Slack is posted on
Canvas.

     
 
### Course requirements  and grading policy



- __Projects: 70%__ 

- __Exams: 20%

- __Class engagement: 10%__


__Projects__  (tentatively aiming for 7 projects, due approximately biweekly) 

__Exams__ There will be two exams, a midterm and a final,
non-cumulative. Exams will be in class, the first one approximately
half way through the semester and the second one at the end of the
semester. Exact dates will be announced later.


__Engagement__ Engagement is crucial for effecive learning, and it
counts as a significant part of your overall grade. Engagement does
not mean having the right answers, but it means contributing
to the class learning community.

    What you can do to help the class learning community: attend
    class, work with your group, consistently and independently engage
    in discussions during class, volunteer ideas and make
    observations, ask questions, work on the whiteboards, offer to
    write on the whiteboard, draw diagrams and examples, participate
    on Slack, attend office hours, be respectful and inclusive of your
    peers, don’t be loud, have a positive attitude, do your best to
    have a good time and strive to turn in good work.

    Activities that hinder the class learning community: doing
    something else in class, working on a different assignment in
    class, checking your messages, dominating the discussion, not
    talking at all or talking too much, showing off when you finish a
    problem fast, not doing your readings and coming unprepared to
    contribute, etc.



