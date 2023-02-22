# papers-courses-books-talks

## Blogs
1. Learning with not Enough Data Part 1: Semi-Supervised Learning [Link](https://lilianweng.github.io/posts/2021-12-05-semi-supervised/)
2. Deep Semi-Supervised Learning [Link](https://yassouali.github.io/ml-blog/deep-semi-supervised/)
3. An overview of proxy-label approaches for semi-supervised learning [Link](https://ruder.io/semi-supervised/index.html)

## Books
1. Statistical Inference [PDF](https://mybiostats.files.wordpress.com/2015/03/casella-berger.pdf)
2. Deep Learning on Graph [Link](https://cse.msu.edu/~mayao4/dlg_book/)
3. Statistical Relational Learning [Link](https://www.cs.umd.edu/srl-book/)

## Talks
1. Beyond NP with Tractable Circuits [Youtube](https://www.youtube.com/watch?v=kdMzmgyLfQs&t=2357s)
2. Bridging Machine Learning and Logical Reasoning by Abductive Learning [Youtube](https://www.youtube.com/watch?v=ETHrFxiFIUM&t=2752s)
3. Building Neural Network Models That Can Reason [Youtube](https://www.youtube.com/watch?v=-2JRiv3Mycs&ab_channel=MicrosoftResearch)

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

### Exploration
1. **THE NEURO-SYMBOLIC CONCEPT LEARNER: INTERPRETING SCENES, WORDS, AND SENTENCES FROM NATURAL SUPERVISION**, [paper](https://arxiv.org/pdf/1904.12584.pdf)
2. **IS CHATGPT A GENERAL-PURPOSE NATURAL LANGUAGE PROCESSING TASK SOLVER?**, [paper](https://arxiv.org/pdf/2302.06476.pdf).
3. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity**, [paper](https://arxiv.org/pdf/2302.04023.pdf)
4. **RNNLOGIC: LEARNING LOGIC RULES FOR REASONING ON KNOWLEDGE GRAPHS**, [paper](https://arxiv.org/pdf/2010.04029.pdf)


### Meta learning

1. **Meta Pseudo Labels**, [paper](https://arxiv.org/pdf/2003.10580.pdf)

2. **Self-Supervised Generalisation with Meta Auxiliary Learning**, [paper](https://arxiv.org/pdf/1901.08933.pdf)

   Auxiliary tasks are supposed to improve primary task but need expert design. This paper constructs a label generation network which automatically generates labels for an auxiliary task. The label generation network is then updated by encouraging auxiliary labels to be chosen such that, if the multi-task network were to be trained using these auxiliary labels, the performance of the primary task would be maximised on this same training data.

### Knowledge graph and knowledge base QA
1. **Knowledge Graph Reasoning with Relational Digraph**, WWW 2022, [paper](https://arxiv.org/pdf/2108.06040.pdf)

   *Yongqi Zhang et al*
   
2. **A Survey on Complex Knowledge Base Question Answering: Methods, Challenges and Solutions**, 2021, [paper](https://arxiv.org/pdf/2105.11644.pdf)

3. **Knowledge Informed Semantic Parsing for Conversational Question Answering**, 2021 [paper](https://assets.amazon.science/ca/f9/bbef16c24f6fbf29059888d54c13/knowledge-informed-semantic-parsing-for-conversational-question-answering.pdf)

### Self-supervised learning
1. **VICREG: VARIANCE-INVARIANCE-COVARIANCE REGULARIZATION FOR SELF-SUPERVISED LEARNING**, ICLR 2021, [paper](https://arxiv.org/pdf/2105.04906.pdf)

   *Adrien Bardes et al*

### Semi-supervised learning
1. **FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence**, NeurIPS, 2020, [paper](https://arxiv.org/pdf/2001.07685.pdf)

    *Kihyuk Sohn et al*
    
2. **MixMatch: A Holistic Approach to Semi-Supervised Learning**, NeurIPS, 2019, [paper](https://arxiv.org/pdf/1905.02249.pdf)

### Knowledge distillation
1. **Knowledge Distillation Beyond Model Compression** 2020 [paper](https://arxiv.org/pdf/2007.01922.pdf) 

    *Fahad Sarfraz, Elahe Arani and Bahram Zonooz*

### Semi-supervised learning

1. **Fast Abductive Learning by Similarity-based Consistency Optimization** [paper](https://proceedings.neurips.cc/paper/2021/file/df7e148cabfd9b608090fa5ee3348bfe-Paper.pdf)

1. **Abductive Learning with Ground Knowledge Base** [paper](https://www.ijcai.org/proceedings/2021/0250.pdf)


1. **Abductive Knowledge Induction From Raw Data** IJCAI 2020, [paper](https://arxiv.org/pdf/2010.03514.pdf)
    
    *Wang-Zhou Dai , Stephen H. Muggleton*
    
    Summary: TODO
    
1. **Abductive learning: towards bridging machine learning and logical reasoning** 2019, [paper](http://scis.scichina.com/en/2019/076101.pdf)
    
    *Zhi-Hua ZHOU*
    
    Summary: TODO
    
1. **Semi-Supervised Abductive Learning and Its Application to Theft Judicial Sentencing** ICDM 2020, [paper](https://cs.nju.edu.cn/liyf/paper/icdm20-SSABL.pdf)

    *Yu-Xuan Huang et al*
    
    Summary: TODO
    
1. **Semi-supervised Relation Extraction via Incremental Meta Self-Training** [paper](https://arxiv.org/pdf/2010.16410.pdf)

    *Xuming Hu et al*
    
1. **Integrating Deep Learning with Logic Fusion for Information Extraction** [paper](https://arxiv.org/pdf/1912.03041.pdf)

    *Wenya Wang et al*
    
    
1. **A Review on Semi-Supervised Relation Extraction** [paper](https://arxiv.org/pdf/2103.07575.pdf)

1. *IN DEFENSE OF PSEUDO-LABELING: AN UNCERTAINTY-AWARE PSEUDO-LABEL SELECTION FRAMEWORK FOR SEMI-SUPERVISED LEARNING* [paper](https://arxiv.org/pdf/2101.06329.pdf) ICLR 2021
Idea: Calibration aware pseudo labels selection.
    

### Neural-sympolic Learning
1. **A Semantic Loss Function for Deep Learning with Symbolic Knowledge** ICLM'2020, [paper](https://arxiv.org/abs/1711.11157)

    *Jingyi Xu 1 Zilu Zhang 2 Tal Friedman 1 Yitao Liang 1 Guy Van den Broeck*
    
    Summary: TODO

1. **Embedding Symbolic Knowledge into Deep Networks** NeurIPS'2019, [paper](https://arxiv.org/abs/1909.01161)

    *Yaqi Xie, Ziwei Xu, Mohan S Kankanhalli, Kuldeep S. Meel, Harold Soh* 
    
    **Summary**: [Chris's Blog](http://christopher5106.github.io/deep/learning/2020/02/26/symbolic_knowledge_in_deep_networks.html)

1. **NeurASP: Embracing Neural Networks into Answer Set Programming** IJCAI-2020, [paper](https://www.ijcai.org/proceedings/2020/0243.pdf)

    *Zhun Yang, Adam Ishay, Joohyung Lee*
    
    Summary: TODO

1. **A Knowledge Compilation Map** Journal of AI Research 2002, [paper](https://arxiv.org/abs/1106.1819)

    *Mehmet Aydar, Ozge Bozal, Furkan Ozbay*

1. **Harnessing Deep Neural Networks with Logic Rules** ACL 2016, [paper](http://www.cs.cmu.edu/~epxing/papers/2016/Hu_etal_ACL16.pdf)

    *Zhiting Hu, Xuezhe Ma, Zhengzhong Liu, Eduard Hovy, Eric P. Xing*
    
1. **Logic Tensor Networks: Deep Learning and Logical Reasoning from Data and Knowledge** Workshop on Neural-Symbolic Learning and Reasoning, 2017, [paper](https://arxiv.org/pdf/1606.04422.pdf)

    *Luciano Serafini and Artur d’Avila Garcez*


### Neural Relation Extraction (NLP)
1. **Span-based Joint Entity and Relation Extraction with Transformer Pre-training**, ECAI 2020, [paper](https://arxiv.org/pdf/1909.07755v4.pdf)

    *Markus Eberts and Adrian Ulges*
    
1. **NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction** WWWW, 2020, [paper](https://arxiv.org/pdf/1909.02177.pdf)

    *Wenxuan Zhou, Hongtao Lin,  Bill Yuchen Lin, Ziqi Wang*
    
1. **A Trigger-Sense Memory Flow Framework for Joint Entity and Relation Extraction** WWW 2021, [paper](https://arxiv.org/pdf/2101.10213.pdf)

    *Yongliang Shen et al*
    
1. **Exploiting the Syntax-Model Consistency for Neural Relation Extraction**, ACL 2020 [paper](https://aclanthology.org/2020.acl-main.715.pdf)

    *Amir Pouran Ben Veyseh et al*
    
1. **Exploiting Syntactico-Semantic Structures for Relation Extraction**, ACL 2011, [paper](https://aclanthology.org/P11-1056.pdf)

    *Yee Seng Chan and Dan Roth*
    
### Visual Relation Extraction (CV)
1. **Compensating Supervision Incompleteness with Prior Knowledge in Semantic Image Interpretation** IJCNN 2019 [paper](https://arxiv.org/pdf/1910.00462v1.pdf)

   *Ivan Donadello, Luciano Serafini*
   
2. **Visual Relationship Detection with Internal and External Linguistic Knowledge Distillation** ICCV 2017 [paper](https://arxiv.org/pdf/1707.09423.pdf)

   *Ruichi Yu, Ang Li, Vlad I. Morariu, Larry S. Davis*


### Survey and general methods
1. **A brief introduction to weakly supervised learning** 2018 [paper](https://watermark.silverchair.com/nwx106.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAArswggK3BgkqhkiG9w0BBwagggKoMIICpAIBADCCAp0GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMedRMaI4UHvI3ErxwAgEQgIICbrZ9EUDcbWw9mLEk17ylJbThWjIN5EP-e_G4CtH5yt4tLeh59Zj2ByFAYXr7jnSTxSYEE9etDqo3xljt53BjXMfpEtQDf3pP_7HC8lb0Z5GW8dgfxWtN8sSvFGFldsq7SPk_8pcTFfAfiyy83Gh2xoP6F0BCvfRtusxmLtdUMJO_K149GRtGaxTnfjNEv5Hiy6GTOOOWmQCLVGWEzHyLVvYJxF0Noydgl_QIY2r9eekE2E-mqEHvaV-mfHpsy1q35Ye0E24WC8MMu0ZIQz3Rn4XOccYalYIPO84oJx6ftE8GYrwh8XAQ2Z9eUWNxkoiW2KqAnl7lRLtkQjsijXPdvE2JNyH77HDgZYLkpDQbSXzZKcg_YnPbBxji1RfTCskgKHBlK5pISiiRgKU82s75Zigt2dIyfhImF3hUURuk0s7GC9-DFGWEo52oFMrNUvqEUP9nYW3MQWUmeax2ekyki6awqxGlC6cpINSHmXYtWNjnhPsZ-j8XiZhE_jQr0LSHAwdsxCVS6CjDYrbw3P67x3z4HToSFXnRhzZZ_Ko6c60tlRAmeWoLPg9JI_iuKwOD72y2Zd_aqKqtNtU6_5ENYi2xtp0U_clkL8GnbbJoOOzlq0mI2q4RUOIJF9T7HftwLAVWbHCIHWylo3a8CcXsjSH-5xxFeFKKU3q4bHlHgT6Xf83FO5jlUH8_mZtmeor93FQ7gSNNbcJo2U2DMe18gBHiy001khC_sVWQUj729Ph-g1tJo31jXlUWWuRf6S-nSkz_L78KEF3vlk2PoXwyr8TQa0Eais14RcXnFjZjHkuGFaFoNubDZsgqTCVa6P8)

1. **Neural relation extraction: a survey** arXiv, 2020, [paper](https://arxiv.org/abs/2007.04247)

    *Mehmet Aydar, Ozge Bozal, Furkan Ozbay*
    
1. **A survey on neural relation extraction** arXviv, 2020, [paper](https://link.springer.com/content/pdf/10.1007/s11431-020-1673-6.pdf)

    *Liu Kang*

1. **NLP-progress: Relationship Extraction** [Link](http://nlpprogress.com/english/relationship_extraction.html)

1. **Knowledge Graph Embedding: A Survey of Approaches and Applications** TKDE, 2017 [Link](https://persagen.com/files/misc/Wang2017Knowledge.pdf)

    *Quan Wang, Zhendong Mao, Bin Wang, and Li Guo*
1. **A Survey on Knowledge Graphs: Representation, Acquisition, and Applications**, 2021, IEEE Transactions on Neural Networks and Learning Systems, [Link](https://ieeexplore.ieee.org/abstract/document/9416312)
    
    *S. Ji, S. Pan, E. Cambria, P. Marttinen and P. S. Yu*
    
1. **A Roadmap to Domain Knowledge Integration in Machine Learning**, 2020, IEEE International Conference on Knowledge Graph, [Link](https://sci-hub.se/https://ieeexplore.ieee.org/abstract/document/9194557)
    
    *H. D. Gupta and V. S. Sheng*
    
1. **A Survey on Deep Semi-supervised Learning**, 2021, [paper](https://arxiv.org/pdf/2103.00550.pdf)

    *Xiangli Yang, Zixing Song, Irwin King*
    
1. **Neural Networks Enhancement with Logical Knowledge**, 2021 [paper](https://arxiv.org/pdf/2009.06087.pdf)
    
### Answer Set Programming
1. **What Is Answer Set Programming?**, [paper](https://www.cs.utexas.edu/users/vl/papers/wiasp.pdf)

   *Vladimir Lifschitz*
   
1. **Answer Set Programming: Basics**, [paper](https://iccl.inf.tu-dresden.de/w/images/1/1a/FLP-ASP-L1.pdf)

   *Sebastian Rudolph*

### Awesome githubs
1. **Active learning**, https://github.com/yongjin-shin/awesome-active-learning
2. **Few-shot learning**, https://github.com/Bryce1010/Awesome-Few-shot
3. **Transfer learning**, https://github.com/artix41/awesome-transfer-learning
4. **Knowledge distillation**, https://github.com/FLHonker/Awesome-Knowledge-Distillation

## Insights

### Neural-symbollic integration
Learning with rules: The core idea of neural symbollic integration is that we use rules to eliminate hypothesises that are inconsistent with the KB (the same idea as ASP). Therefore, we can maximize the learning capability of machine learning models since the KB has tighten the search space of the model.

![](https://i.imgur.com/giB1iqw.png)

The rules we are trying to incoporate should be in form of integrity constrains which means a list conjunct literals that implies FALSE. For example, in Visual Relationship Detection (VDR) the visual relationship <person, ride, horse> is expressed with the atomic formulas Person(p1), Horse(h1) and ride(p1, h1). Common knowledge is expressed through logical constraints, e.g., ∀x, y(ride(x, y) → ¬Dog(x)) states that dogs do not ride.



## MISO
1. **Log analysis via space-time pattern matching**, [paper](https://hal.archives-ouvertes.fr/hal-02909936/document)

   *Anne Bouillard, Marc-Olivier Buob, Maxime Raynal, Achille Salaün*

## Lecture notes
1. **Math for computer science (series)**, [Link](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/readings/MIT6_042JF10_chap09.pdf)

   *MIT*
