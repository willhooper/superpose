# Superpose
C++ code for finding the rotation matrix and translation vector between two points (using the Kabsch algorithm). Includes functionality for applying transformation.
This is more or less a direct translation of the python code I found sitting on
the Bystroff server.

Algorithm takes 2D vector of the form [ [x], [y], [z] ]. Use the transpose function
if your points are in the form [ [x,y,z] , [x,y,z], ... ]

No dependencies, compiles with g++

http://www.bioinfo.rpi.edu/bystrc/
