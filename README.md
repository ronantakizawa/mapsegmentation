Final project for CP307 (Data Structures and Algorithms) at Colorado College.

Worked with Oliver Moscow and Khawla Douah


This is an algorithm demonstrates trapezoidal decomposition with random on a plane. Each segment is then stored in a segment tree. 

This algorithm can divide maps into different segments, and each segment's data can be stored on the segment tree with its information easily
accessible. 

Installation

-      pip install -r requirements.txt


Run each segment of code to divide map segments and store it in the tree. 

1. Plot a random set of polygons that represent map regions
2. Divide the maps up for every vertex (Trapezoidal Composition) and store a tuple (Region lines, region names) that will be used as leaf nodes for the segment tree
3. Create the segment tree

<img width="650" alt="Screenshot 2023-10-15 at 17 26 23" src="https://github.com/ronantakizawa/mapsegmentation/assets/71115970/adc5d456-ae30-43ba-9bc8-5ee8e02507f2">
