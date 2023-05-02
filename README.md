# Network_Science-

Part 1 - Network_science 1 

Loading and Preprocessing the Data: You loaded the Enron email dataset and preprocessed it by removing unnecessary characters and converting the data types.

Analyzing Network Properties:

You loaded the Enron email network into a graph data structure using the NetworkX library.
You performed various analyses on the network properties, including clustering coefficient, shortest path length, power law degree distribution, and betweenness centrality.
You visualized the betweenness distribution and profile to understand the role of links in connecting different parts of the network.
Fitting a Gaussian Distribution:

You generated a G(N, p) network and fitted a Gaussian distribution to its degree distribution using the maximum likelihood method.
You compared the quality of the fitting and visualized the ensemble degree distribution, the fitted Gaussian distribution, and the graph's degree distribution.
Manipulating and Analyzing Networks:

You generated a Watts-Strogatz network and converted it into a directed graph.
You randomly deleted half of the links in the network and analyzed the changes in the in-degree and out-degree distributions.
You explained the differences observed in the distributions before and after link removal.
Comparing Network Types:

You generated a Barabasi-Albert network and a G(N, L) network with similar average degrees.
You estimated the probability that a randomly selected node has at least 3 times the average degree in each network.
You discussed the meaning of the results, highlighting the presence of highly connected hubs in the Barabasi-Albert network.


Part 2 - network Science 

Network Analysis and Robustness Assessment:

Conducted network analysis on a given network using NetworkX library.
Assessed the robustness of the network by measuring the size of the giant component as nodes were removed.
Compared the robustness of the original network to a randomized version using matplotlib and seaborn for visualization.
Community Detection using Girvan-Newman Algorithm:

Applied the Girvan-Newman algorithm available in NetworkX to identify communities within the network.
Determined the best partition (community structure) based on modularity measure.
Analyzed the number of communities in the best partition and highlighted the community structure of the network.
Disease Spread Simulation:

Simulated the spread of a disease in the network using the SIRS model.
Created plots to visualize the disease spread for different initial infected nodes located in communities of varying sizes.
Conducted multiple simulation runs and averaged the results to observe the average behavior of disease spread within each community.
Avalanche Size Distribution:

Analyzed the distribution of avalanche sizes using a model that considers the failure of nodes in response to the failure of their neighbors.
Calculated the distribution of avalanche sizes for the network and visualized it using a histogram.
Discussed the implications of the distribution in terms of network robustness and compared it to a random network with the same degree distribution.
