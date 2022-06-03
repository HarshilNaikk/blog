# Research Projects

## Motion Planning for Autonomous Quadrotors
*As a part of Team Aerove, UMIC. Guide : Prof. Dhwanil Shukla, Dept. of Aerospace Engineering, IIT Bombay*

I led the Motion Planning subsystem at Team Aerove for developing a heavy-lift autonomous multirotor capable for performing aerial manipulation tasks in extreme environments. This was done as part of the International Aerial Robotics Competition, hosted by AUVSI. \

I worked on implementing standard algorithms like A*, RRT*, and Potential Field algorithms to Ardupilot SITL simulations for planning a path in an indoor obstacle rich environment. After this, I worked on a real-time planning strategy that used Vector Field Histograms for robust and quick planning. This then led to an implementation of a real time planning algorithm that used memory histograms that involved having a form of "memory" for the obstacles so that the drone can plan not just based on the forward view, but based on past data as well. This increased the optimality of the path being generated, while keeping the computational complexity low. \
\

## Distributed Multi Agent Bias Estimation
*Guide : Prof. Sukumar Srikant, Dept. of Systems and Control, IIT Bombay*

I worked on 

## Multi Agent Connectivity Maintainance
*Guide : Prof. Shashi Ranjan Kumar, Dept. of Aerospace Engineering, IIT Bombay*

I worked on implementing a Connectivity Maintenance framework for a multi agent network that enabled the graph to always remain fully connected, even when one or more agents have ulterior motives, and move according to an external planner. 
It works in two steps - at the start of each iteration, the graph is checked to be fully connected. That is accomplished by computing the fiedler eigenvalue (This is done in a decentralized manner by using the PI Average Consensus algorithm). After this, a global connectivity potential is implemented that tugs the agents in a direction so as to always remain connected.

# Technical Projects
