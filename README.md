# Mining Temporal Networks
### Tutorial proposed for the Web Conference 2024

 In World Wide Web (WWW) systems, networks (or graphs) serve as a fundamental 
 tool for representing,  analyzing, and understanding linked data, providing 
 significant insights into the underlying systems. Naturally, most real-world 
 systems have inherent temporal information, e.g., interactions in social 
 networks occur at specific moments in time and last for a certain period.
Temporal networks, i.e., network data modeling temporal information, enable 
 novel and fundamental discoveries about the underlying systems they model, 
 otherwise not captured by the static network model (i.e., networks not considering 
 such temporal information).
    
In this tutorial, we present state-of-the-art models and algorithmic techniques 
for mining temporal networks that can provide precious insights into a plethora 
of web-related applications. We describe how temporal networks can be used to 
extract novel information, especially in web-related network data, and highlight 
the discoveries (and challenges) that arise when modeling temporal information 
compared to traditional static network-based approaches. We first overview 
different temporal network models. We then show how such powerful models can be 
leveraged to extract novel insights through suitable mining primitives. In 
particular, we present recent advances addressing most foundational problems 
for temporal network mining---ranging from the computation of temporal centrality 
measures, temporal motif counting, and temporal communities to bursty events and 
anomaly detection. 

#### Teaser Video
<a href="http://www.youtube.com/watch?feature=player_embedded&v=wJ8gwGiDz6E" target="_blank">
 <img src="http://img.youtube.com/vi/wJ8gwGiDz6E/mqdefault.jpg" alt="Watch the teaser video" width="360" height="160" />
</a>


#### Previous Editions
[Website of the previous editions at KDD 2019 and the EDBT19 summer school.](https://rozensp.github.io/KDD19-tutorial-temporal/)

## Tutorial Content

**Part I: Introduction**
* Motivation and application areas.
* Main definitions and different types of temporal networks

* Models of temporal networks
	* Representation of temporality: 
	static networks with aggregated temporal information
	dynamic and time-evolving networks with sequential updates
	sequences of network snapshots
	sequences of interactions with meta information

	* Combinatorial models: multi-graphs, labeled graphs, sets of temporal edges, temporal hypergraphs
    * Statistical models: generative models and parameter fitting
	dynamical processes

* Algorithmic approaches 

	* Streaming model, sliding-window model, sequential updates
	* Theoretical foundations of network analysis


**Part II: Mining temporal networks A: connectivity, temporal properties, centrality, communities** 

* Connectivity, temporal walks and paths, reachability 
* Temporal properties: burstiness, temporal clustering coefficient, temporal efficiency, topological overlap, etc.
* Centrality measures
* Temporal cores, communities, and dense temporal subnetworks
* Measures of regime change in temporal networks, rules of evolution, etc.


**Part III: Mining temporal networks B: patterns, events, diffusion, random networks**

* Temporal patterns: trees, motifs, etc.
* Frequent patterns, episodes and subgraphs
* Event detection and structural prediction
* Diffusion and spreading
* Synthetic and random network

**Tools and code libraries**\
**Challenges, open problems, and trends** 


## Slides and links to relevant papers

Coming soon.

## Tutors

### Aristides Gionis 
Aristides Gionis is a professor in the department of Division of 
Theoretical Computer Science at KTH Royal Institute of Technology in Stockholm, Sweden.
He has been a fellow in the ISI foundation, Turin, and a visiting professor in the University of Rome. His previous appointment was with Yahoo! Research, Barcelona, where he has
been a senior research scientist and group leader. He obtained his
PhD in 2003 from Stanford University, USA. 
He is currently serving as an action editor in the 
Data Management and Knowledge Discovery journal (DMKD), 
and an associate editor in the ACM Transactions on the Web (TWEB). 
He has contributed in several areas of data science, such as algorithmic data
analysis, web mining, social-media analysis, data clustering, and
privacy-preserving data mining. His current research is funded by
by the European Commission with an ERC Advanced grant
(REBOUND) and with RIA project SoBigData++, 
and by the Wallenberg AI, Autonomous Systems and Software Program (WASP) in Sweden.
Aristides Gionis has presented several tutorials on graph mining and web
mining in conferences such as the 
Web Conference (2008, 2018, 2020, 2021, and 2022), 
KDD (2013, 2015, 2018, and 2019), 
ECML PKDD (2008, 2013, and 2015), 
IJCAI (2011 and 2022), 
as well as in many summer schools, 
including the EDBT Summer School 2019 and the Hi! Paris Data Science Summer School 2022.

### Lutz Oettershagen
Lutz Oettershagen is a postdoctoral researcher in the Division of  
Theoretical Computer Science at KTH Royal Institute of Technology in 
Stockholm, Sweden. He has been a postdoctoral researcher at the University 
of Bonn in Germany, where he also obtained his PhD. He obtained his master's 
degree at the TU University of Dortmund. His main research interests are 
algorithmic data analysis and data mining on temporal networks, focusing 
on social networks. In recent works, he covers temporal centrality measures, 
community search, and tie strength inference in temporal networks.


### Ilie Sarpe

Ilie Sarpe is a postdoctoral researcher in the Division of Theoretical 
Computer Science at KTH Royal Institute of Technology in Stockholm, Sweden. 
He obtained his PhD in Information Engineering from the University of Padova, 
Italy where he also earned his MSc in 2023 and 2019 respectively. His research 
interests focus on the development of scalable algorithms with rigorous 
theoretical guarantees for data mining primitives, and randomized algorithms. 
In particular, recently he focused on efficient algorithms with probabilistic 
guarantees for problems related to collecting patterns and centrality measures 
in temporal networks.


