Search Algorithm which helps in finding the opitimized result(distance) from point A to point B

1. Start with a frontier that contains the initial state

2. Start with an empty explored set (data structure containing the set of nodes already explored)

Repeat:
 
3. If the frontier is empty, then no solution

4. Remove a node from the frontier

5. If node contains the goal state, return the solution // Check with goal test

6. Add the node to the explored set

7. Expand node, add resulting nodes to the frontier if they aren’t already in the frontier or the explored set // Expand node: Explore the other nodes linked with the current node
