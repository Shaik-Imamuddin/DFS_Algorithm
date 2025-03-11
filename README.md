# DFS_Algorithm

Step 1: Create a visited array of size equal to the number of vertices and initialize all elements as False.

Step 2: Create an empty stack and push the starting vertex into it. Mark the starting vertex as visited.

Step 3: Repeat the following steps while the stack is not empty:
- Pop the top vertex from the stack and store it in currnode.
- Print or process the currnode.

Step 4: Access the adjacency list of the current vertex and traverse all its adjacent vertices.

Step 5: For each adjacent vertex:
- Check whether it is already visited.
- If it is not visited:
  - Mark it as visited.
  - Push it into the stack.

Step 6: Continue traversing the adjacent vertices until all neighbors of the current vertex have been checked.

Step 7: Repeat Steps 3–6 until the stack becomes empty.