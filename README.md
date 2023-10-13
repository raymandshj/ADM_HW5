# ADM_HW5

**Marvel Superheros Graph**

## 1. Introduction

### Project Overview

In this project, we will analyze networks of superheroes and comics. We will create two different graphs based on the provided datasets and implement various functionalities to extract valuable insights from these networks.

### Data Description

We have three main datasets:

- **nodes.csv**: Contains information about nodes (heroes and comics).
- **edges.csv**: Defines relationships between heroes and comics.
- **hero-network.csv**: Contains information about hero collaborations.

### Data Preprocessing

To ensure consistency in the data, we performed the following preprocessing steps:

- Removed extra spaces and slashes from hero names.
- Addressed naming inconsistencies between datasets.
- Eliminated self-loop entries.

## 2. Backend Implementation

### Functionality 1 - Extract the Graph's Features

This functionality calculates and reports various features of the graph, including the number of nodes, number of collaborations, degree distribution, network density, hubs, and more.

### Functionality 2 - Find Top Superheroes

This functionality allows users to find top superheroes based on centrality measures such as Betweenness, PageRank, Closeness Centrality, and Degree Centrality.

### Functionality 3 - Shortest Ordered Route

Users can find the shortest walk of comics required to get from one hero to another while preserving the order of heroes.

### Functionality 4 - Disconnecting Graphs

This functionality calculates the minimum number of links needed to disconnect the original graph into two disconnected subgraphs.

### Functionality 5 - Extracting Communities

Users can identify communities within the first graph and calculate the minimum number of edges required to form these communities.

## 3. Frontend Implementation

We present visualizations to provide insights based on the implemented functionalities.

### Visualization 1 - Visualize Network Features

Visualizations include tables and plots depicting network features such as density, degree distribution, hubs, and more.

### Visualization 2 - Visualize Centrality Measures

This visualization presents centrality measures and the requested metric values for the given node, providing insights into the network structure.

### Visualization 3 - Visualize Shortest Ordered Route

The shortest walk from one hero to another is displayed on the graph, and the nodes and edges in the shortest walk are identified.

### Visualization 4 - Visualize Disconnected Graph

This visualization shows the original graph, the graph after removing links, and identifies the two disconnected nodes.

### Visualization 5 - Visualize Communities

Users can explore communities in the first graph and see the effect of removing edges to form these communities. The communities are plotted within the network structure.

## 4. Command Line Question

A set of command-line questions provide insights into the network's characteristics, including popular hero pairs, comics per hero, and the average number of heroes in comics.

## Contributions

- Raymand Shojaie Aghabalaghe
- Gizem Goker
