### Antarctic Spatial Sociometry Analysis

Between winter 79' and autumn 80' prof. dr hab. Terelak stayed on [Arctowski research station](https://en.wikipedia.org/wiki/Henryk_Arctowski_Polish_Antarctic_Station) and gathered data about scientists' social interactions. Now, in the advent of long-term manned space missions it is especially valuable to analyze the data and learn from it.

In [this Jupyter notebook](https://github.com/marcindahlen/Antarctica_research_2020/blob/master/notebook.ipynb) I performed some basic summary statistics about the data I received.

The notebook investigates three primary questions:

#### 1. Temporal sensitivity
Are spatial relation maps more temporally responsive than classical nomination-based sociometric status measures?

#### 2. Event responsiveness
Do spatial relation changes align with documented interpersonal tensions, subgroup formation, and social events observed during the expedition?

#### 3. Spatial-only relational affordances
What additional dyadic and network-level information becomes accessible when interpersonal relations are represented as continuous spatial structures rather than categorical sociometric statuses?


The analyses combine two complementary archival datasets collected repeatedly during the expedition:

#### Spatial sociometry ("relation maps")
Participants marked all other crew members on two-dimensional charts according to perceived interpersonal closeness.  
The notebook transforms these point placements into:

- pairwise interpersonal distances,
- continuous closeness measures,
- weighted directed relational networks,
- temporal relational trajectories.

#### Nomination-based sociometry
The expedition also used a classical sociometric nomination procedure based on the Sympathy–Antipathy Plebiscite (Pilkiewicz, 1973a,b), producing repeated sociometric status categories over time.

Unlike the spatial data, the surviving nomination data are available only as aggregated person-session sociometric outcomes rather than full dyadic matrices.



*Please notice that sometimes Github doesn't load jupyter notebook properly, and the notebook needs to be refreshed several times.*
