# Mining Temporal Networks
### A Tutorial at the [ACM Web Conference 2024](https://www2024.thewebconf.org/)

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


<a href="http://www.youtube.com/watch?feature=player_embedded&v=wJ8gwGiDz6E" target="_blank">
 <img src="http://img.youtube.com/vi/wJ8gwGiDz6E/mqdefault.jpg" alt="Watch the teaser video" width="360" height="160" />
</a>


#### [Previous Editions.](https://rozensp.github.io/KDD19-tutorial-temporal/)


## Tutorial Content

**Part I: Introduction and Movivation**
* Motivation and application areas.
* Main definitions and different types of temporal networks
* Models of temporal networks
* Algorithmic approaches 

**Part II: Mining temporal networks A** 
* Connectivity, temporal walks and paths, reachability 
* Temporal properties
* Centrality measures
* Temporal cores decomposition

**Part III: Mining temporal networks B**
* Temporal communities
* Temporal patterns: trees, motifs, etc.
* Event detection and structural prediction
* Diffusion and spreading
* Synthetic and random network

**Tools and code libraries**\
**Challenges, open problems, and trends** 


## Slides 

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

[Website](https://www.kth.se/profile/argioni)


### Lutz Oettershagen
Lutz Oettershagen is a postdoctoral researcher in the Division of 
Theoretical Computer Science at KTH Royal Institute of Technology in 
Stockholm, Sweden. He has been a postdoctoral researcher at the University 
of Bonn in Germany, where he also obtained his PhD. He obtained his master's 
degree at the TU University of Dortmund. His main research interests are 
algorithmic data analysis and data mining on temporal networks, focusing 
on social networks. In recent works, he covers temporal centrality measures, 
community search, and tie strength inference in temporal networks.

[Website](https://lutzoe.github.io/)


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

[Website](https://iliesarpe.github.io/)


## Relevant Papers

- **Measures of concurrency in networks and the spread of infectious disease**.  
 Kretzschmar, Mirjam and Morris, Martina.  
 Mathematical biosciences. 1996.  
[10.1016/0025-5564(95)00093-3](https://doi.org/10.1016/0025-5564(95)00093-3)
- **NetScope: traffic engineering for IP networks**.  
 A. Feldmann and A. Greenberg and C. Lund and N. Reingold and J. Rexford.  
 IEEE Network. 2000.  
[10.1109/65.826367](https://doi.org/10.1109/65.826367)
- **Dynamical random graphs with memory**.  
 Turova, Tatyana S.  
 Physical Review E. 2002.  
[10.1103/physreve.65.066102](https://doi.org/10.1103/physreve.65.066102)
- **Complexity of connected components in evolving graphs and the computation of multicast trees in dynamic networks**.  
 Bhadra, Sandeep and Ferreira, Afonso.  
 Ad-Hoc, Mobile, and Wireless Networks: ADHOC-NOW2003. 2003.  
[10.1007/978-3-540-39611-6_23](https://doi.org/10.1007/978-3-540-39611-6_23)
- **Group formation in large social networks: membership, growth, and evolution**.  
 Backstrom, Lars and Huttenlocher, Dan and Kleinberg, Jon and Lan, Xiangyang.  
 Proceedings of the 12th ACM SIGKDD international conference on Knowledge discovery and data mining. 2006.  
[10.1145/1150402.1150412](https://doi.org/10.1145/1150402.1150412)
- **Mining graph data**.  
 Cook, Diane J and Holder, Lawrence B.  
 . 2006.  
[10.1002/0470073047](https://doi.org/10.1002/0470073047)
- **Recovering temporally rewiring networks: A model-based approach**.  
 Guo, Fan and Hanneke, Steve and Fu, Wenjie and Xing, Eric P.  
 Proceedings of the 24th international conference on Machine learning. 2007.  
[10.1145/1273496.1273537](https://doi.org/10.1145/1273496.1273537)
- **Structure prediction in temporal networks using frequent subgraphs**.  
 Lahiri, Mayank and Berger-Wolf, Tanya Y.  
 2007 IEEE Symposium on Computational Intelligence and Data Mining. 2007.  
[10.1109/cidm.2007.368850](https://doi.org/10.1109/cidm.2007.368850)
- **Burstiness and memory in complex systems**.  
 Goh, K-I and Barab\'asi, A-L.  
 Europhysics Letters. 2008.  
[10.1209/0295-5075/81/48002](https://doi.org/10.1209/0295-5075/81/48002)
- **Microscopic evolution of social networks**.  
 Leskovec, Jure and Backstrom, Lars and Kumar, Ravi and Tomkins, Andrew.  
 Proceedings of the 14th ACM SIGKDD international conference on Knowledge discovery and data mining. 2008.  
[10.1145/1401890.1401948](https://doi.org/10.1145/1401890.1401948)
- **Mining graph evolution rules**.  
 Berlingerio, Michele and Bonchi, Francesco and Bringmann, Bj\"orn and Gionis, Aristides.  
 ECML PKDD. 2009.  
[10.1007/978-3-642-04180-8_25](https://doi.org/10.1007/978-3-642-04180-8_25)
- **Temporality in link prediction: Understanding social complexity**.  
 Potgieter, Anet and April, Kurt A and Cooke, Richard JE and Osunmakinde, Isaac O.  
 Emergence: Complexity \& Organization (E: CO). 2009.  
[10.1007/978-3-030-10767-3_6](https://doi.org/10.1007/978-3-030-10767-3_6)
- **Temporal distance metrics for social network analysis**.  
 Tang, John and Musolesi, Mirco and Mascolo, Cecilia and Latora, Vito.  
 Proceedings of the 2nd ACM workshop on Online social networks. 2009.  
[10.1145/1592665.1592674](https://doi.org/10.1145/1592665.1592674)
- **Graph data management and mining: A survey of algorithms and applications**.  
 Aggarwal, Charu C and Wang, Haixun.  
 Managing and mining graph data. 2010.  
[10.1007/978-1-4419-6045-0_2](https://doi.org/10.1007/978-1-4419-6045-0_2)
- **Dynamic model of time-dependent complex networks**.  
 Hill, Scott A and Braha, Dan.  
 Physical Review E. 2010.  
[10.1103/physreve.82.046105](https://doi.org/10.1103/physreve.82.046105)
- **Mining temporal subgraph patterns in heterogeneous information networks**.  
 Hsieh, Hsun-Ping and Li, Cheng-Te.  
 2010 IEEE Second International Conference on Social Computing. 2010.  
[10.1109/socialcom.2010.47](https://doi.org/10.1109/socialcom.2010.47)
- **Structure and evolution of online social networks**.  
 Kumar, Ravi and Novak, Jasmine and Tomkins, Andrew.  
 Link mining: models, algorithms, and applications. 2010.  
[10.1007/978-3-319-05164-2_2](https://doi.org/10.1007/978-3-319-05164-2_2)
- **Small-world behavior in time-varying graphs**.  
 Tang, John and Scellato, Salvatore and Musolesi, Mirco and Mascolo, Cecilia and Latora, Vito.  
 Physical Review E. 2010.  
[10.1103/physreve.81.055101](https://doi.org/10.1103/physreve.81.055101)
- **Frequent subgraph discovery in dynamic networks**.  
 Wackersreuther, Bianca and Wackersreuther, Peter and Oswald, Annahita and B\"ohm, Christian and Borgwardt, Karsten M.  
 Proceedings of the Eighth Workshop on Mining and Learning with Graphs. 2010.  
[10.1145/1830252.1830272](https://doi.org/10.1145/1830252.1830272)
- **Communication motifs**.  
 Qiankun Zhao and Yuan Tian and Qi He and Nuria Oliver and Ruoming Jin and Wang-Chien Lee.  
 Proceedings of the 19th ACM international conference on Information and knowledge management - CIKM \textquotesingle10. 2010.  
[10.1145/1871437.1871694](https://doi.org/10.1145/1871437.1871694)
- **Emergence of bursts and communities in evolving weighted networks**.  
 Jo, Hang-Hyun and Pan, Raj Kumar and Kaski, Kimmo.  
 PloS one. 2011.  
[10.1371/journal.pone.0022687](https://doi.org/10.1371/journal.pone.0022687)
- **Temporal motifs in time-dependent networks**.  
 Lauri Kovanen and Márton Karsai and Kimmo Kaski and János Kertész and Jari Saramäki.  
 J. Stat. Mech. (2011) P11005. 2011.  
[10.1088/1742-5468/2011/11/P11005](https://doi.org/10.1088/1742-5468/2011/11/P11005)
- **Time-varying graphs and dynamic networks**.  
 Casteigts, Arnaud and Flocchini, Paola and Quattrociocchi, Walter and Santoro, Nicola.  
 International Journal of Parallel, Emergent and Distributed Systems. 2012.  
[10.1080/17445760.2012.668546](https://doi.org/10.1080/17445760.2012.668546)
- **Temporal networks**.  
 Holme, Petter and Saram\"aki, Jari.  
 Physics reports. 2012.  
[10.1007/978-1-4614-7163-9_42-1](https://doi.org/10.1007/978-1-4614-7163-9_42-1)
- **Exploiting temporal network structures of human interaction to effectively immunize populations**.  
 Lee, Sungmin and Rocha, Luis EC and Liljeros, Fredrik and Holme, Petter.  
 PloS one. 2012.  
[10.1371/journal.pone.0036439](https://doi.org/10.1371/journal.pone.0036439)
- **Social networks on the Internet**.  
 Katarzyna Musia\l and Przemys\law Kazienko.  
 World Wide Web. 2012.  
[10.7238/rusc.v6i1.30](https://doi.org/10.7238/rusc.v6i1.30)
- **Influence maximization in continuous time diffusion networks**.  
 Rodriguez, Manuel Gomez and Sch\"olkopf, Bernhard.  
 arXiv preprint arXiv:1205.1682. 2012.  
[10.1145/2824253](https://doi.org/10.1145/2824253)
- **Survey and analysis of temporal link prediction in online social networks**.  
 Dhote, Yugchhaya and Mishra, Nishchol and Sharma, Sanjeev.  
 2013 International Conference on Advances in Computing, Communications and Informatics. 2013.  
[10.1109/icacci.2013.6637344](https://doi.org/10.1109/icacci.2013.6637344)
- **Epidemiologically optimal static networks from temporal network data**.  
 Holme, Petter.  
 PLoS computational biology. 2013.  
[10.1371/journal.pcbi.1003142](https://doi.org/10.1371/journal.pcbi.1003142)
- **Temporal motifs reveal homophily, gender-specific patterns, and group talk in call sequences**.  
 Lauri Kovanen and Kimmo Kaski and J\'anos Kert\'esz and Jari Saramäki.  
 Proceedings of the National Academy of Sciences. 2013.  
[10.1073/pnas.1307941110](https://doi.org/10.1073/pnas.1307941110)
- **Event detection in social media: A survey**.  
 Nurwidyantoro, Arif and Winarko, Edi.  
 International Conference on ICT for Smart Society. 2013.  
[10.1109/ictss.2013.6588106](https://doi.org/10.1109/ictss.2013.6588106)
- **Evolutionary network analysis: A survey**.  
 Aggarwal, Charu and Subbian, Karthik.  
 ACM Computing Surveys (CSUR). 2014.  
[10.1145/2601412](https://doi.org/10.1145/2601412)
- **Graph stream algorithms: a survey**.  
 McGregor, Andrew.  
 ACM SIGMOD Record. 2014.  
[10.1145/2627692.2627694](https://doi.org/10.1145/2627692.2627694)
- **Event detection in activity networks**.  
 Rozenshtein, Polina and Anagnostopoulos, Aris and Gionis, Aristides and Tatti, Nikolaj.  
 Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining. 2014.  
[10.1145/2623330.2623674](https://doi.org/10.1145/2623330.2623674)
- **Graph based anomaly detection and description: a survey**.  
 Akoglu, Leman and Tong, Hanghang and Koutra, Danai.  
 Data mining and knowledge discovery. 2015.  
[10.1007/s10618-014-0365-y](https://doi.org/10.1007/s10618-014-0365-y)
- **Modern temporal network theory: a colloquium**.  
 Holme, Petter.  
 The European Physical Journal B. 2015.  
[10.1140/epjb/e2015-60657-4](https://doi.org/10.1140/epjb/e2015-60657-4)
- **Maintaining sliding-window neighborhood profiles in interaction networks**.  
 Kumar, Rohit and Calders, Toon and Gionis, Aristides and Tatti, Nikolaj.  
 Joint European Conference on Machine Learning and Knowledge Discovery in Databases. 2015.  
[10.1007/978-3-319-23525-7_44](https://doi.org/10.1007/978-3-319-23525-7_44)
- **Core decomposition in large temporal graphs**.  
 Wu, Huanhuan and Cheng, James and Lu, Yi and Ke, Yiping and Huang, Yuzhen and Yan, Da and Wu, Hejun.  
 Big Data. 2015.  
[10.1109/bigdata.2015.7363809](https://doi.org/10.1109/bigdata.2015.7363809)
- **Network science**.  
 Barab\'asi, Albert-L\'aszl\'o and others.  
 . 2016.  
[10.1007/978-1-84996-396-1](https://doi.org/10.1007/978-1-84996-396-1)
- **Online social networks event detection: a survey**.  
 Cordeiro, M\'ario and Gama, Jo\~ao.  
 Solving Large Scale Learning Tasks. Challenges and Algorithms. 2016.  
[10.1007/978-3-319-41706-6_1](https://doi.org/10.1007/978-3-319-41706-6_1)
- **A survey of event detection techniques in online social networks**.  
 Goswami, Anuradha and Kumar, Ajey.  
 Social Network Analysis and Mining. 2016.  
[10.1007/s13278-016-0414-1](https://doi.org/10.1007/s13278-016-0414-1)
- **An introduction to temporal graphs: An algorithmic perspective**.  
 Michail, Othon.  
 Internet Mathematics. 2016.  
[10.1007/978-3-319-24024-4_18](https://doi.org/10.1007/978-3-319-24024-4_18)
- **Reconstructing an epidemic over time**.  
 Rozenshtein, Polina and Gionis, Aristides and Prakash, B Aditya and Vreeken, Jilles.  
 Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 2016.  
[10.1145/2939672.2939865](https://doi.org/10.1145/2939672.2939865)
- **Discovering topically-and temporally-coherent events in interaction networks**.  
 Xiao, Han and Rozenshtein, Polina and Gionis, Aristides.  
 Joint European Conference on Machine Learning and Knowledge Discovery in Databases. 2016.  
[10.1007/978-3-319-46227-1_43](https://doi.org/10.1007/978-3-319-46227-1_43)
- **Scalable temporal latent space inference for link prediction in dynamic social networks**.  
 Zhu, Linhong and Guo, Dong and Yin, Junming and Ver Steeg, Greg and Galstyan, Aram.  
 IEEE Transactions on Knowledge and Data Engineering. 2016.  
[10.1109/tkde.2016.2591009](https://doi.org/10.1109/tkde.2016.2591009)
- **Temporal Pattern Mining from Evolving Networks**.  
 Impedovo, Angelo and Loglisci, Corrado and Ceci, Michelangelo.  
 arXiv preprint arXiv:1709.06772. 2017.  
[10.1109/tpami.2023.3324799](https://doi.org/10.1109/tpami.2023.3324799)
- **Discovering Graph Temporal Association Rules**.  
 Mohammad Hossein Namaki and Yinghui Wu and Qi Song and Peng Lin and Tingjian Ge.  
 Proceedings of the 2017 ACM on Conference on Information and Knowledge Management. 2017.  
[10.1145/3132847.3133014](https://doi.org/10.1145/3132847.3133014)
- **Finding dynamic dense subgraphs**.  
 Rozenshtein, Polina and Tatti, Nikolaj and Gionis, Aristides.  
 ACM Transactions on Knowledge Discovery from Data (TKDD). 2017.  
[10.1145/3046791](https://doi.org/10.1145/3046791)
- **The network-untangling problem: From interactions to activity timelines**.  
 Rozenshtein, Polina and Tatti, Nikolaj and Gionis, Aristides.  
 Joint European Conference on Machine Learning and Knowledge Discovery in Databases. 2017.  
[10.1007/978-3-319-71249-9_42](https://doi.org/10.1007/978-3-319-71249-9_42)
- **Simplicial closure and higher-order link prediction**.  
 Austin R. Benson and Rediet Abebe and Michael T. Schaub and Ali Jadbabaie and Jon Kleinberg.  
 Proceedings of the National Academy of Sciences. 2018.  
[10.1073/pnas.1800683115](https://doi.org/10.1073/pnas.1800683115)
- **Methods for analyzing temporal networks**.  
 Polina Rozenshtein.  
 . 2018.  
[10.1109/jproc.2014.2361326](https://doi.org/10.1109/jproc.2014.2361326)
- **Stream graphs and link streams for the modeling of interactions over time**.  
 Latapy, Matthieu and Viard, Tiphaine and Magnien, Cl\'emence.  
 Social Network Analysis and Mining. 2018.  
[10.1007/s13278-018-0537-7](https://doi.org/10.1007/s13278-018-0537-7)
- **Persistent Community Search in Temporal Networks**.  
 Rong-Hua Li and Jiao Su and Lu Qin and Jeffrey Xu Yu and Qiangqiang Dai.  
 2018 IEEE 34th International Conference on Data Engineering (ICDE). 2018.  
[10.1109/icde.2018.00077](https://doi.org/10.1109/icde.2018.00077)
- **Graph summarization methods and applications: A survey**.  
 Liu, Yike and Safavi, Tara and Dighe, Abhilash and Koutra, Danai.  
 ACM Computing Surveys (CSUR). 2018.  
[10.1145/3186727](https://doi.org/10.1145/3186727)
- **A Chronological Edge-Driven Approach to Temporal Subgraph Isomorphism**.  
 Patrick Mackey and Katherine Porterfield and Erin Fitzhenry and Sutanay Choudhury and George Chin.  
 2018 IEEE International Conference on Big Data (Big Data). 2018.  
[10.1109/bigdata.2018.8622100](https://doi.org/10.1109/bigdata.2018.8622100)
- **Community discovery in dynamic networks: a survey**.  
 Rossetti, Giulio and Cazabet, R\'emy.  
 ACM Computing Surveys (CSUR). 2018.  
[10.1145/3172867](https://doi.org/10.1145/3172867)
- **Finding events in temporal networks: Segmentation meets densest-subgraph discovery**.  
 Rozenshtein, Polina and Bonchi, Francesco and Gionis, Aristides and Sozio, Mauro and Tatti, Nikolaj.  
 2018 IEEE International Conference on Data Mining (ICDM). 2018.  
[10.1007/s10115-019-01403-9](https://doi.org/10.1007/s10115-019-01403-9)
- **Reconstructing a cascade from temporal observations**.  
 Xiao, Han and Rozenshtein, Polina and Tatti, Nikolaj and Gionis, Aristides.  
 Proceedings of the 2018 SIAM International Conference on Data Mining. 2018.  
[10.1137/1.9781611975321.75](https://doi.org/10.1137/1.9781611975321.75)
- **Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks**.  
 Srijan Kumar and Xikun Zhang and Jure Leskovec.  
 Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining. 2019.  
[10.1145/3292500.3330895](https://doi.org/10.1145/3292500.3330895)
- **Sampling Methods for Counting Temporal Motifs**.  
 Paul Liu and Austin R. Benson and Moses Charikar.  
 Proceedings of the Twelfth ACM International Conference on Web Search and Data Mining. 2019.  
[10.1145/3289600.3290988](https://doi.org/10.1145/3289600.3290988)
- **On the enumeration of bicriteria temporal paths**.  
 Mutzel, Petra and Oettershagen, Lutz.  
 Theory and Applications of Models of Computation, TAMC. 2019.  
[10.1007/978-3-030-14812-6_32](https://doi.org/10.1007/978-3-030-14812-6_32)
- **Mining Temporal Networks**.  
 Polina Rozenshtein and Aristides Gionis.  
 Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining. 2019.  
[10.1145/3292500.3332295](https://doi.org/10.1145/3292500.3332295)
- **Finding events in temporal networks: segmentation meets densest subgraph discovery**.  
 Polina Rozenshtein and Francesco Bonchi and Aristides Gionis and Mauro Sozio and Nikolaj Tatti.  
 Knowledge and Information Systems. 2019.  
[10.1007/s10115-019-01403-9](https://doi.org/10.1007/s10115-019-01403-9)
- **TM-Miner: TFS-Based Algorithm for Mining Temporal Motifs in Large Temporal Network**.  
 Xiaoli Sun and Yusong Tan and Qingbo Wu and Baozi Chen and Changxiang Shen.  
 IEEE Access. 2019.  
[10.1109/access.2019.2911181](https://doi.org/10.1109/access.2019.2911181)
- **Mining Persistent Activity in Continually Evolving Networks**.  
 Caleb Belth and Xinyi Zheng and Danai Koutra.  
 Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining. 2020.  
[10.1145/3394486.3403136](https://doi.org/10.1145/3394486.3403136)
- **Algorithmic Aspects of Temporal Betweenness**.  
 Sebastian Bu\ss and Hendrik Molter and Rolf Niedermeier and Maciej Rymar.  
 Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining. 2020.  
[10.1145/3394486.3403259](https://doi.org/10.1145/3394486.3403259)
- **Span-core decomposition for temporal networks: Algorithms and applications**.  
 Galimberti, Edoardo and Ciaperoni, Martino and Barrat, Alain and Bonchi, Francesco and Cattuto, Ciro and Gullo, Francesco.  
 TKDD. 2020.  
[10.1145/3418226](https://doi.org/10.1145/3418226)
- **Motif discovery algorithms in static and temporal networks: A survey**.  
 Ali Jazayeri and Christopher C Yang.  
 Journal of Complex Networks. 2020.  
[10.1093/comnet/cnaa031](https://doi.org/10.1093/comnet/cnaa031)
- **Inferring temporal motifs for travel pattern analysis using large scale smart card data**.  
 Da Lei and Xuewu Chen and Long Cheng and Lin Zhang and Satish V. Ukkusuri and Frank Witlox.  
 Transportation Research Part C: Emerging Technologies. 2020.  
[10.1016/j.trc.2020.102810](https://doi.org/10.1016/j.trc.2020.102810)
- **Classifying dissemination processes in temporal graphs**.  
 Oettershagen, Lutz and Kriege, Nils M and Morris, Christopher and Mutzel, Petra.  
 Big Data. 2020.  
[10.1089/big.2020.0086](https://doi.org/10.1089/big.2020.0086)
- **Efficient top-k temporal closeness calculation in temporal networks**.  
 Oettershagen, Lutz and Mutzel, Petra.  
 2020 IEEE International Conference on Data Mining (ICDM). 2020.  
[10.1109/icdm50108.2020.00049](https://doi.org/10.1109/icdm50108.2020.00049)
- **Temporal graph kernels for classifying dissemination processes**.  
 Oettershagen, Lutz and Kriege, Nils M and Morris, Christopher and Mutzel, Petra.  
 Proceedings of the 2020 SIAM International Conference on Data Mining. 2020.  
[10.1137/1.9781611976236.56](https://doi.org/10.1137/1.9781611976236.56)
- **Efficient Sampling Algorithms for Approximate Temporal Motif Counting**.  
 Jingjing Wang and Yanhao Wang and Wenjun Jiang and Yuchen Li and Kian-Lee Tan.  
 Proceedings of the 29th ACM International Conference on Information \& Knowledge Management. 2020.  
[10.1145/3340531.3411862](https://doi.org/10.1145/3340531.3411862)
- **Thyme+: Temporal hypergraph motifs and fast algorithms for exact counting**.  
 Lee, Geon and Shin, Kijung.  
 2021 IEEE International Conference on Data Mining (ICDM). 2021.  
[10.1109/icdm51629.2021.00042](https://doi.org/10.1109/icdm51629.2021.00042)
- **Temporal Network Motifs: Models, Limitations, Evaluation**.  
 Penghang Liu and Valerio Guarrasi and A. Erdem Sariyuce.  
 IEEE Transactions on Knowledge and Data Engineering. 2021.  
[10.1109/tkde.2021.3077495](https://doi.org/10.1109/tkde.2021.3077495)
- **An efficient procedure for mining egocentric temporal motifs**.  
 Antonio Longa and Giulia Cencetti and Bruno Lepri and Andrea Passerini.  
 Data Mining and Knowledge Discovery. 2021.  
[10.1007/s10618-021-00803-2](https://doi.org/10.1007/s10618-021-00803-2)
- **Faster and Generalized Temporal Triangle Counting, via Degeneracy Ordering**.  
 Noujan Pashanasangi and C. Seshadhri.  
 Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery \& Data Mining. 2021.  
[10.1145/3447548.3467374](https://doi.org/10.1145/3447548.3467374)
- **Discovering Dense Correlated Subgraphs in Dynamic Networks**.  
 Giulia Preti and Polina Rozenshtein and Aristides Gionis and Yannis Velegrakis.  
 Advances in Knowledge Discovery and Data Mining. 2021.  
[10.1007/978-3-030-75762-5_32](https://doi.org/10.1007/978-3-030-75762-5_32)
- **OdeN: Simultaneous Approximation of Multiple Motif Counts in Large Temporal Networks**.  
 Ilie Sarpe and Fabio Vandin.  
 Proceedings of the 30th ACM International Conference on Information \& Knowledge Management. 2021.  
[10.1109/icdm54844.2022.00084](https://doi.org/10.1109/icdm54844.2022.00084)
- **PRESTO: Simple and Scalable Sampling Techniques for the Rigorous Approximation of Temporal Motif Counts**.  
 Ilie Sarpe and Fabio Vandin.  
 Proceedings of the 2021 SIAM International Conference on Data Mining (SDM). 2021.  
[10.1137/1.9781611976700.17](https://doi.org/10.1137/1.9781611976700.17)
- **A Comprehensive Survey on Graph Neural Networks**.  
 Zonghan Wu and Shirui Pan and Fengwen Chen and Guodong Long and Chengqi Zhang and Philip S. Yu.  
 IEEE Transactions on Neural Networks and Learning Systems. 2021.  
[10.1109/tnnls.2020.2978386](https://doi.org/10.1109/tnnls.2020.2978386)
- **Simple, strict, proper, happy: A study of reachability in temporal graphs**.  
 Casteigts, Arnaud and Corsini, Timoth\'ee and Sarkar, Writika.  
 International Symposium on Stabilizing, Safety, and Security of Distributed Systems. 2022.  
[10.1016/j.tcs.2024.114434](https://doi.org/10.1016/j.tcs.2024.114434)
- **Scalable Motif Counting for Large-scale Temporal Graphs**.  
 Zhongqiang Gao and Chuanqi Cheng and Yanwei Yu and Lei Cao and Chao Huang and Junyu Dong.  
 2022 IEEE 38th International Conference on Data Engineering (ICDE). 2022.  
[10.1109/icde53745.2022.00244](https://doi.org/10.1109/icde53745.2022.00244)
- **Randomized Reference Models for Temporal Networks**.  
 Laetitia Gauvin and Mathieu G\'enois and M\'arton Karsai and Mikko Kivelä and Taro Takaguchi and Eugenio Valdano and Christian L. Vestergaard.  
 SIAM Review. 2022.  
[10.1137/19m1242252](https://doi.org/10.1137/19m1242252)
- **Mining Stable Quasi-Cliques on Temporal Networks**.  
 Longlong Lin and Pingpeng Yuan and Rong-Hua Li and Jifei Wang and Ling Liu and Hai Jin.  
 IEEE Transactions on Systems, Man, and Cybernetics: Systems. 2022.  
[10.1109/tsmc.2021.3071721](https://doi.org/10.1109/tsmc.2021.3071721)
- **Computing top-k temporal closeness in temporal networks**.  
 Oettershagen, Lutz and Mutzel, Petra.  
 Knowledge and Information Systems. 2022.  
[10.1007/s10115-021-01639-4](https://doi.org/10.1007/s10115-021-01639-4)
- **Inferring Tie Strength in Temporal Networks**.  
 Oettershagen, Lutz and Konstantinidis, Athanasios L and Italiano, Giuseppe F.  
 Joint European Conference on Machine Learning and Knowledge Discovery in Databases. 2022.  
[10.1007/978-3-031-26390-3_5](https://doi.org/10.1007/978-3-031-26390-3_5)
- **Temporal walk centrality: ranking nodes in evolving networks**.  
 Oettershagen, Lutz and Mutzel, Petra and Kriege, Nils M.  
 Proceedings of the ACM Web Conference 2022. 2022.  
[10.1145/3485447.3512210](https://doi.org/10.1145/3485447.3512210)
- **Tglib: an open-source library for temporal graph analysis**.  
 Oettershagen, Lutz and Mutzel, Petra.  
 2022 IEEE International Conference on Data Mining Workshops (ICDMW). 2022.  
[10.1109/icdmw58026.2022.00160](https://doi.org/10.1109/icdmw58026.2022.00160)
- **Analytical Models for Motifs in Temporal Networks**.  
 Alexandra Porter and Baharan Mirzasoleiman and Jure Leskovec.  
 Companion Proceedings of the Web Conference 2022. 2022.  
[10.1145/3487553.3524669](https://doi.org/10.1145/3487553.3524669)
- **Mining Bursting Core in Large Temporal Graphs**.  
 Hongchao Qin and Rong-Hua Li and Ye Yuan and Guoren Wang and Lu Qin and Zhiwei Zhang.  
 Proceedings of the VLDB Endowment. 2022.  
[10.14778/3565838.3565845](https://doi.org/10.14778/3565838.3565845)
- **ONBRA: Rigorous Estimation of the Temporal Betweenness Centrality in Temporal Networks**.  
 Diego Santoro and Ilie Sarpe.  
 Proceedings of the ACM Web Conference 2022. 2022.  
[10.1145/3485447.3512204](https://doi.org/10.1145/3485447.3512204)
- **Deep Learning for Spatio-Temporal Data Mining: A Survey**.  
 Senzhang Wang and Jiannong Cao and Philip S. Yu.  
 IEEE Transactions on Knowledge and Data Engineering. 2022.  
[10.1109/tkde.2020.3025580](https://doi.org/10.1109/tkde.2020.3025580)
- **Detecting Mixing Services via Mining Bitcoin Transaction Network With Hybrid Motifs**.  
 Jiajing Wu and Jieli Liu and Weili Chen and Huawei Huang and Zibin Zheng and Yan Zhang.  
 IEEE Transactions on Systems, Man, and Cybernetics: Systems. 2022.  
[10.1109/tsmc.2021.3049278](https://doi.org/10.1109/tsmc.2021.3049278)
- **A Higher-Order Temporal H-Index for Evolving Networks**.  
 Oettershagen, Lutz and Kriege, Nils M. and Mutzel, Petra.  
 Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining. 2023.  
[10.1145/3580305.3599242](https://doi.org/10.1145/3580305.3599242)
- **On Computing Large Temporal (Unilateral) Connected Components**.  
 Costa, Isnard Lopes and Lopes, Raul and Marino, Andrea and Silva, Ana.  
 IWOCA. 2023.  
[10.1007/978-3-031-34347-6_24](https://doi.org/10.1007/978-3-031-34347-6_24)
- **Using Motif Transitions for Temporal Graph Generation**.  
 Penghang Liu and Ahmet Erdem Sariyüce.  
 Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining. 2023.  
[10.1145/3580305.3599540](https://doi.org/10.1145/3580305.3599540)
- **An Index For Temporal Closeness Computation in Evolving Graphs**.  
 Oettershagen, Lutz and Mutzel, Petra.  
 Proceedings of the 2023 SIAM International Conference on Data Mining (SDM). 2023.  
[10.1137/1.9781611977653.ch32](https://doi.org/10.1137/1.9781611977653.ch32)
- **Temporal Network Core Decomposition and Community Search**.  
 Oettershagen, Lutz and Konstantinidis, Athanasios L and Italiano, Giuseppe F.  
 arXiv preprint arXiv:2309.11843. 2023.  
[10.1007/978-3-030-59728-3_37](https://doi.org/10.1007/978-3-030-59728-3_37)
- **A Temporal Graphlet Kernel for Classifying Dissemination in Evolving Networks**.  
 Oettershagen, Lutz and Kriege, Nils M and Jordan, Claude and Mutze, Petra.  
 Proceedings of the 2023 SIAM International Conference on Data Mining (SDM). 2023.  
[10.1137/1.9781611977653.ch3](https://doi.org/10.1137/1.9781611977653.ch3)
- **Densest Periodic Subgraph Mining on Large Temporal Graphs**.  
 Hongchao Qin and Rong-Hua Li and Ye Yuan and Yongheng Dai and Guoren Wang.  
 IEEE Transactions on Knowledge and Data Engineering. 2023.  
[10.1109/tkde.2022.3233788](https://doi.org/10.1109/tkde.2022.3233788)
