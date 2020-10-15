Between winter 79' and autumn 80' prof. dr hab. Terelak stayed on [Arctowski research station](https://en.wikipedia.org/wiki/Henryk_Arctowski_Polish_Antarctic_Station) and gathered data about scientists' social interactions. Now, in the advent of long-term manned space missions it is especially valuable to analyze the data and learn from it.

In [this Jupyter notebook](https://github.com/marcindahlen/Antarctica_research_2020/blob/master/notebook.ipynb) I performed some basic summary statistics about the data I received.

I've transformed the data from point coordinates marked on charts to distances. This unfortunately has caused the loss of the plausible patterns people used to mark their opinions. With the distances organized by people by sessions, I've looked at how those changed through time, I've created sample graphs of parallel (and mutual) relations and used the graphs to get closeness centralities. Finally, I've plotted a graph defined by mean closeness centralities across all sessions, and peeked into possible groups of people. Done all this, I've tried to come with some insights from what I've learned.

Summary of what I've done:
1. Load the data from excel as-is
1. Define objects 'Session' and 'Person' to hold the data in useful form, organised by sessions, or by men
1. Find general tendency how people marked other on charts during sessions
1. Find general tendency how people were marked by others
1. Create weighted graphs of relations, one for each session for futher use
1. Find how graph centrality changed over the sessions
1. Define and investigate the summary graph
1. How do sessions' graphs vary?
1. Find what groups did people created
1. Who was most infuential among the men?
1. How one's view about others shaped the view others had about him?
1. A look on statistical significances
1. Summary and insights