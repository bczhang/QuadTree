QuadTree
========

A quad tree is a data structure specializing in the storage and lookup of points contained within a rectangular region of a 2d plane. This demo allows a user to insert points into a quadtree and shows the dynamic breakdown of the node structure. Inserts, deletes, and searches are performed in logarithmic time. Quad tree is dynamic and allocates the minimum number of nodes necessary to partition the point set, because of this it is capable of high precision even on large regions without requiring enormous memory overhead.  
  
Controls
========

* 'leftmouse' - place new point
* 'w' - pan up
* 'a' - pan left
* 's' - pan down
* 'd' - pan right
* 'b' - reduce bucket size
* 'B' - increase bucket size
* '-' - zoom in
* '+' - zoom out
* '~' - reset tree/delete points
