For this assignment you will be using Gephi or Cytoscape to detect communities in a couple real-world graphs. 

This tutorial video does a good job of explaining how you can use Gephi to detect community structure: [https://www.youtube.com/watch?v=7LMnpM0p4cM](https://www.youtube.com/watch?v=7LMnpM0p4cM)

For the first part of the assignment download the [American college football network](http://www-personal.umich.edu/~mejn/netdata/) and use it to complete the assignment (note: the force atlas layout is usually pretty good for visualizing networks with community structure).

1. Adjust the resolution of the community detection algorithm and get a sense of what communities are formed at different resolutions. Pick a resolution that makes sense to you. Give a physical interpretation of the communities and justify your choice for the resolution parameter.
2. Calculate the betweenness centrality for the nodes in the network and create a visualization which shows both the betweenness centrality and community membership (save this figure). How are betweenness centrality and community structure related?

Now download a graph of your choosing (this can be a network you are investigating for you final project):
1. Find an appropriate resolution for detecting meaningful communities in the network and adjust the node layout accordingly. Does the network have a distinct community structure? If so, what do these communities represent and how do you think they were formed? If not, why do think that structure is lacking?
2. Pick another centrality measure and create (and save) a visualization that captures the community membership along with this centrality measure. Explain what relationships (or lack thereof) you see between the centrality measure you chose and community structure. Can you relate your explanations back to the real-world elements that make-up the network?

For Cytoscape users: you need to download some plugins by going to "Apps" -> "App manager", or go to the app store [https://apps.cytoscape.org/](https://apps.cytoscape.org/), download the installation file and choose "App manager" -> "manual install". Choose a plugin that you consider to be good and follow the instructions above. You can bring in other tools (networkx, etc) if necessary. Once you are complete compile your results (figures and responses) into a single PDF file and submit that to Canvas.
