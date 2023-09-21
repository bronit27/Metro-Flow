# Metro-Flow

This is NOT an ANDROID Application!

Presented here is a Java application designed to assist users in navigating the Delhi Metro system. It prompts the user for their starting and ending stations, calculates the fare, and identifies the shortest metro route to reach their destination. The program also offers a visual metro map to aid commuters in their journey.

The underlying concept leverages Graph and Heap data structures for efficient processing. The graph comprises nodes and edges, where nodes correspond to metro stations, housing essential details like station names, metro corridors, and connecting lines. Edges, representing links between nodes, signify the distance between two stations, with each edge's cost equaling the distance between its associated stations.

A variety of algorithms, including Dijkstra's, breadth-first search, and depth-first search, come into play to determine the optimal path from the origin to the destination station. The fare is then calculated based on the total distance traveled between the two stations. Finally, the program presents the metro route connecting the two stations and displays the total fare.

For implementation, you'll find the primary code in the Main.java file, while Heap.java contains the heap data structure implementatio


	
