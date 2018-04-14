**P1 Building the graph**

My solution consisted of nesting for loops and if statements to loop through each member and find its connections. This helped me build the graph. 

My run time is O(G * M^2 * L^2)

**P2 Connecting to someone using Breath-first Search**

*Time taken to find path to member with BFS:*

1) 0.01128 seconds
2) 0.01149 seconds
3) 0.01201 seconds

Average: 0.01159 seconds

*Peak memory consumption:* 

Without Path Finding: 128020 kilobytes

With Path Finding : 127900 kilobytes

Difference : 120 kilobytes

**P3 Connecting to someone using IDDFS**

*Time taken to find path to member with BFS:*

1) 0.00991 seconds
2) 0.00902 seconds
3) 0.00997 seconds

Average: 0.00963 seconds

*Peak memory consumption:* 

Without Path Finding: 127975 kilobytes

With Path Finding : 127945 kilobytes

Difference : 30 kilobytes


