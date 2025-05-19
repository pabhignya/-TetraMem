# TetraMem
 TetraMem 2D Path Problem
 You’re given a 2D universe, specified as an image file with only black and white values (you can find some examples at https://github.com/mcollinswisc/2D_paths), and two points 
 A and B.
 Write a Python function that determines whether a path exists between two points that only crosses black pixels. Define a path as a sequence of pixels such that each pixel in 
 the path is adjacent to the next pixel in the path. An example function signature follows, but you are not required to use this.

 Intution:
 ## Single Path
 From start point to end point run bfs and find the shortest possile path.
 ## Two non intersecting Paths
 We already have single path now mark that are as white nodes and block it. Now check if there exists path between the points it can be of right or left direction, if possible return the path.
