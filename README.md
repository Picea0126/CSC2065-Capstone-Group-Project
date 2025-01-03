# CSC2065 Capstone Group Project
This folder contains programs that can be used to visualize and analyze a social network dataset. The provided dataset is the file SocialNetworkData_10K.json.

# adjacency_matrix.py
Represents a subset of the the social network as an adjacency matrix. The subset range can be adjusted by modifying the n_start and n_end variables.

# bfs_shortest_path.py
Uses breadth-first search to find shortest paths. The user enters a node id, then the program finds the shortest path to every other node in the network.

# complexity_analysis.py
Uses Big O notation to analyze the time complexity of a number of network operations.

# dfs_cylcles.py
Uses depth-first search to find a cycle in a subgraph of the network. The subgraph range can be adjusted by modifying the n_start and n_end variables.

# graph.py
Represents the social network as a graph. May take longer than 30s to load graph, depending on your system.

# network_properties.py
Checks network properties such as graph connectivity, minimum node degree, and edge/node connectivity

# query_system.py
Uses boolean algebra to filter users in the network. Boolean statements are made up of the following predefined symbols:
    a - User is 21 years or older
    i - User has one interest
    c - User lives in a capital city (US)
-Boolean statements are entered in disjunctive normal form
-Two symbols entered next to each other represent a logical AND
-A \'+\' between symbols represents a logical OR\n\
-A symbol entered in uppercase form represents a logical NOT
Example: \'iC+a\' would return users who either have one interest and do not live in a capital city, or users who are 21 years or older

# tree.py
Represents a subset of the network as a minimum spanning tree. The weight between nodes is an integer equal to their age gap. The subset range can be adjusted by modifying the n_start and n_end variables.

# user subsets.py
Allows subsets to be defined by field values. Union, intersect, and difference operations can be applied to subsets. For example, the set of users from Denver can be intersected with the set of users who are 21 years old.