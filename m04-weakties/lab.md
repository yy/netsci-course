For this assignment we will be introducing you to two network visualization tools, Gephi and Cytoscape.

Gephi can calculate statistics of interest about a graph and can produce pretty visualizations quickly. The downside is that it's currently not well maintained. As a result, the installation has become problematic, particularly in the recent systems including Windows 10 and MacOS 10.12+. There are some troubleshooting tips in the [course wiki](https://github.com/yy/netsci-course/wiki/Gephi).

You can download and install Gephi (For Windows users who have trouble installing, see the end of this assignment for one possible solution): https://gephi.org/. The following is a tutorial made by a previous AI, Nathaniel.

[gephi tutorial.mp4](https://iu.instructure.com/courses/1774393/files/86775833/download?wrap=1)

Depending upon what version of Gephi you use the location of some buttons and tabs may vary, but the general functionality is roughly the same. If you want to know more about Gephi or what file formats it can read/write you can visit their [documentation page](https://gephi.org/users/). 

Cytoscape is developed by biologists & bioinformaticians and thus geared towards biological networks. Additionally, it does not have many network analysis functionalities. However, it is more stable and sensible than Gephi in many ways. You can download it at [http://www.cytoscape.org/](http://www.cytoscape.org/) and check out the tutorials at: [https://github.com/cytoscape/cytoscape-tutorials/wiki](https://github.com/cytoscape/cytoscape-tutorials/wiki). 

You can use either of these for the assignment. I would recommend trying Gephi first, and use Cytoscape if you have trouble installing Gephi.

We'll use the Les Miserables graph, which can be downloaded from: [http://www-personal.umich.edu/~mejn/netdata/](http://www-personal.umich.edu/~mejn/netdata/). This site has other graphs which you can download and use with Gephi. They are already in a format that Gephi will recognize (.net, .gexf, .gml, etc). 

Once you have the Les Miserables graph do the following: 
1. Load the graph into Gephi/Cytoscape as an undirected graph.
2. Calculate and record the number of nodes, number of edges, average degree, average clustering coefficient, and average path length of the graph.
3. Save a plot of the degree distribution of the nodes. Note: if you use Cytoscape, you may need to do this step in networkx.
4. Then, select a graph layout that you think best visualizes the graph and save it.
5. Create a new Jupyter notebook and use the [random graph generator tool](https://networkx.github.io/documentation/stable/reference/generated/networkx.generators.random_graphs.erdos_renyi_graph.html) introduced in the last assignment to create a random graph with the same number of nodes and about the same average degree and number of edges as the real graph. Please set the random seed as `seed=42`.
6. Save this random graph to a file format that Gephi/Cytoscape can read (see [this page](https://networkx.github.io/documentation/stable/reference/readwrite/index.html) for Networkx read/write functions) and perform steps 1-4 with this new graph. You can save it as pajek (.net), gml, or gexf.

You should then answer the following questions:
1. How do the degree distributions of the real graph and random graph compare? Explain any differences or similarities you see and consider why they might exist.
2. Is the real graph more clustered or less than the random one? What might this tell you about the organizing principles of the real graph?
3. Does the real graph exhibit the small-world property? 

When complete, compile your results, figures, and analysis into a `.pdf` file and upload that, along with the Jupyter notebook you used to generate the random graph exported to a `.html` file.