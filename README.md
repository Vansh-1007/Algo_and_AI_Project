# Analyzing Zachary Karate Dataset Using NetworkX

This project explores the **Zachary Karate Club** dataset to analyze its social network using the NetworkX library in Python. The dataset, representing relationships among 34 members of a university karate club, was collected by Wayne W. Zachary in 1977. It includes 78 edges showcasing interactions among members, and highlights the club's division into two factions due to internal conflicts. 

## Table of Contents
- [Project Objectives](#project-objectives)
- [Dataset Overview](#dataset-overview)
- [Key Analyses](#key-analyses)
- [Visualization](#visualization)
- [Libraries Used](#libraries-used)
- [Results and Findings](#results-and-findings)
- [Files in the Project](#files-in-the-project)
- [How to Run the Code](#how-to-run-the-code)
- [References](#references)

## Project Objectives
1. Construct the network graph for the dataset.
2. Analyze the centrality metrics to identify key members and their roles:
   - Degree Centrality
   - Betweenness Centrality
   - Closeness Centrality
   - Eigenvector Centrality
3. Detect communities using:
   - Girvan-Newman Algorithm
   - Louvain Method
4. Simulate real-world network dynamics using:
   - Watts-Strogatz Model
   - Barabási-Albert Model
5. Visualize network structure to highlight clustering, influential members, and community divisions.

## Dataset Overview
- **Nodes**: 34 (representing members)
- **Edges**: 78 (representing relationships)
- The dataset reflects the division into two factions resulting from internal conflicts.

## Key Analyses
1. **Centrality Measures**:
   - **Degree Centrality**: Identifies the most connected nodes.
   - **Betweenness Centrality**: Highlights nodes that act as bridges.
   - **Closeness Centrality**: Measures accessibility to others.
   - **Eigenvector Centrality**: Reflects influence based on connections to other central nodes.

2. **Community Detection**:
   - Girvan-Newman Algorithm: Splits the network iteratively by removing edges with the highest betweenness.
   - Louvain Method: Optimizes modularity to detect cohesive subgroups.

3. **Clustering Analysis**:
   - Local and global clustering coefficients to understand node-level and network-level cohesiveness.

4. **Path Analysis**:
   - Shortest and average path lengths to measure connectivity and communication efficiency.

5. **Network Models**:
   - **Watts-Strogatz Model**: Simulates small-world properties.
   - **Barabási-Albert Model**: Explores scale-free network characteristics.

## Visualization
- Graphs were visualized using Matplotlib and NetworkX to depict:
  - Node and edge attributes (e.g., centrality scores, clustering coefficients).
  - Community structures and network dynamics.

## Libraries Used
- **Python**: 3.x
- **NetworkX**: For graph construction and analysis.
- **Matplotlib**: For static visualizations.
- **Plotly**: For interactive graphs.

## Results and Findings
- **Central Figures**:
  - Node 33: Highest Degree Centrality, Katz Centrality, and PageRank.
  - Node 0: High Betweenness and Closeness Centrality.
- **Community Structure**:
  - The club split into two factions, confirmed through community detection algorithms.
- **Clustering**:
  - High clustering coefficients for several nodes, indicating tightly-knit subgroups.
- **Model Simulations**:
  - The Watts-Strogatz and Barabási-Albert models highlighted the network's small-world and scale-free characteristics.

## Files in the Project
1. **report.pdf**: Contains the detailed project report and findings.
2. **Graph_Social_Networks_Codes.ipynb**: Jupyter Notebook with the Python code for analyzing the dataset.
3. **Visualization.ipynb**: Jupyter Notebook with additional visualizations for the dataset.
4. **Project_ppt.pdf**: Presentation summarizing the project and its outcomes.

## How to Run the Code
Open the following files in Jupyter Notebook or Google Colab:
- `Graph_Social_Networks_Codes.ipynb`
- `Visualization.ipynb`

Execute the cells step-by-step to generate the analysis and visualizations.

## References
1. [Zachary’s Karate Club Dataset](https://networkdata.ics.uci.edu/netdata/html/zacharyKarate.html)
2. Rogers, I. (2002). *The Google PageRank Algorithm and How It Works*.
3. Wikipedia contributors. *HITS Algorithm*, *Social Network Analysis*.
