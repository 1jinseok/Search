# Search

A common problem in robotics and control is path planning. In EE 16B, we studied controllable systems from a linear-algebraic perspective. Our state variables (angle, position, etc) would be represented by a vector, and the system would be represented by matrix transformation. We used this linear system perspective as a means of controlling our robot car.

Once we have a robot under control, the next thing we want to do in a variety of scenarios is to plan out the path that our robot car should take to accomplish a certain task. In order to do so, we'll need to reconsider how we think about our "state"—rather than view a state as a vector which can take on continuous values, we will instead define a set of discrete values that our variables can take on and consider the state as a node in a graph.

You'll recall from EE 16B that given a continuous-time system, we can sample or discretize in the time dimension and model some scenarios with a discrete-time system. Graph state-space models take another step of also discretizing in the spatial dimensions to have a finite number of possible states.  

## Learning Objectives  
Upon completion of this lesson, the student will be able to: 

1. Formulate problems using discrete state-space representations, motivated by the example of path planning for a 6DOF Robotic Manipulator. 

2. Use common uninformed search algorithms (BFS, DFS, and UCS) to solve search problems, generating nodes on-demand. 

3. Understand the strengths and weaknesses of different search algorithms.

3. Identify how to create useful heuristics and use them to inform the search process.

4. Implement informed search algorithms such as Greedy and A*, and apply them to efficiently solving a wide variety of problems in Artificial Intelligence. 

## How this assignment helps with that 
The assignment builds off of the problem of robotic manipulation which students in EECS 16B will find familiar. It then delves into the process of designing state-space representations for the 6DOF robotic manipulator, allowing students to observe how we can turn a real-life scenario into a graph search problem. 

Students then take on the meat of the challenge, namely implementing both the uninformed and informed search algorithms on a graph. They compare the performance of these search algorithms and see how they are able to use it to get a path from the start to the goal. Finally, they are able to put the pieces together and use their search algorithm to solve the original problem in path planning for a robotic manipulator. 

## Navigating this repository

Note is contained in Note.pdf

Slide Deck is contained in State Spaces and Search Slides.pdf

Code is contained in State Spaces and Search.ipynb

Code solution is contained in State_Spaces_and_Search_Solution.ipynb

Quiz Questions are contained in Quiz Questions State Spaces and Search.pdf

Quiz Solutions are contained in Quiz Solutions State Spaces and Search.pdf


