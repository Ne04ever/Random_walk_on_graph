# Random_walk_on_graph
Using random walk on full graph to study its properties

## Introduction:
A simple random walk on a graph is a sequence of movements from one vertex to
another where at each step the next vertex is chosen uniformly at random from the
neighbors of the current one. The cover time of the walk is the expectation of the
number of steps required to visit every vertex. The aim is to investigate how the
expected cover time behaves depending on the size of the considered graph and its
connectivity properties..


## Procedures:
1) Create a function to generate transition matrix of a complete graph with N
vertices.
2) Create a function to generate transition matrix of a graph obtained by joining two
complete graphs on N/2 vertices each by a single cross-edge
3) Create a function to find the covertime of a given transition matrix
4) Find the expected cover time by applying law of large numbers.
5) Analyse the cover time of both complete and joined graphs.


## Observation 1
The Expected cover time increases as the number of vertices increases.
• Expected cover time for 25 vertices : 90.363
• Expected cover time for 50 vertices : 219.622
• Expected cover time for 75 vertices : 361.0
• Expected cover time for 100 vertices : 511.42


## Observation 2
The expected cover time of the joined graphs increases substantially comparing to the
complete graph
For vertices 2,4,...20 the expected cover time for the;
• complete graph is : 2.0, 6.3, 12.5, 18.908, 26.6, 34.08, 42.026, 51.76, 59.308, 67.67
• Joined graph is : 2.0, 12.1, 21.3, 37.932, 55.5, 77.08, 98.329, 124.71, 150.081, 186.7
