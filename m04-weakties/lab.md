# Network visualization

In this assignment, you will play with network visualization tools: Gephi and Cytoscape. Both software can not only visualize networks but also analyze them to some extent. You can use either one of them, but feel free to play with both. You may want to try  Gephi first, and then Cytoscape if you have trouble installing Gephi.

<img src="https://gephi.org/images/logo.png" alt="Gephi logo" style="height:100px;"/>
<img src="https://cytoscape.org/images/logo/Cytoscape_3.png" alt="Cytoscape logo" style="height:100px;"/>

## Gephi

Gephi became popular with its fast layout algorithms and powerful functionalities. However, it is currently not well maintained. As a result, the installation can be problematic, particularly in recent systems. There are some troubleshooting tips in the [course wiki](https://github.com/yy/netsci-course/wiki/Gephi).

You can download and install Gephi: <https://gephi.org/>. The following is a tutorial made by a previous AI, Nathaniel.

[Gephi tutorial](https://youtu.be/MtgIQP0g5Hs)

Depending upon what version of Gephi you use the location of some buttons and tabs may vary, but the general functionality is roughly the same. If you want to know more about Gephi or what file formats it can read/write you can visit their [documentation page](https://gephi.org/users/).

## Cytoscape

As you can see from the name, Cytoscape is more geared towards biological networks because it was developed for biological network analysis. Still, it can visualize all kinds of networks.

Additionally, it does not have many built-in network analysis functionalities. Instead it uses plug-in system and many plug-ins can be installed and used.

Cytoscape is sustained by a larger community and federal funding, so it is more stable than Gephi in many ways. You can download it at [http://www.cytoscape.org/](http://www.cytoscape.org/) and check out the tutorials at: [https://github.com/cytoscape/cytoscape-tutorials/wiki](https://github.com/cytoscape/cytoscape-tutorials/wiki).

## Assignment

We'll use the Les Miserables graph, which can be downloaded from: [http://www-personal.umich.edu/~mejn/netdata/](http://www-personal.umich.edu/~mejn/netdata/). This site has other graphs which you can download. They are already in a format that Gephi or Cytoscape will recognize (`.net`, `.gexf`, `.gml`, etc).

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
