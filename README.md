# Search
Learning Objectives
A common problem in robotics and control is path planning.
In EE 16B, we studied controllable systems from a linear-algebraic perspective. 
Our state variables (angle, position, etc) would be represented by a vector, and the system would be represented by matrix transformation. 
We used this linear system perspective as a means of controlling our robot car.

Once we have a robot under control, the next thing we want to do in a variety of scenarios is to plan out the path that our robot car should take to accomplish a certain task. 
In order to do so, we'll need to reconsider how we think about our "state"—rather than view a state as a vector which can take on continuous values, 
  we will instead define a set of discrete values that our variables can take on and consider the state as a node in a graph.

You'll recall from EE 16B that given a continuous-time system, we can sample or discretize in the time dimension and model some scenarios with a discrete-time system. 
Graph state-space models take another step of also discretizing in the spatial dimensions to have a finite number of possible states.

Navigating this repository
Note is contained in State Spaces and Search Note.pdf
Slide Deck is contained in State Spaces and Search Slide Deck.pdf
Code is contained in State Spaces and Search.ipynb
Quiz Questions are contained in State Spaces and Search Quiz Questions.pdf

