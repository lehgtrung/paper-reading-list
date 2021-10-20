# papers-courses-books-talks

## Books
1. Statistical Inference [PDF](https://mybiostats.files.wordpress.com/2015/03/casella-berger.pdf)
2. Deep Learning on Graph [Link](https://cse.msu.edu/~mayao4/dlg_book/)
3. Electric Power System Basics For Non-electrical Professional 2nd Edition, Steve W. Blume

## Talks
1. Beyond NP with Tractable Circuits [Youtube](https://www.youtube.com/watch?v=kdMzmgyLfQs&t=2357s)
2. Bridging Machine Learning and Logical Reasoning by Abductive Learning [Youtube](https://www.youtube.com/watch?v=ETHrFxiFIUM&t=2752s)

## Courses
1. **CS264A Automated Reasoning., UCLA** 
    * [Youtube playlist](https://www.youtube.com/playlist?list=PLlDG_zCuBub5AyHuxnw8vfgx7Wd-P-4XN)
    * [Review Note](http://web.cs.ucla.edu/~patricia.xiao/files/CS264A_Review_Note_midterm.pdf)
    * [Homeworks](https://github.com/lehgtrung/UCLA-CS264A-Fall2020)

2. **CS224W: Machine Learning with Graphs., Stanford** 
    * [Youtube playlist](https://www.youtube.com/watch?v=JAB_plj2rbA&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn)
    * [Website](http://web.stanford.edu/class/cs224w/)

3. **Graph Neural Network., UPenn**
    * [Course page](https://gnn.seas.upenn.edu/lectures/)

## Papers
### Neural-sympolic Learning
1. **A Semantic Loss Function for Deep Learning with Symbolic Knowledge** ICLM'2020, [paper](https://arxiv.org/abs/1711.11157)

    *Jingyi Xu 1 Zilu Zhang 2 Tal Friedman 1 Yitao Liang 1 Guy Van den Broeck*
    
    Summary: TODO

1. **Embedding Symbolic Knowledge into Deep Networks** NeurIPS'2019, [paper](https://arxiv.org/abs/1909.01161)

    *Yaqi Xie, Ziwei Xu, Mohan S Kankanhalli, Kuldeep S. Meel, Harold Soh* 
    
    <img src="https://raw.githubusercontent.com/lehgtrung/paper-reading-list/main/Screenshot%20from%202021-10-06%2021-43-01.png?token=AKIJDHC7WPEPVRJ5YT35EGTBN7OKK" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="600" height="300" />
    
    **Summary**: The task that LENSR tried to solve was “Visual relation prediction”, given an image and 2 objects, we must predict the relationship between them. For example, in the image above, given two objects “person” and “helmet”, we must predict the relationship “person-wear-helmet”. Based on the spatial knowledge we know about the relationship, for example, we know that if an object A has the relationship “wear” with an object B then B must be above and overlap with A. LENRS takes advantage of these knowledge which is encoded as a logic formula and convert the formula into a graph. With the logic formula graph, the authors model them with Graph Neural Networks. This step is called “Logic embedding”. The encoded knowledge can serve as a regularization (the logic loss in the figure) to guide the model to make better prediction without consuming lots of data. Furthermore, LENSR can automatically extract those rules based on the ground truth labels themselves. LENSR defines the spatial relationship as in the following figure: 
    
    <img src="https://raw.githubusercontent.com/lehgtrung/paper-reading-list/main/Screenshot%20from%202021-10-06%2021-52-32.png?token=AKIJDHB7WEK5ANDRW73PQLLBN7O2W" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="600" height="300" />
    
    Another example is “person” and “motor”, the spatial relationship could be {overlap left, overlap below, overlap right). 

The key idea in ASP or LENSR is how to make logical rules or solver’s operations differentiable functions in order to make them to work as a module in neural network. By doing so, we can reduce the amount of data we need to train an effective network and furthermore, we can go towards controllability in machine learning/artificial intelligence.

1. **NeurASP: Embracing Neural Networks into Answer Set Programming** IJCAI-2020, [paper](https://www.ijcai.org/proceedings/2020/0243.pdf)

    *Zhun Yang, Adam Ishay, Joohyung Lee*
    
    Summary: TODO

1. **A Knowledge Compilation Map** Journal of AI Research 2002, [paper](https://arxiv.org/abs/1106.1819)

    *Mehmet Aydar, Ozge Bozal, Furkan Ozbay*

1. **Harnessing Deep Neural Networks with Logic Rules** ACL 2016, [paper](http://www.cs.cmu.edu/~epxing/papers/2016/Hu_etal_ACL16.pdf)

    *Zhiting Hu, Xuezhe Ma, Zhengzhong Liu, Eduard Hovy, Eric P. Xing*


### Neural Relation Extraction (NLP)



### Survey and general methods
1. **Neural relation extraction: a survey** arXiv, 2020, [paper](https://arxiv.org/abs/2007.04247)

    *Mehmet Aydar, Ozge Bozal, Furkan Ozbay*

1. **NLP-progress: Relationship Extraction** [Link](http://nlpprogress.com/english/relationship_extraction.html)

1. **Knowledge Graph Embedding: A Survey of Approaches and Applications** TKDE, 2017 [Link](https://persagen.com/files/misc/Wang2017Knowledge.pdf)

    *Quan Wang, Zhendong Mao, Bin Wang, and Li Guo*

3. **RECON: Relation Extraction using Knowledge Graph Context in a Graph Neural Network**, *SOTA in RE*, WWW'2021 [paper](https://arxiv.org/pdf/2009.08694)
    
    *Anson Bastos, Abhishek Nadgeri, Kuldeep Singh, Isaiah Onando Mulang’, Saeedeh Shekarpour, Johannes Hoffart, Manohar Kaul*


