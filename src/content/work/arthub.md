---
title: ArtHub
publishDate: 2020-03-04 00:00:00
img: /assets/work/arthub/demo.jpeg
img_alt: Preview of ArtHub program
description: |
  Using Harvard Museum's API to reimagine art relationships
tags:
  - UX/UI Design
  - APIs
  - Processing
---

## Proposal + Design
The goal of this assignment was to create a graph implementation/representation and compare two graph algorithms completing the same task. We chose an Adjacency List representation and to compare Breadth First Search (BFS) and Depth First Search (DFS)​

![alt text](/assets/work/arthub/cover.jpeg "Arthub sketch design")

### Motivation
As a learning tool, this project adds to the learning experience of Art History. The general curriculum involves observing different time periods and cultures individually. By organizing data into a visual graph, we open the subject to analysis on different levels. Art History represents the whole of human history and should be viewed at both micro and macro scales.
### Work Distribution
- Cindy Ngo: UI/UX, GitHub Repo, Graph Implementation, DFS algorithm
- Jacob Mass: Graph Display, Graph Implementation
- Neha Kallamvalli: API Implementation, Graph Implementation, BFS algorithm
### Data Structures
- Graphs
- Java HashMap
- ArrayList
- Queues
### References
- <a href="https://github.com/harvardartmuseums/api-docs" target="blank">Harvard Art Museum API</a>
- <a href="https://sojamo.de/libraries/controlP5/" target="blank">ControlP5 Library</a>
- <a href="https://docs.oracle.com/javase/7/docs/api/" target="blank">Java API Library</a>
- <a href="https://processing.org/reference/" target="blank">Processing</a>

## Core Mechanics
Graph Type Selection: Users can choose different vertex and edge implementations. In the UI there are options for examining paintings by Culture, Time Period, or All. Then, users can select edge relationships such as Color and Title.

BFS: Users can explore the graph level by level. We implemented the BFS using a Queue data structure.

DFS: Users can explore the graph branch by branch. This was implemented using a Vertex iterator and a recursive approach.

Art Display: We implemented a display that showcases images of actual art pieces from the Harvard Art Museum. The user can search a specific art piece and will be shown pieces related by the selected relationship.
## Conclusions
A major challenge our team faced was how to work collaboratively on this project. We planned to use Processing 3 which lacked support for version control and extensions for collaboration. To compensate for this, we used Visual Studio Code extensions for GitHub and LiveShare. However, we still had to use Processing 3 since Visual Studio Code lacked debugging tools for the program.​

One change we could make is the tools and technologies that we chose. Although the pro to using Processing 3 includes an easy combination of Front End and Back End implementation, we had to sacrifice easy collaboration and debugging in order to make it work.

![alt text](/assets/work/arthub/demo.jpeg "Arthub final product")

<button>
  <a href="https://github.com/cindyngo44/2D-Art-Museum" target="blank">Github</a>
</button>


