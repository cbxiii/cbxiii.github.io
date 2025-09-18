---
layout: project
type: project
image: img/canoe.jpg
title: "Canoe Loading and Resource Distribution"
date: 2025
published: true
labels:
  - Python
  - Data Structures
  - Algorithms
summary: "Implementing an algorithm that optimizes resource distribution to a network of islands."
---

<img width="400px" src="../img/canoe.jpg" alt="Image of canoe">
<br>

This project was an assignment for my Algorithms course. I had to create an algorithm that ensures a resource produced on one island is distributed to as many other islands as possible, as efficiently as possible. I had to load resources on canoes that had a defined capacity, and then distribute those resources equally to all of the islands. I also had to find the most efficient route between the islands for the canoes to take.

I implemented the islands as a graph, with the nodes being the islands themselves. The edges of the graph were the possible routes between two islands; the edges were also weighted with the distance between the two islands.

For this algorithm, I decided to implement a greedy approach for loading the canoes because it allowed for loading the most amount of resources on the fewest amount of canoes. I also chose this approach because the canoes allowed fractional loading, which means the canoes can be loaded without worrying about any resources being left over. In order to find the most efficient path for the canoes to take between the islands, I implemented Dijkstra's algorithm. This algorithm compares the distances of each of the node's neighbors, and chooses the shortest path. 

With completing this project, I learned about how to implement a graph in a program, and about how Dijkstra's algorithm works to find the shortest path within a graph.

Link to source code: <a href="https://github.com/cbxiii/ics311-5">https://github.com/cbxiii/ics311-5</a>
