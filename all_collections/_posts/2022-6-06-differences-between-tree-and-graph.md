---
layout: post
title: Differences Between Tree and Graph
date: 2022-6-06 10:18:00
categories: [Tree, Graph]
---

Although tree and graph are non-linear data structures, there are many differences between them. The main differences between them are due to the fact that graphs were invented to create computer network, and later turned into a non-linear data type with the development of algorithms. Trees, on the other hand, were designed from the very beginning to store data. There are three differences between them, design of the structures, formations, and root node requirement.

![alt](https://picsum.photos/800/300)

In their formations, there is no feature in the trees. However, In the graphs loops can be created within the database. This makes graphs programmable.

For node requirement, trees must have a root node because of their structure, to reach other nodes, the first node is taken as a starting point and the nodes are skipped one by one to reach data. If the starting point is not taken, the location of the data to be reached on the tree cannot be calculated. In the Graph data type, there is no starting point, it can be started from any point, this feature comes from the fact that graph is basically network struct.

As a result, graph provides a lot of flexibility and has more features compared to tree. However, since the graph data type is complex and difficult to implement, it may be more logical to use the tree data type for small structure types, but graph seems to be a good solution for large-scale data structures.