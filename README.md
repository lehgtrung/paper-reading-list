# papers-courses-books-talks

## Blogs
1. Learning with not Enough Data Part 1: Semi-Supervised Learning [Link](https://lilianweng.github.io/posts/2021-12-05-semi-supervised/)
2. Deep Semi-Supervised Learning [Link](https://yassouali.github.io/ml-blog/deep-semi-supervised/)
3. An overview of proxy-label approaches for semi-supervised learning [Link](https://ruder.io/semi-supervised/index.html)

## Books
1. Statistical Inference [PDF](https://mybiostats.files.wordpress.com/2015/03/casella-berger.pdf)
2. Deep Learning on Graph [Link](https://cse.msu.edu/~mayao4/dlg_book/)
3. Statistical Relational Learning [Link](https://www.cs.umd.edu/srl-book/)
4. Knowledge Representation and Reasoning by Hector Levesque and Ronald J. Brachman

## Talks
1. Beyond NP with Tractable Circuits [Youtube](https://www.youtube.com/watch?v=kdMzmgyLfQs&t=2357s)
2. Bridging Machine Learning and Logical Reasoning by Abductive Learning [Youtube](https://www.youtube.com/watch?v=ETHrFxiFIUM&t=2752s)
3. Building Neural Network Models That Can Reason [Youtube](https://www.youtube.com/watch?v=-2JRiv3Mycs&ab_channel=MicrosoftResearch)
4. Logic-based Learning for Interpretable AI [Slides](https://www.dropbox.com/scl/fi/8eomnhhvyrx1zni67hm95/20-LBL-of-Definite-Programs.pdf?rlkey=53tp65k4drcqpgzibxzd8xpwi&dl=0)
5. Knowledge Representation and Reasoning [Slides](https://www.cs.toronto.edu/~hector/PublicKRSlides.pdf)

## Courses
1. **CS264A Automated Reasoning., UCLA** 
    * [Youtube playlist](https://www.youtube.com/playlist?list=PLlDG_zCuBub5AyHuxnw8vfgx7Wd-P-4XN)
    * [Review Note](http://web.cs.ucla.edu/~patricia.xiao/files/CS264A_Review_Note_midterm.pdf)
    * [Homeworks](https://github.com/lehgtrung/UCLA-CS264A-Fall2020)

2. **CS224W: Machine Learning with Graphs., Stanford** 
    * [Youtube playlist](https://www.youtube.com/watch?v=JAB_plj2rbA&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn)
    * [Website](http://web.stanford.edu/class/cs224w/)

4. **Berkeley Deep Learning: CS 182 Spring 2021**
    * [Youtube playlist](https://www.youtube.com/playlist?list=PL_iWQOsE6TfVmKkQHucjPAoRtIJYt8a5A)
  
5. **Deep Reinforcement Learning: CS 285 Fall 2021**
    * [Youtube playlist](https://www.youtube.com/playlist?list=PL_iWQOsE6TfXxKgI1GgyV1B_Xa0DxE5eH)
  
6. **MIT RES.6-012 Introduction to Probability, Spring 2018**
    * [Youtube playlist](https://youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6&si=Xn4FmgnIsnN6NQVG)

## Papers

### Exploration
1. **THE NEURO-SYMBOLIC CONCEPT LEARNER: INTERPRETING SCENES, WORDS, AND SENTENCES FROM NATURAL SUPERVISION**, [paper](https://arxiv.org/pdf/1904.12584.pdf)
2. **IS CHATGPT A GENERAL-PURPOSE NATURAL LANGUAGE PROCESSING TASK SOLVER?**, [paper](https://arxiv.org/pdf/2302.06476.pdf).
3. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity**, [paper](https://arxiv.org/pdf/2302.04023.pdf)
4. **RNNLOGIC: LEARNING LOGIC RULES FOR REASONING ON KNOWLEDGE GRAPHS**, [paper](https://arxiv.org/pdf/2010.04029.pdf)
5. **REPLUG: Retrieval-Augmented Black-Box Language Models**, [paper](https://arxiv.org/pdf/2301.12652.pdf)
6. **Abductive Learning with Ground Knowledge Base**, [paper](http://www.lamda.nju.edu.cn/huangyx/src/IJCAI21-GABL.pdf)
7. **AUTOPROMPT: Eliciting Knowledge from Language Models with Automatically Generated Prompts** [paper](https://aclanthology.org/2020.emnlp-main.346.pdf)
8. **Ruleformer: Context-aware Rule Mining over Knowledge Graph** [paper](https://aclanthology.org/2022.coling-1.225.pdf)
9. **RLogic: Recursive Logical Rule Learning from Knowledge Graphs** [paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539421)
10. **Relational Message Passing for Knowledge Graph Completion** [paper](https://dl.acm.org/doi/pdf/10.1145/3447548.3467247)


### Knowledge graph reasoning
1. **NeuralLP: Differentiable Learning of Logical Rules for Knowledge Base Reasoning**, [paper](https://arxiv.org/pdf/1702.08367.pdf)
2. **DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs**, [paper](https://arxiv.org/pdf/1911.00055.pdf)
3. **RNNLOGIC: LEARNING LOGIC RULES FOR REASONING ON KNOWLEDGE GRAPHS**, [paper](https://arxiv.org/pdf/2010.04029.pdf)
4. **RLogic: Recursive Logical Rule Learning from Knowledge Graphs**, [paper](https://web.cs.ucla.edu/~yzsun/papers/2022_KDD_RLogic.pdf)
5. **NEURAL COMPOSITIONAL RULE LEARNING FOR KNOWLEDGE GRAPH REASONING**, [paper](https://arxiv.org/pdf/2303.03581.pdf)
6. **LOGICAL ENTITY REPRESENTATION IN KNOWLEDGEGRAPHS FOR DIFFERENTIABLE RULE LEARNING**, [paper](https://arxiv.org/pdf/2305.12738.pdf)



### Knowledge graph and Link prediction
1. Link Prediction Based on Graph Neural Networks, [paper](https://proceedings.neurips.cc/paper_files/paper/2018/file/53f0d7c537d99b3824f0f99d62ea2428-Paper.pdf)\
Use GNN to learn subgraph heuristics (common neighbors, Jaccard, preferential attachment,...) and use those statistics to infer hidden links.

3. **Knowledge Informed Semantic Parsing for Conversational Question Answering**, 2021 [paper](https://assets.amazon.science/ca/f9/bbef16c24f6fbf29059888d54c13/knowledge-informed-semantic-parsing-for-conversational-question-answering.pdf)
Learn a path, then traverse graph with learned path.


### Meta learning

2. **Self-Supervised Generalisation with Meta Auxiliary Learning**, [paper](https://arxiv.org/pdf/1901.08933.pdf)
Automatically learning sub-classes via meta-learning and use the learned data&sub-class as auxiliary objective. 


### Abductive learning

1. **Fast Abductive Learning by Similarity-based Consistency Optimization** [paper](https://proceedings.neurips.cc/paper/2021/file/df7e148cabfd9b608090fa5ee3348bfe-Paper.pdf)

1. **Abductive Learning with Ground Knowledge Base** [paper](https://www.ijcai.org/proceedings/2021/0250.pdf)


1. **Abductive Knowledge Induction From Raw Data** IJCAI 2020, [paper](https://arxiv.org/pdf/2010.03514.pdf)
    
1. **Abductive learning: towards bridging machine learning and logical reasoning** 2019, [paper](http://scis.scichina.com/en/2019/076101.pdf)
    
1. **Semi-Supervised Abductive Learning and Its Application to Theft Judicial Sentencing** ICDM 2020, [paper](https://cs.nju.edu.cn/liyf/paper/icdm20-SSABL.pdf)
    
1. **Semi-supervised Relation Extraction via Incremental Meta Self-Training** [paper](https://arxiv.org/pdf/2010.16410.pdf)
    
1. **IN DEFENSE OF PSEUDO-LABELING: AN UNCERTAINTY-AWARE PSEUDO-LABEL SELECTION FRAMEWORK FOR SEMI-SUPERVISED LEARNING** [paper](https://arxiv.org/pdf/2101.06329.pdf)
    

### Neural-sympolic Learning
1. **A Semantic Loss Function for Deep Learning with Symbolic Knowledge** ICLM'2020, [paper](https://arxiv.org/abs/1711.11157)

1. **Embedding Symbolic Knowledge into Deep Networks** NeurIPS'2019, [paper](https://arxiv.org/abs/1909.01161)
    
    **Summary**: [Chris's Blog](http://christopher5106.github.io/deep/learning/2020/02/26/symbolic_knowledge_in_deep_networks.html)

1. **NeurASP: Embracing Neural Networks into Answer Set Programming** IJCAI-2020, [paper](https://www.ijcai.org/proceedings/2020/0243.pdf)

1. **Harnessing Deep Neural Networks with Logic Rules** ACL 2016, [paper](http://www.cs.cmu.edu/~epxing/papers/2016/Hu_etal_ACL16.pdf)

1. **DeepProbLog: Neural Probabilistic Logic Programming**, [paper](https://arxiv.org/pdf/1805.10872.pdf)

2. **A Critical Review of Inductive Logic Programming Techniques for Explainable AI**[paper](https://arxiv.org/pdf/2112.15319.pdf)

3. **NEUROSYMBOLIC AI AND ITS TAXONOMY: A SURVEY** [paper](https://arxiv.org/pdf/2305.08876.pdf)


### Neural Relation Extraction (NLP)
1. **Span-based Joint Entity and Relation Extraction with Transformer Pre-training**, ECAI 2020, [paper](https://arxiv.org/pdf/1909.07755v4.pdf)
    
1. **NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction** WWWW, 2020, [paper](https://arxiv.org/pdf/1909.02177.pdf)
    
### Visual Relation Extraction (CV)
   
2. **Visual Relationship Detection with Internal and External Linguistic Knowledge Distillation** ICCV 2017 [paper](https://arxiv.org/pdf/1707.09423.pdf)

   *Ruichi Yu, Ang Li, Vlad I. Morariu, Larry S. Davis*

    
### Answer Set Programming
1. **What Is Answer Set Programming?**, [paper](https://www.cs.utexas.edu/users/vl/papers/wiasp.pdf)

   *Vladimir Lifschitz*
   
1. **Answer Set Programming: Basics**, [paper](https://iccl.inf.tu-dresden.de/w/images/1/1a/FLP-ASP-L1.pdf)

   *Sebastian Rudolph*


## Insights

### Neural-symbollic integration
Learning with rules: The core idea of neural symbollic integration is that we use rules to eliminate hypothesises that are inconsistent with the KB (the same idea as ASP). Therefore, we can maximize the learning capability of machine learning models since the KB has tighten the search space of the model.

![](https://i.imgur.com/giB1iqw.png)

The rules we are trying to incoporate should be in form of integrity constrains which means a list conjunct literals that implies FALSE. For example, in Visual Relationship Detection (VDR) the visual relationship <person, ride, horse> is expressed with the atomic formulas Person(p1), Horse(h1) and ride(p1, h1). Common knowledge is expressed through logical constraints, e.g., ∀x, y(ride(x, y) → ¬Dog(x)) states that dogs do not ride.


## LLMs
1. **DSP: Discriminative Soft Prompts for Zero-Shot Entity and Relation** [paper](https://aclanthology.org/2023.findings-acl.339.pdf)

2. **Leveraging Large Language Models to Generate Answer Set Programs** [paper](https://arxiv.org/pdf/2307.07699.pdf)

3. **Distilling Large Language Models for Biomedical Knowledge Extraction: A Case Study on Adverse Drug Events** [paper](https://arxiv.org/pdf/2307.06439.pdf)

4. **A Survey of Large Language Models** [paper](https://arxiv.org/pdf/2303.18223.pdf)

5. **AgentBench: Evaluating LLMs as Agents** [paper](https://arxiv.org/pdf/2308.03688.pdf)

## MISO
### Association rules mining
1. **Frequent Itemsets** [paper](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
1. **Detection of Frequent Alarm Patterns in Industrial Alarm Floods Using Itemset Mining Methods**, [paper](https://sci-hub.hkvisa.net/10.1109/TIE.2018.2795573)
1. **Discovering Association Rules of Mode-Dependent Alarms From Alarm and Event Logs**, [paper](https://sci-hub.ru/https://ieeexplore.ieee.org/document/7921590)
2. **Association rules mining based analysis of consequential alarm sequences in chemical processes**, [paper](https://sci-hub.ru/https://www.sciencedirect.com/science/article/abs/pii/S0950423016300778)
3. **Process Mining for Alarm Rationalization and Fault Patterns Identification**, [paper](https://sci-hub.ru/10.1109/etfa.2012.6489695)
4. **Aiding Alarm Rationalization by Automatic Identification of various sequential patterns in large volume of Alarm and Event log data**, [paper](https://iopscience.iop.org/article/10.1088/1757-899X/778/1/012092/pdf)
5. **Methodology and Application of Pattern Mining in Multiple Alarm Flood Sequences**, [paper](https://reader.elsevier.com/reader/sd/pii/S2405896315011246)
6. **Online pattern matching and prediction of incoming alarm floods**, [paper](https://sci-hub.ru/https://www.sciencedirect.com/science/article/abs/pii/S0959152417300100)
7. **Process Discovery of Operator Actions in Response to Univariate Alarms**, [paper](https://www.sciencedirect.com/science/article/pii/S2405896316305444)
8. **Detection of Temporal Dependencies in Alarm Time Series of Industrial Plants**, [paper](https://www.sciencedirect.com/science/article/pii/S1474667016418744)

### Clustering
1. **Detection of Correlated Alarms Based on Similarity Coefficients of Binary Data**, [paper](https://sci-hub.ru/https://ieeexplore.ieee.org/document/6485001)
2. **Online Alarm Flood Classification Using Alarm Coactivations**, [paper](https://www.sciencedirect.com/science/article/pii/S2405896318320068)
3. **IPL2 and 3 performance improvement method for process safety using event
correlation analysis**, [paper](https://sci-hub.hkvisa.net/10.1016/j.compchemeng.2010.07.029)
4. **Graphical Representation of Industrial Alarm Data**, [paper](https://www.sciencedirect.com/science/article/pii/S1474667015325283)
5. **Graphical tools for routine assessment of industrial alarm systems**, [paper](https://sci-hub.hkvisa.net/10.1016/j.compchemeng.2012.06.042)
6. **Similarity Analysis of Industrial Alarm Flood Data**, [paper](https://sci-hub.hkvisa.net/10.1109/tase.2012.2230627)

### Nuisance alarm removal
1. **A method to remove chattering alarms using median filters** [paper](https://sci-hub.ru/https://www.sciencedirect.com/science/article/abs/pii/S0019057817306286)


1. **Log analysis via space-time pattern matching**, [paper](https://hal.archives-ouvertes.fr/hal-02909936/document)

   *Anne Bouillard, Marc-Olivier Buob, Maxime Raynal, Achille Salaün*

## Lecture notes
1. **Math for computer science (series)**, [Link](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/readings/MIT6_042JF10_chap09.pdf)
