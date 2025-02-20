Literature of Deep Learning for Graphs
**************************************
This is a paper list about deep learning for graphs.

.. contents::
    :local:
    :depth: 2

.. sectnum::
    :depth: 2

.. role:: author(emphasis)

.. role:: venue(strong)

.. role:: keyword(emphasis)

Node Representation Learning
============================

Unsupervised Node Representation Learning
-----------------------------------------

`DeepWalk: Online Learning of Social Representations
<https://arxiv.org/pdf/1403.6652>`_
    | :author:`Bryan Perozzi, Rami Al-Rfou, Steven Skiena`
    | :venue:`KDD 2014`
    | :keyword:`Node classification, Random walk, Skip-gram`

`LINE: Large-scale Information Network Embedding
<https://arxiv.org/pdf/1503.03578>`_
    | :author:`Jian Tang, Meng Qu, Mingzhe Wang, Ming Zhang, Jun Yan, Qiaozhu Mei`
    | :venue:`WWW 2015`
    | :keyword:`First-order, Second-order, Node classification`

`GraRep: Learning Graph Representations with Global Structural Information
<https://dl.acm.org/citation.cfm?id=2806512>`_
    | :author:`Shaosheng Cao, Wei Lu, Qiongkai Xu`
    | :venue:`CIKM 2015`
    | :keyword:`High-order, SVD`

`node2vec: Scalable Feature Learning for Networks
<https://arxiv.org/pdf/1607.00653>`_
    | :author:`Aditya Grover, Jure Leskovec`
    | :venue:`KDD 2016`
    | :keyword:`Breadth-first Search, Depth-first Search, Node Classification, Link Prediction`

`Variational Graph Auto-Encoders
<https://arxiv.org/abs/1611.07308>`_
    | :author:`Thomas N. Kipf, Max Welling`
    | :venue:`arXiv 1611`

`Scalable Graph Embedding for Asymmetric Proximity
<https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14696>`_
    | :author:`Chang Zhou, Yuqiong Liu, Xiaofei Liu, Zhongyi Liu, Jun Gao`
    | :venue:`AAAI 2017`

`Fast Network Embedding Enhancement via High Order Proximity Approximation
<https://www.ijcai.org/proceedings/2017/544>`_
    | :author:`Cheng Yang, Maosong Sun, Zhiyuan Liu, Cunchao Tu`
    | :venue:`IJCAI 2017`

`struc2vec: Learning Node Representations from Structural Identity
<https://arxiv.org/pdf/1704.03165>`_
    | :author:`Leonardo F. R. Ribeiro, Pedro H. P. Savarese, Daniel R. Figueiredo`
    | :venue:`KDD 2017`
    | :keyword:`Structural Identity`

`Poincaré Embeddings for Learning Hierarchical Representations
<https://arxiv.org/pdf/1705.08039>`_
    | :author:`Maximilian Nickel, Douwe Kiela`
    | :venue:`NIPS 2017`

`VERSE: Versatile Graph Embeddings from Similarity Measures
<https://arxiv.org/pdf/1803.04742>`_
    | :author:`Anton Tsitsulin, Davide Mottin, Panagiotis Karras, Emmanuel Müller`
    | :venue:`WWW 2018`

`Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec
<https://arxiv.org/pdf/1710.02971>`_
    | :author:`Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Kuansan Wang, Jie Tang`
    | :venue:`WSDM 2018`

`Learning Structural Node Embeddings via Diffusion Wavelets
<https://arxiv.org/pdf/1710.10321>`_
    | :author:`Claire Donnat, Marinka Zitnik, David Hallac, Jure Leskovec`
    | :venue:`KDD 2018`

`Adversarial Network Embedding
<https://arxiv.org/pdf/1711.07838>`_
    | :author:`Quanyu Dai, Qiang Li, Jian Tang, Dan Wang`
    | :venue:`AAAI 2018`

`GraphGAN: Graph Representation Learning with Generative Adversarial Nets
<https://arxiv.org/pdf/1711.08267>`_
    | :author:`Hongwei Wang, Jia Wang, Jialin Wang, Miao Zhao, Weinan Zhang, Fuzheng Zhang, Xing Xie, Minyi Guo`
    | :venue:`AAAI 2018`

`A General View for Network Embedding as Matrix Factorization
<https://dl.acm.org/citation.cfm?id=3291029>`_
    | :author:`Xin Liu, Tsuyoshi Murata, Kyoung-Sook Kim, Chatchawan Kotarasu, Chenyi Zhuang`
    | :venue:`WSDM 2019`

`Deep Graph Infomax
<https://arxiv.org/pdf/1809.10341>`_
    | :author:`Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm`
    | :venue:`ICLR 2019`

`NetSMF: Large-Scale Network Embedding as Sparse Matrix Factorization
<http://keg.cs.tsinghua.edu.cn/jietang/publications/www19-Qiu-et-al-NetSMF-Large-Scale-Network-Embedding.pdf>`_
    | :author:`Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Chi Wang, Kuansan Wang, Jie Tang`
    | :venue:`WWW 2019`

`Adversarial Training Methods for Network Embedding
<https://dl.acm.org/citation.cfm?id=3313445>`_
    | :author:`Quanyu Dai, Xiao Shen, Liang Zhang, Qiang Li, Dan Wang`
    | :venue:`WWW 2019`

`vGraph: A Generative Model for Joint Community Detection and Node Representation Learning
<https://arxiv.org/pdf/1906.07159.pdf>`_
    | :author:`Fan-Yun Sun, Meng Qu, Jordan Hoffmann, Chin-Wei Huang, Jian Tang`
    | :venue:`arXiv 1906`

Node Representation Learning in Heterogeneous Graphs
----------------------------------------------------

`Learning Latent Representations of Nodes for Classifying in Heterogeneous Social Networks
<https://dl.acm.org/citation.cfm?id=2556225>`_
    | :author:`Yann Jacob, Ludovic Denoyer, Patrick Gallinari`
    | :venue:`WSDM 2014`

`PTE: Predictive Text Embedding through Large-scale Heterogeneous Text Networks
<https://arxiv.org/pdf/1508.00200>`_
    | :author:`Jian Tang, Meng Qu, Qiaozhu Mei`
    | :venue:`KDD 2015`
    | :keyword:`Text Embedding, Heterogeneous Text Graphs`

`Heterogeneous Network Embedding via Deep Architectures
<https://dl.acm.org/citation.cfm?id=2783296>`_
    | :author:`Shiyu Chang, Wei Han, Jiliang Tang, Guo-Jun Qi, Charu C. Aggarwal, Thomas S. Huang`
    | :venue:`KDD 2015`

`Network Representation Learning with Rich Text Information
<https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/view/11098>`_
    | :author:`Cheng Yang, Zhiyuan Liu, Deli Zhao, Maosong Sun, Edward Chang`
    | :venue:`AAAI 2015`

`Max-Margin DeepWalk: Discriminative Learning of Network Representation
<https://www.ijcai.org/Proceedings/16/Papers/547.pdf>`_
    | :author:`Cunchao Tu, Weicheng Zhang, Zhiyuan Liu, Maosong Sun`
    | :venue:`IJCAI 2016`

`metapath2vec: Scalable Representation Learning for Heterogeneous Networks
<https://dl.acm.org/citation.cfm?id=3098036>`_
    | :author:`Yuxiao Dong, Nitesh V. Chawla, Ananthram Swami`
    | :venue:`KDD 2017`

`Meta-Path Guided Embedding for Similarity Search in Large-Scale Heterogeneous Information Networks
<https://arxiv.org/pdf/1610.09769>`_
    | :author:`Jingbo Shang, Meng Qu, Jialu Liu, Lance M. Kaplan, Jiawei Han, Jian Peng`
    | :venue:`arXiv 2016`

`HIN2Vec: Explore Meta-paths in Heterogeneous Information Networks for Representation Learning
<https://dl.acm.org/citation.cfm?id=3132953>`_
    | :author:`Tao-yang Fu, Wang-Chien Lee, Zhen Lei`
    | :venue:`CIKM 2017`

`An Attention-based Collaboration Framework for Multi-View Network Representation Learning
<https://arxiv.org/pdf/1709.06636>`_
    | :author:`Meng Qu, Jian Tang, Jingbo Shang, Xiang Ren, Ming Zhang, Jiawei Han`
    | :venue:`CIKM 2017`

`Multi-view Clustering with Graph Embedding for Connectome Analysis
<https://dl.acm.org/citation.cfm?id=3132909>`_
    | :author:`Guixiang Ma, Lifang He, Chun-Ta Lu, Weixiang Shao, Philip S. Yu, Alex D. Leow, Ann B. Ragin`
    | :venue:`CIKM 2017`

`Attributed Signed Network Embedding
<https://dl.acm.org/citation.cfm?id=3132847.3132905>`_
    | :author:`Suhang Wang, Charu Aggarwal, Jiliang Tang, Huan Liu`
    | :venue:`CIKM 2017`

`CANE: Context-Aware Network Embedding for Relation Modeling
<https://aclweb.org/anthology/papers/P/P17/P17-1158/>`_
    | :author:`Cunchao Tu, Han Liu, Zhiyuan Liu, Maosong Sun`
    | :venue:`ACL 2017`

`PME: Projected Metric Embedding on Heterogeneous Networks for Link Prediction
<https://dl.acm.org/citation.cfm?id=3219986>`_
    | :author:`Hongxu Chen, Hongzhi Yin, Weiqing Wang, Hao Wang, Quoc Viet Hung Nguyen, Xue Li`
    | :venue:`KDD 2018`

`BiNE: Bipartite Network Embedding
<https://dl.acm.org/citation.cfm?id=3209978.3209987>`_
    | :author:`Ming Gao, Leihui Chen, Xiangnan He, Aoying Zhou`
    | :venue:`SIGIR 2018`

`StarSpace: Embed All The Things
<https://arxiv.org/pdf/1709.03856>`_
    | :author:`Ledell Wu, Adam Fisch, Sumit Chopra, Keith Adams, Antoine Bordes, Jason Weston`
    | :venue:`AAAI 2018`

`Exploring Expert Cognition for Attributed Network Embedding
<https://dl.acm.org/citation.cfm?id=3159655>`_
    | :author:`Xiao Huang, Qingquan Song, Jundong Li, Xia Hu`
    | :venue:`WSDM 2018`

`SHINE: Signed Heterogeneous Information Network Embedding for Sentiment Link Prediction
<https://arxiv.org/pdf/1712.00732>`_
    | :author:`Hongwei Wang, Fuzheng Zhang, Min Hou, Xing Xie, Minyi Guo, Qi Liu`
    | :venue:`WSDM 2018`

`Multidimensional Network Embedding with Hierarchical Structures
<https://dl.acm.org/citation.cfm?id=3159680>`_
    | :author:`Yao Ma, Zhaochun Ren, Ziheng Jiang, Jiliang Tang, Dawei Yin`
    | :venue:`WSDM 2018`

`Curriculum Learning for Heterogeneous Star Network Embedding via Deep Reinforcement Learning
<https://dl.acm.org/citation.cfm?id=3159711>`_
    | :author:`Meng Qu, Jian Tang, Jiawei Han`
    | :venue:`WSDM 2018`

`Generative Adversarial Network based Heterogeneous Bibliographic Network Representation for Personalized Citation Recommendation
<https://www.semanticscholar.org/paper/Generative-Adversarial-Network-Based-Heterogeneous-Cai-Han/1596d6487012696ba400fb69904a2c372a08a2be>`_
    | :author:`Xiaoyan Cai, Junwei Han, Libin Yang`
    | :venue:`AAAI 2018`

`ANRL: Attributed Network Representation Learning via Deep Neural Networks
<https://www.ijcai.org/proceedings/2018/438>`_
    | :author:`Zhen Zhang, Hongxia Yang, Jiajun Bu, Sheng Zhou, Pinggang Yu, Jianwei Zhang, Martin Ester, Can Wang`
    | :venue:`IJCAI 2018`

`Efficient Attributed Network Embedding via Recursive Randomized Hashing
<https://www.ijcai.org/proceedings/2018/397>`_
    | :author:`Wei Wu, Bin Li, Ling Chen, Chengqi Zhang`
    | :venue:`IJCAI 2018`

`Deep Attributed Network Embedding
<https://www.ijcai.org/proceedings/2018/467>`_
    | :author:`Hongchang Gao, Heng Huang`
    | :venue:`IJCAI 2018`

`Co-Regularized Deep Multi-Network Embedding
<https://dl.acm.org/citation.cfm?id=3186113>`_
    | :author:`Jingchao Ni, Shiyu Chang, Xiao Liu, Wei Cheng, Haifeng Chen, Dongkuan Xu, Xiang Zhang`
    | :venue:`WWW 2018`

`Easing Embedding Learning by Comprehensive Transcription of Heterogeneous Information Networks
<https://arxiv.org/pdf/1807.03490>`_
    | :author:`Yu Shi, Qi Zhu, Fang Guo, Chao Zhang, Jiawei Han`
    | :venue:`KDD 2018`

`Meta-Graph Based HIN Spectral Embedding: Methods, Analyses, and Insights
<https://www.semanticscholar.org/paper/Meta-Graph-Based-HIN-Spectral-Embedding%3A-Methods%2C-Yang-Feng/4d5f4d6785d550383e3f3afb04c3015bf0d28405>`_
    | :author:`Carl Yang, Yichen Feng, Pan Li, Yu Shi, Jiawei Han`
    | :venue:`ICDM 2018`

`SIDE: Representation Learning in Signed Directed Networks
<https://dl.acm.org/citation.cfm?id=3186117>`_
    | :author:`Junghwan Kim, Haekyu Park, Ji-Eun Lee, U Kang`
    | :venue:`WWW 2018`

Node Representation Learning in Dynamic Graphs
----------------------------------------------

`Know-evolve: Deep temporal reasoning for dynamic knowledge graphs
<https://arxiv.org/pdf/1705.05742.pdf>`_
    | :author:`Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song`
    | :venue:`ICML 2017`

`Dyngem: Deep embedding method for dynamic graphs
<https://arxiv.org/pdf/1805.11273.pdf>`_
    | :author:`Palash Goyal, Nitin Kamra, Xinran He, Yan Liu`
    | :venue:`ICLR 2017 Workshop`

`Attributed network embedding for learning in a dynamic environment
<https://arxiv.org/pdf/1706.01860.pdf>`_
    | :author:`Jundong Li, Harsh Dani, Xia Hu, Jiliang Tang, Yi Chang, Huan Liu`
    | :venue:`CIKM 2017`

`Dynamic Network Embedding by Modeling Triadic Closure Process
<http://yangy.org/works/dynamictriad/dynamic_triad.pdf>`_
    | :author:`Lekui Zhou, Yang Yang, Xiang Ren, Fei Wu, Yueting Zhuang`
    | :venue:`AAAI 2018`

`DepthLGP: Learning Embeddings of Out-of-Sample Nodes in Dynamic Networks
<https://pdfs.semanticscholar.org/9499/b38866b1eb87ae43fa5be02f9d08cd3c20a8.pdf?_ga=2.6780794.935636364.1561139530-1831876308.1523264869>`_
    | :author:`Jianxin Ma, Peng Cui, Wenwu Zhu`
    | :venue:`AAAI 2018`

`TIMERS: Error-Bounded SVD Restart on Dynamic Networks
<https://arxiv.org/pdf/1711.09541.pdf>`_
    | :author:`Ziwei Zhang, Peng Cui, Jian Pei, Xiao Wang, Wenwu Zhu`
    | :venue:`AAAI 2018`

`Dynamic Embeddings for User Profiling in Twitter
<https://dl.acm.org/citation.cfm?id=3219819.3220043>`_
    | :author:`Shangsong Liang, Xiangliang Zhang, Zhaochun Ren, Evangelos Kanoulas`
    | :venue:`KDD 2018`

`Dynamic Network Embedding : An Extended Approach for Skip-gram based Network Embedding
<https://www.ijcai.org/proceedings/2018/0288.pdf>`_
    | :author:`Lun Du, Yun Wang, Guojie Song, Zhicong Lu, Junshan Wang`
    | :venue:`IJCAI 2018`

`DyRep: Learning Representations over Dynamic Graphs
<https://openreview.net/pdf?id=HyePrhR5KX>`_
    | :author:`Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha`
    | :venue:`ICLR 2019`

`Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks
<https://cs.stanford.edu/~srijan/pubs/jodie-kdd2019.pdf>`_
    | :author:`Srijan Kumar, Xikun Zhang, Jure Leskovec`
    | :venue:`KDD2019`

Knowledge Graph Embedding
=========================

`Translating Embeddings for Modeling Multi-relational Data
<https://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf>`_
    | :author:`Antoine Bordes, Nicolas Usunier, Alberto Garcia-Duran, Jason Weston, Oksana Yakhnenko`
    | :venue:`NIPS 2013`

`Knowledge Graph Embedding by Translating on Hyperplanes
<https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8531/8546>`_
    | :author:`Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen`
    | :venue:`AAAI 2014`

`Learning Entity and Relation Embeddings for Knowledge Graph Completion
<https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9571/9523>`_
    | :author:`Yankai Lin, Zhiyuan Liu, Maosong Sun, Yang Liu, Xuan Zhu`
    | :venue:`AAAI 2015`

`Knowledge Graph Embedding via Dynamic Mapping Matrix
<https://www.aclweb.org/anthology/P15-1067>`_
    | :author:`Guoliang Ji, Shizhu He, Liheng Xu, Kang Liu, Jun Zha`
    | :venue:`ACL 2015`

`Modeling Relation Paths for Representation Learning of Knowledge Bases
<https://arxiv.org/pdf/1506.00379>`_
    | :author:`Yankai Lin, Zhiyuan Liu, Huanbo Luan, Maosong Sun, Siwei Rao, Song Liu`
    | :venue:`EMNLP 2015`

`Embedding Entities and Relations for Learning and Inference in Knowledge Bases
<https://arxiv.org/pdf/1412.6575>`_
    | :author:`Bishan Yang, Wen-tau Yih, Xiaodong He, Jianfeng Gao, Li Deng`
    | :venue:`ICLR 2015`

`Holographic Embeddings of Knowledge Graphs
<https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewPDFInterstitial/12484/11828>`_
    | :author:`Maximilian Nickel, Lorenzo Rosasco, Tomaso Poggio`
    | :venue:`AAAI 2016`

`Complex Embeddings for Simple Link Prediction
<http://www.jmlr.org/proceedings/papers/v48/trouillon16.pdf>`_
    | :author:`Théo Trouillon, Johannes Welbl, Sebastian Riedel, Éric Gaussier, Guillaume Bouchard`
    | :venue:`ICML 2016`

`Modeling Relational Data with Graph Convolutional Networks
<https://arxiv.org/pdf/1703.06103>`_
    | :author:`Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne Van Den Berg, Ivan Titov, Max Welling`
    | :venue:`arXiv 2017.03`

`Fast Linear Model for Knowledge Graph Embeddings
<https://arxiv.org/pdf/1710.10881>`_
    | :author:`Armand Joulin, Edouard Grave, Piotr Bojanowski, Maximilian Nickel, Tomas Mikolov`
    | :venue:`arXiv 2017.10`

`Convolutional 2D Knowledge Graph Embeddings
<https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/17366/15884>`_
    | :author:`Tim Dettmers, Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel`
    | :venue:`AAAI 2018`

`Knowledge Graph Embedding With Iterative Guidance From Soft Rules
<https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16369/16011>`_
    | :author:`Shu Guo, Quan Wang, Lihong Wang, Bin Wang, Li Guo`
    | :venue:`AAAI 2018`

`KBGAN: Adversarial Learning for Knowledge Graph Embeddings
<https://arxiv.org/abs/1711.04071>`_
    | :author:`Liwei Cai, William Yang Wang`
    | :venue:`NAACL 2018`

`Improving Knowledge Graph Embedding Using Simple Constraints
<https://arxiv.org/abs/1805.02408>`_
    | :author:`Boyang Ding, Quan Wang, Bin Wang, Li Guo`
    | :venue:`ACL 2018`

`SimplE Embedding for Link Prediction in Knowledge Graphs
<https://arxiv.org/abs/1802.04868>`_
    | :author:`Seyed Mehran Kazemi, David Poole`
    | :venue:`NeurIPS 2018`

`A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network
<https://aclweb.org/anthology/papers/N/N18/N18-2053/>`_
    | :author:`Dai Quoc Nguyen, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung`
    | :venue:`NAACL 2018`

`Iteratively Learning Embeddings and Rules for Knowledge Graph Reasoning
<https://arxiv.org/abs/1903.08948>`_
    | :author:`Wen Zhang, Bibek Paudel, Liang Wang, Jiaoyan Chen, Hai Zhu, Wei Zhang, Abraham Bernstein, Huajun Chen`
    | :venue:`WWW 2019`

`RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space
<https://arxiv.org/abs/1902.10197>`_
    | :author:`Zhiqing Sun, Zhi-Hong Deng, Jian-Yun Nie, Jian Tang`
    | :venue:`ICLR 2019`

`Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs
<https://arxiv.org/abs/1906.01195>`_
    | :author:`Deepak Nathani, Jatin Chauhan, Charu Sharma, Manohar Kaul`
    | :venue:`ACL 2019`

`Probabilistic Logic Neural Networks for Reasoning
<https://arxiv.org/pdf/1906.08495.pdf>`_
    | :author:`Meng Qu, Jian Tang`
    | :venue:`arXiv 1906`

Graph Neural Networks
=====================

`Revisiting Semi-supervised Learning with Graph Embeddings
<https://arxiv.org/pdf/1603.08861>`_
    | :author:`Zhilin Yang, William W. Cohen, Ruslan Salakhutdinov`
    | :venue:`ICML 2016`

`Semi-Supervised Classification with Graph Convolutional Networks
<https://arxiv.org/pdf/1609.02907>`_
    | :author:`Thomas N. Kipf, Max Welling`
    | :venue:`ICLR 2017`

`Neural Message Passing for Quantum Chemistry
<https://arxiv.org/pdf/1704.01212>`_
    | :author:`Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl`
    | :venue:`ICML 2017`

`Motif-Aware Graph Embeddings
<http://gearons.org/assets/docs/motif-aware-graph-final.pdf>`_
    | :author:`Hoang Nguyen, Tsuyoshi Murata`
    | :venue:`IJCAI 2017`

`Learning Graph Representations with Embedding Propagation
<https://arxiv.org/pdf/1710.03059>`_
    | :author:`Alberto Garcia-Duran, Mathias Niepert`
    | :venue:`NIPS 2017`

`Inductive Representation Learning on Large Graphs
<https://arxiv.org/pdf/1706.02216>`_
    | :author:`William L. Hamilton, Rex Ying, Jure Leskovec`
    | :venue:`NIPS 2017`

`Graph Attention Networks
<https://arxiv.org/pdf/1710.10903>`_
    | :author:`Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, Yoshua Bengio`
    | :venue:`ICLR 2018`

`FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling
<https://arxiv.org/pdf/1801.10247>`_
    | :author:`Jie Chen, Tengfei Ma, Cao Xiao`
    | :venue:`ICLR 2018`

`Representation Learning on Graphs with Jumping Knowledge Networks
<https://arxiv.org/pdf/1806.03536>`_
    | :author:`Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka`
    | :venue:`ICML 2018`

`Stochastic Training of Graph Convolutional Networks with Variance Reduction
<https://arxiv.org/pdf/1710.10568>`_
    | :author:`Jianfei Chen, Jun Zhu, Le Song`
    | :venue:`ICML 2018`

`Large-Scale Learnable Graph Convolutional Networks
<https://arxiv.org/pdf/1808.03965>`_
    | :author:`Hongyang Gao, Zhengyang Wang, Shuiwang Ji`
    | :venue:`KDD 2018`

`Adaptive Sampling Towards Fast Graph Representation Learning
<https://papers.nips.cc/paper/7707-adaptive-sampling-towards-fast-graph-representation-learning.pdf>`_
    | :author:`Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang`
    | :venue:`NeurIPS 2018`

`Hierarchical Graph Representation Learning with Differentiable Pooling
<https://arxiv.org/pdf/1806.08804>`_
    | :author:`Rex Ying, Jiaxuan You, Christopher Morris, Xiang Ren, William L. Hamilton, Jure Leskovec`
    | :venue:`NeurIPS 2018`

`Bayesian Semi-supervised Learning with Graph Gaussian Processes
<https://papers.nips.cc/paper/7440-bayesian-semi-supervised-learning-with-graph-gaussian-processes.pdf>`_
    | :author:`Yin Cheng Ng, Nicolò Colombo, Ricardo Silva`
    | :venue:`NeurIPS 2018`

`Pitfalls of Graph Neural Network Evaluation
<https://arxiv.org/pdf/1811.05868>`_
    | :author:`Oleksandr Shchur, Maximilian Mumme, Aleksandar Bojchevski, Stephan Günnemann`
    | :venue:`arXiv 2018.11`

`Heterogeneous Graph Attention Network
<https://arxiv.org/pdf/1903.07293>`_
    | :author:`Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye`
    | :venue:`WWW 2019`

`Bayesian graph convolutional neural networks for semi-supervised classification
<https://arxiv.org/pdf/1811.11103.pdf>`_
    | :author:`Yingxue Zhang, Soumyasundar Pal, Mark Coates, Deniz Üstebay`
    | :venue:`AAAI 2019`

`How Powerful are Graph Neural Networks?
<https://arxiv.org/pdf/1810.00826>`_
    | :author:`Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka`
    | :venue:`ICLR 2019`

`LanczosNet: Multi-Scale Deep Graph Convolutional Networks
<https://arxiv.org/pdf/1901.01484>`_
    | :author:`Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard S. Zemel`
    | :venue:`ICLR 2019`

`Graph Wavelet Neural Network
<https://arxiv.org/pdf/1904.07785>`_
    | :author:`Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng`
    | :venue:`ICLR 2019`

`Supervised Community Detection with Line Graph Neural Networks
<https://openreview.net/pdf?id=H1g0Z3A9Fm>`_
    | :author:`Zhengdao Chen, Xiang Li, Joan Bruna`
    | :venue:`ICLR 2019`

`Predict then Propagate: Graph Neural Networks meet Personalized PageRank
<https://arxiv.org/pdf/1810.05997>`_
    | :author:`Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann`
    | :venue:`ICLR 2019`

`Invariant and Equivariant Graph Networks
<https://arxiv.org/pdf/1812.09902>`_
    | :author:`Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman`
    | :venue:`ICLR 2019`

`Capsule Graph Neural Network
<https://openreview.net/pdf?id=Byl8BnRcYm>`_
    | :author:`Zhang Xinyi, Lihui Chen`
    | :venue:`ICLR 2019`

`MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing
<https://arxiv.org/pdf/1905.00067>`_
    | :author:`Sami Abu-El-Haija, Bryan Perozzi, Amol Kapoor, Nazanin Alipourfard, Kristina Lerman,
        Hrayr Harutyunyan, Greg Ver Steeg, Aram Galstyan`
    | :venue:`ICML 2019`

`Graph U-Nets
<https://arxiv.org/pdf/1905.05178>`_
    | :author:`Hongyang Gao, Shuiwang Ji`
    | :venue:`ICML 2019`

`Disentangled Graph Convolutional Networks
<http://proceedings.mlr.press/v97/ma19a/ma19a.pdf>`_
    | :author:`Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu`
    | :venue:`ICML 2019`

`GMNN: Graph Markov Neural Networks
<https://arxiv.org/pdf/1905.06214>`_
    | :author:`Meng Qu, Yoshua Bengio, Jian Tang`
    | :venue:`ICML 2019`

`Simplifying Graph Convolutional Networks
<https://arxiv.org/pdf/1902.07153>`_
    | :author:`Felix Wu, Tianyi Zhang, Amauri Holanda de Souza Jr., Christopher Fifty, Tao Yu, Kilian Q. Weinberger`
    | :venue:`ICML 2019`

`Position-aware Graph Neural Networks
<https://arxiv.org/pdf/1906.04817>`_
    | :author:`Jiaxuan You, Rex Ying, Jure Leskovec`
    | :venue:`ICML 2019`

`Self-Attention Graph Pooling
<https://arxiv.org/pdf/1904.08082>`_
    | :author:`Junhyun Lee, Inyeop Lee, Jaewoo Kang`
    | :venue:`ICML 2019`

`Relational Pooling for Graph Representations
<https://arxiv.org/pdf/1903.02541>`_
    | :author:`Ryan L. Murphy, Balasubramaniam Srinivasan, Vinayak Rao, Bruno Ribeiro`
    | :venue:`ICML 2019`

`Graph Representation Learning via Hard and Channel-Wise Attention Networks
<https://arxiv.org/pdf/1907.04652.pdf>`_
    | :author:`Hongyang Gao, Shuiwang Ji`
    | :venue:`KDD 2019`

`Conditional Random Field Enhanced Graph Convolutional Neural Networks
<https://www.kdd.org/kdd2019/accepted-papers/view/conditional-random-field-enhanced-graph-convolutional-neural-networks>`_
    | :author:`Hongchang Gao, Jian Pei, Heng Huang`
    | :venue:`KDD 2019`

`Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks
<https://arxiv.org/abs/1905.07953>`_
    | :author:`Wei-Lin Chiang, Xuanqing Liu, Si Si, Yang Li, Samy Bengio, Cho-Jui Hsieh`
    | :venue:`KDD 2019`

`DEMO-Net: Degree-specific Graph Neural Networks for Node and Graph Classification
<https://arxiv.org/abs/1906.02319>`_
    | :author:`Jun Wu, Jingrui He, Jiejun Xu`
    | :venue:`KDD 2019`

`HetGNN: Heterogeneous Graph Neural Network
<https://www.kdd.org/kdd2019/accepted-papers/view/hetgnn-heterogeneous-graph-neural-network>`_
    | :author:`Chuxu Zhang, Dongjin Song, Chao Huang, Ananthram Swami, Nitesh V. Chawla`
    | :venue:`KDD 2019`

`Graph Recurrent Networks with Attributed Random Walks
<https://dl.acm.org/citation.cfm?id=3292500.3330941>`_
    | :author:`Xiao Huang, Qingquan Song, Yuening Li, Xia Hu`
    | :venue:`KDD 2019`

`Graph Convolutional Networks with EigenPooling
<https://arxiv.org/abs/1904.13107>`_
    | :author:`Yao Ma, Suhang Wang, Charu Aggarwal, Jiliang Tang`
    | :venue:`KDD 2019`

Applications of Graph Neural Networks
=====================================

Natural Language Processing
---------------------------

`Encoding Sentences with Graph Convolutional Networks for Semantic Role Labeling
<https://www.aclweb.org/anthology/D17-1159>`_
    | :author:`Diego Marcheggiani, Ivan Titov`
    | :venue:`EMNLP 2017`

`Graph Convolutional Encoders for Syntax-aware Neural Machine Translation
<https://www.aclweb.org/anthology/D17-1209>`_
    | :author:`Joost Bastings, Ivan Titov, Wilker Aziz, Diego Marcheggiani, Khalil Sima’an`
    | :venue:`EMNLP 2017`

`Graph-based Neural Multi-Document Summarization
<https://www.aclweb.org/anthology/K17-1045>`_
    | :author:`Michihiro Yasunaga, Rui Zhang, Kshitijh Meelu, Ayush Pareek, Krishnan Srinivasan, Dragomir Radev`
    | :venue:`CoNLL 2017`

`QANet: Combining Local Convolution with Global Self-Attention for Reading Comprehension
<https://arxiv.org/pdf/1804.09541.pdf>`_
    | :author:`Adams Wei Yu, David Dohan, Minh-Thang Luong, Rui Zhao, Kai Chen, Mohammad Norouzi, Quoc V. Le`
    | :venue:`ICLR 2018`

`A Structured Self-attentive Sentence Embedding
<https://arxiv.org/pdf/1703.03130.pdf>`_
    | :author:`Zhouhan Lin, Minwei Feng, Cicero Nogueira dos Santos, Mo Yu, Bing Xiang, Bowen Zhou, Yoshua Bengio`
    | :venue:`ICLR 2018`

`Modeling Semantics with Gated Graph Neural Networks for Knowledge Base Question Answering
<https://aclweb.org/anthology/C18-1280>`_
    | :author:`Daniil Sorokin, Iryna Gurevych`
    | :venue:`COLING 2018`

`Exploiting Semantics in Neural Machine Translation with Graph Convolutional Networks
<https://www.aclweb.org/anthology/N18-2078>`_
    | :author:`Diego Marcheggiani, Joost Bastings, Ivan Titov`
    | :venue:`NAACL 2018`

`Linguistically-Informed Self-Attention for Semantic Role Labeling
<https://www.aclweb.org/anthology/D18-1548>`_
    | :author:`Emma Strubell, Patrick Verga, Daniel Andor, David Weiss, Andrew McCallum`
    | :venue:`EMNLP 2018`

`Graph Convolution over Pruned Dependency Trees Improves Relation Extraction
<https://aclweb.org/anthology/D18-1244>`_
    | :author:`Yuhao Zhang, Peng Qi, Christopher D. Manning`
    | :venue:`EMNLP 2018`

`A Graph-to-Sequence Model for AMR-to-Text Generation
<https://www.aclweb.org/anthology/P18-1150>`_
    | :author:`Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea`
    | :venue:`ACL 2018`

`Graph-to-Sequence Learning using Gated Graph Neural Networks
<https://www.aclweb.org/anthology/P18-1026>`_
    | :author:`Daniel Beck, Gholamreza Haffari, Trevor Cohn`
    | :venue:`ACL 2018`

`Graph Convolutional Networks for Text Classification
<https://arxiv.org/pdf/1809.05679.pdf>`_
    | :author:`Liang Yao, Chengsheng Mao, Yuan Luo`
    | :venue:`AAAI 2019`

`Differentiable Perturb-and-Parse: Semi-Supervised Parsing with a Structured Variational Autoencoder
<https://openreview.net/pdf?id=BJlgNh0qKQ>`_
    | :author:`Caio Corro, Ivan Titov`
    | :venue:`ICLR 2019.`

`Structured Neural Summarization
<https://arxiv.org/pdf/1811.01824.pdf>`_
    | :author:`Patrick Fernandes, Miltiadis Allamanis, Marc Brockschmid`
    | :venue:`ICLR 2019`

`Multi-task Learning over Graph Structures
<https://arxiv.org/pdf/1811.10211.pdf>`_
    | :author:`Pengfei Liu, Jie Fu, Yue Dong, Xipeng Qiu, Jackie Chi Kit Cheung`
    | :venue:`AAAI 2019`

`Imposing Label-Relational Inductive Bias for Extremely Fine-Grained Entity Typing
<https://arxiv.org/pdf/1903.02591.pdf>`_
    | :author:`Wenhan Xiong, Jiawei Wu, Deren Lei, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang`
    | :venue:`NAACL 2019`

`Single Document Summarization as Tree Induction
<https://www.aclweb.org/anthology/N19-1173>`_
    | :author:`Yang Liu, Ivan Titov, Mirella Lapata`
    | :venue:`NAACL 2019`

`Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks
<https://arxiv.org/pdf/1903.01306.pdf>`_
    | :author:`Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, Huajun Chen`
    | :venue:`NAACL 2019`

`Graph Neural Networks with Generated Parameters for Relation Extraction
<https://arxiv.org/pdf/1902.00756.pdf>`_
    | :author:`Hao Zhu, Yankai Lin, Zhiyuan Liu, Jie Fu, Tat-seng Chua, Maosong Sun`
    | :venue:`ACL 2019`

`Dynamically Fused Graph Network for Multi-hop Reasoning
<https://arxiv.org/pdf/1905.06933.pdf>`_
    | :author:`Yunxuan Xiao, Yanru Qu, Lin Qiu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu`
    | :venue:`ACL 2019`

`Encoding Social Information with Graph Convolutional Networks for Political Perspective Detection
in News Media
<https://www.cs.purdue.edu/homes/dgoldwas//downloads/papers/LiG_acl_2019.pdf>`_
    | :author:`Chang Li, Dan Goldwasser`
    | :venue:`ACL 2019`

`Attention Guided Graph Convolutional Networks for Relation Extraction
<https://arxiv.org/pdf/1906.07510.pdf>`_
    | :author:`Zhijiang Guo, Yan Zhang, Wei Lu`
    | :venue:`ACL 2019`

`Incorporating Syntactic and Semantic Information in Word Embeddings using Graph Convolutional Networks
<https://arxiv.org/pdf/1809.04283.pdf>`_
    | :author:`Shikhar Vashishth, Manik Bhandari, Prateek Yadav, Piyush Rai, Chiranjib Bhattacharyya, Partha Talukdar`
    | :venue:`ACL 2019`

`GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction
<https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf>`_
    | :author:`Tsu-Jui Fu, Peng-Hsuan Li, Wei-Yun Ma`
    | :venue:`ACL 2019`

`Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs
<https://arxiv.org/pdf/1905.07374.pdf>`_
    | :author:`Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou`
    | :venue:`ACL 2019`

`Cognitive Graph for Multi-Hop Reading Comprehension at Scale
<https://arxiv.org/pdf/1905.05460.pdf>`_
    | :author:`Ming Ding, Chang Zhou, Qibin Chen, Hongxia Yang, Jie Tang`
    | :venue:`ACL 2019`

`Coherent Comment Generation for Chinese Articles with a Graph-to-Sequence Model
<https://arxiv.org/pdf/1906.01231.pdf>`_
    | :author:`Wei Li, Jingjing Xu, Yancheng He, Shengli Yan, Yunfang Wu, Xu Sun`
    | :venue:`ACL 2019`

`Matching Article Pairs with Graphical Decomposition and Convolutions
<https://arxiv.org/pdf/1802.07459.pdf>`_
    | :author:`Bang Liu, Di Niu, Haojie Wei, Jinghong Lin, Yancheng He, Kunfeng Lai, Yu Xu`
    | :venue:`ACL 2019`

`Embedding Imputation with Grounded Language Information
<https://arxiv.org/pdf/1906.03753.pdf>`_
    | :author:`Ziyi Yang, Chenguang Zhu, Vin Sachidananda, Eric Darve`
    | :venue:`ACL 2019`

`Look Again at the Syntax: Relational Graph Convolutional Network for Gendered Ambiguous Pronoun Resolution
<https://arxiv.org/pdf/1905.08868.pdf>`_
    | :author:`Yinchuan Xu, Junlin Yang`
    | :venue:`ACL 2019 Workshop`
    | :keyword:`https://github.com/ianycxu/RGCN-with-BERT`

`Learning Graph Pooling and Hybrid Convolutional Operations for Text Representations
<https://arxiv.org/pdf/1901.06965.pdf>`_
    | :author:`Hongyang Gao, Yongjun Chen, Shuiwang Ji`
    | :venue:`WWW 2019`

Computer Vision
---------------

`3D Graph Neural Networks for RGBD Semantic Segmentation
<http://www.cs.toronto.edu/~rjliao/papers/iccv_2017_3DGNN.pdf>`_
    | :author:`Xiaojuan Qi, Renjie Liao, Jiaya Jia, Sanja Fidler, Raquel Urtasun`
    | :venue:`ICCV 2017`

`Situation Recognition With Graph Neural Networks
<https://arxiv.org/abs/1708.04320>`_
    | :author:`Ruiyu Li, Makarand Tapaswi, Renjie Liao, Jiaya Jia, Raquel Urtasun, Sanja Fidler`
    | :venue:`ICCV 2017`

`Graph-Based Classification of Omnidirectional Images
<https://arxiv.org/abs/1707.08301>`_
    | :author:`Renata Khasanova, Pascal Frossard`
    | :venue:`ICCV 2017`

`Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition
<https://arxiv.org/abs/1801.07455>`_
    | :author:`Sijie Yan, Yuanjun Xiong, Dahua Lin`
    | :venue:`AAAI 2018`

`Image Generation from Scene Graphs
<https://arxiv.org/abs/1804.01622>`_
    | :author:`Justin Johnson, Agrim Gupta, Li Fei-Fei`
    | :venue:`CVPR 2018`

`FoldingNet: Point Cloud Auto-Encoder via Deep Grid Deformation
<https://arxiv.org/abs/1712.07262>`_
    | :author:`Yaoqing Yang, Chen Feng, Yiru Shen, Dong Tian`
    | :venue:`CVPR 2018`

`PPFNet: Global Context Aware Local Features for Robust 3D Point Matching
<https://arxiv.org/abs/1802.02669>`_
    | :author:`Haowen Deng, Tolga Birdal, Slobodan Ilic`
    | :venue:`CVPR 2018`

`Iterative Visual Reasoning Beyond Convolutions
<https://arxiv.org/abs/1803.11189>`_
    | :author:`Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta`
    | :venue:`CVPR 2018`

`Surface Networks
<https://arxiv.org/abs/1705.10819>`_
    | :author:`Ilya Kostrikov, Zhongshi Jiang, Daniele Panozzo, Denis Zorin, Joan Bruna`
    | :venue:`CVPR 2018`

`FeaStNet: Feature-Steered Graph Convolutions for 3D Shape Analysis
<https://arxiv.org/abs/1706.05206>`_
    | :author:`Nitika Verma, Edmond Boyer, Jakob Verbeek`
    | :venue:`CVPR 2018`

`Learning to Act Properly: Predicting and Explaining Affordances From Images
<https://arxiv.org/abs/1712.07576>`_
    | :author:`Ching-Yao Chuang, Jiaman Li, Antonio Torralba, Sanja Fidler`
    | :venue:`CVPR 2018`

`Mining Point Cloud Local Structures by Kernel Correlation and Graph Pooling
<https://arxiv.org/abs/1712.06760>`_
    | :author:`Yiru Shen, Chen Feng, Yaoqing Yang, Dong Tian`
    | :venue:`CVPR 2018`

`Deformable Shape Completion With Graph Convolutional Autoencoders
<https://arxiv.org/abs/1712.00268>`_
    | :author:`Or Litany, Alex Bronstein, Michael Bronstein, Ameesh Makadia`
    | :venue:`CVPR 2018`

`Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images
<https://arxiv.org/abs/1804.01654>`_
    | :author:`Nanyang Wang, Yinda Zhang, Zhuwen Li, Yanwei Fu, Wei Liu, Yu-Gang Jiang`
    | :venue:`ECCV 2018`

`Learning Human-Object Interactions by Graph Parsing Neural Networks
<https://arxiv.org/abs/1808.07962>`_
    | :author:`Siyuan Qi, Wenguan Wang, Baoxiong Jia, Jianbing Shen, Song-Chun Zhu`
    | :venue:`ECCV 2018`

`Generating 3D Faces using Convolutional Mesh Autoencoders
<https://arxiv.org/abs/1807.10267>`_
    | :author:`Anurag Ranjan, Timo Bolkart, Soubhik Sanyal, Michael J. Black`
    | :venue:`ECCV 2018`

`Learning SO(3) Equivariant Representations with Spherical CNNs
<https://arxiv.org/abs/1711.06721>`_
    | :author:`Carlos Esteves, Christine Allen-Blanchette, Ameesh Makadia, Kostas Daniilidis`
    | :venue:`ECCV 2018`

`Neural Graph Matching Networks for Fewshot 3D Action Recognition
<http://openaccess.thecvf.com/content_ECCV_2018/papers/Michelle_Guo_Neural_Graph_Matching_ECCV_2018_paper.pdf>`_
    | :author:`Michelle Guo, Edward Chou, De-An Huang, Shuran Song, Serena Yeung, Li Fei-Fei`
    | :venue:`ECCV 2018`

`Multi-Kernel Diffusion CNNs for Graph-Based Learning on Point Clouds
<https://arxiv.org/abs/1809.05370>`_
    | :author:`Lasse Hansen, Jasper Diesel, Mattias P. Heinrich`
    | :venue:`ECCV 2018`

`Hierarchical Video Frame Sequence Representation with Deep Convolutional Graph Network
<https://arxiv.org/abs/1906.00377>`_
    | :author:`Feng Mao, Xiang Wu, Hui Xue, Rong Zhang`
    | :venue:`ECCV 2018`

`Graph R-CNN for Scene Graph Generation
<https://arxiv.org/abs/1808.00191>`_
    | :author:`Jianwei Yang, Jiasen Lu, Stefan Lee, Dhruv Batra, Devi Parikh`
    | :venue:`ECCV 2018`

`Exploring Visual Relationship for Image Captioning
<https://arxiv.org/abs/1809.07041>`_
    | :author:`Ting Yao, Yingwei Pan, Yehao Li, Tao Mei`
    | :venue:`ECCV 2018`

`Beyond Grids: Learning Graph Representations for Visual Recognition
<https://papers.nips.cc/paper/8135-beyond-grids-learning-graph-representations-for-visual-recognition>`_
    | :author:`Yin Li, Abhinav Gupta`
    | :venue:`NeurIPS 2018`

`Learning Conditioned Graph Structures for Interpretable Visual Question Answering
<https://arxiv.org/abs/1806.07243>`_
    | :author:`Will Norcliffe-Brown, Efstathios Vafeias, Sarah Parisot`
    | :venue:`NeurIPS 2018`

`LinkNet: Relational Embedding for Scene Graph
<https://arxiv.org/abs/1811.06410>`_
    | :author:`Sanghyun Woo, Dahun Kim, Donghyeon Cho, In So Kweon`
    | :venue:`NeurIPS 2018`

`Flexible Neural Representation for Physics Prediction
<https://arxiv.org/abs/1806.08047>`_
    | :author:`Damian Mrowca, Chengxu Zhuang, Elias Wang, Nick Haber, Li Fei-Fei,
        Joshua B. Tenenbaum, Daniel L. K. Yamins`
    | :venue:`NeurIPS 2018`

`Learning Localized Generative Models for 3D Point Clouds via Graph Convolution
<https://openreview.net/forum?id=SJeXSo09FQ>`_
    | :author:`Diego Valsesia, Giulia Fracastoro, Enrico Magli`
    | :venue:`ICLR 2019`

`Graph-Based Global Reasoning Networks
<https://arxiv.org/abs/1811.12814>`_
    | :author:`Yunpeng Chen, Marcus Rohrbach, Zhicheng Yan, Shuicheng Yan, Jiashi Feng, Yannis Kalantidis`
    | :venue:`CVPR 2019`

`Deep Graph Laplacian Regularization for Robust Denoising of Real Images
<https://arxiv.org/abs/1807.11637>`_
    | :author:`Jin Zeng, Jiahao Pang, Wenxiu Sun, Gene Cheung`
    | :venue:`CVPR 2019`

`Learning Context Graph for Person Search
<https://arxiv.org/abs/1904.01830>`_
    | :author:`Yichao Yan, Qiang Zhang, Bingbing Ni, Wendong Zhang, Minghao Xu, Xiaokang Yang`
    | :venue:`CVPR 2019`

`Graphonomy: Universal Human Parsing via Graph Transfer Learning
<https://arxiv.org/abs/1904.04536>`_
    | :author:`Ke Gong, Yiming Gao, Xiaodan Liang, Xiaohui Shen, Meng Wang, Liang Lin`
    | :venue:`CVPR 2019`

`Masked Graph Attention Network for Person Re-Identification
<http://openaccess.thecvf.com/content_CVPRW_2019/html/TRMTMCT/Bao_Masked_Graph_Attention_Network_
for_Person_Re-Identification_CVPRW_2019_paper.html>`_
    | :author:`Liqiang Bao, Bingpeng Ma, Hong Chang, Xilin Chen`
    | :venue:`CVPR 2019`

`Learning to Cluster Faces on an Affinity Graph
<https://arxiv.org/abs/1904.02749>`_
    | :author:`Lei Yang, Xiaohang Zhan, Dapeng Chen, Junjie Yan, Chen Change Loy, Dahua Lin`
    | :venue:`CVPR 2019`

`Actional-Structural Graph Convolutional Networks for Skeleton-Based Action Recognition
<https://arxiv.org/abs/1904.12659>`_
    | :author:`Maosen Li, Siheng Chen, Xu Chen, Ya Zhang, Yanfeng Wang, Qi Tian`
    | :venue:`CVPR 2019`

`Adaptively Connected Neural Networks
<https://arxiv.org/abs/1904.03579>`_
    | :author:`Guangrun Wang, Keze Wang, Liang Lin`
    | :venue:`CVPR 2019`

`Reasoning Visual Dialogs with Structural and Partial Observations
<https://arxiv.org/abs/1904.03579>`_
    | :author:`Zilong Zheng, Wenguan Wang, Siyuan Qi, Song-Chun Zhu`
    | :venue:`CVPR 2019`

`MeshCNN: A Network with an Edge
<https://arxiv.org/pdf/1809.05910.pdf>`_
    | :author:`Rana Hanocka, Amir Hertz, Noa Fish, Raja Giryes, Shachar Fleishman, Daniel Cohen-Or`
    | :venue:`SIGGRAPH 2019`
    | :keyword:`https://ranahanocka.github.io/MeshCNN/`

Recommender Systems
-------------------

`Graph Convolutional Neural Networks for Web-Scale Recommender Systems
<https://arxiv.org/pdf/1806.01973.pdf>`_
    | :author:`Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec`
    | :venue:`KDD 2018`
    | :keyword:`PinSage`

`SocialGCN: An Efficient Graph Convolutional Network based Model for Social Recommendation
<https://arxiv.org/pdf/1811.02815.pdf>`_
    | :author:`Le Wu, Peijie Sun, Richang Hong, Yanjie Fu, Xiting Wang, Meng Wang`
    | :venue:`AAAI 2018`
    | :keyword:`GCN, Social recommendation`

`Session-based Social Recommendation via Dynamic Graph Attention Networks
<https://arxiv.org/pdf/1902.09362.pdf>`_
    | :author:`Weiping Song, Zhiping Xiao, Yifan Wang, Laurent Charlin, Ming Zhang, Jian Tang`
    | :venue:`WSDM 2019`
    | :keyword:`Social recommendation, session-based, GAT`

`Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in
Recommender Systems
<https://arxiv.org/pdf/1903.10433.pdf>`_
    | :author:`Qitian Wu, Hengrui Zhang, Xiaofeng Gao, Peng He, Paul Weng, Han Gao, Guihai Chen`
    | :venue:`WWW 2019`
    | :keyword:`Social recommendation, GAT`

`Graph Neural Networks for Social Recommendation
<https://arxiv.org/pdf/1902.07243.pdf>`_
    | :author:`Wenqi Fan, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang, Dawei Yin`
    | :venue:`WWW 2019`
    | :keyword:`Social recommendation, GNN`

`Session-based Recommendation with Graph Neural Networks
<https://arxiv.org/pdf/1811.00855.pdf>`_
    | :author:`Shu Wu, Yuyuan Tang, Yanqiao Zhu, Liang Wang, Xing Xie, Tieniu Tan`
    | :venue:`AAAI 2019`
    | :keyword:`Session-based recommendation, GNN`

`A Neural Influence Diffusion Model for Social Recommendation
<https://arxiv.org/pdf/1904.10322.pdf>`_
    | :author:`Le Wu, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang, Meng Wang`
    | :venue:`SIGIR 2019`
    | :keyword:`Social Recommendation, diffusion`

`Neural Graph Collaborative Filtering
<https://arxiv.org/pdf/1905.08108.pdf>`_
    | :author:`Xiang Wang, Xiangnan He, Meng Wang, Fuli Feng, Tat-Seng Chua`
    | :venue:`SIGIR 2019`
    | :keyword:`Collaborative Filtering, GNN`

`Binarized Collaborative Filtering with Distilling Graph Convolutional Networks
<https://arxiv.org/pdf/1906.01829.pdf>`_
    | :author:`Haoyu Wang, Defu Lian, Yong Ge`
    | :venue:`IJCAI 2019`

Link Prediction
---------------

`Link Prediction Based on Graph Neural Networks
<https://papers.nips.cc/paper/7763-link-prediction-based-on-graph-neural-networks.pdf>`_
    | :author:`Muhan Zhang, Yixin Chen`
    | :venue:`NeurIPS 2018`

`Link Prediction via Subgraph Embedding-Based Convex Matrix Completion
<http://iiis.tsinghua.edu.cn/~weblt/papers/link-prediction-subgraphembeddings.pdf>`_
    | :author:`Zhu Cao, Linlin Wang, Gerard de Melo`
    | :venue:`AAAI 2018`

`Graph Convolutional Matrix Completion
<https://www.kdd.org/kdd2018/files/deep-learning-day/DLDay18_paper_32.pdf>`_
    | :author:`Rianne van den Berg, Thomas N. Kipf, Max Welling`
    | :venue:`KDD 2018 Workshop`

Influence Prediction
--------------------

`DeepInf: Social Influence Prediction with Deep Learning
<https://arxiv.org/pdf/1807.05560.pdf>`_
    | :author:`Jiezhong Qiu, Jian Tang, Hao Ma, Yuxiao Dong, Kuansan Wang, Jie Tang`
    | :venue:`KDD 2018`

`Estimating Node Importance in Knowledge Graphs Using Graph Neural Networks
<https://arxiv.org/pdf/1905.08865.pdf>`_
    | :author:`Namyong Park, Andrey Kan, Xin Luna Dong, Tong Zhao, Christos Faloutsos`
    | :venue:`KDD 2019`

Neural Architecture Search
--------------------------

`Graph HyperNetworks for Neural Architecture Search
<https://openreview.net/pdf?id=rkgW0oA9FX>`_
    | :author:`Chris Zhang, Mengye Ren, Raquel Urtasun`
    | :venue:`ICLR 2019`

Reinforcement Learning
----------------------

`Action Schema Networks: Generalised Policies with Deep Learning
<https://arxiv.org/pdf/1709.04271.pdf>`_
    | :author:`Sam Toyer, Felipe Trevizan, Sylvie Thiebaux, Lexing Xie`
    | :venue:`AAAI 2018`

`NerveNet: Learning Structured Policy with Graph Neural Networks
<https://openreview.net/pdf?id=S1sqHMZCb>`_
    | :author:`Tingwu Wang, Renjie Liao, Jimmy Ba, Sanja Fidler`
    | :venue:`ICLR 2018`

`Graph Networks as Learnable Physics Engines for Inference and Control
<https://arxiv.org/pdf/1806.01242.pdf>`_
    | :author:`Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel,
        Martin Riedmiller`
    | :venue:`ICML 2018`

`Learning Policy Representations in Multiagent Systems
<https://arxiv.org/pdf/1806.06464.pdf>`_
    | :author:`Aditya Grover, Maruan Al-Shedivat, Jayesh K. Gupta, Yura Burda, Harrison Edwards`
    | :venue:`ICML 2018`

`Relational recurrent neural networks
<https://papers.nips.cc/paper/7960-relational-recurrent-neural-networks.pdf>`_
    | :author:`Adam Santoro,  Ryan Faulkner, David Raposo, Jack Rae, Mike Chrzanowski,Théophane Weber,
        Daan Wierstra, Oriol Vinyals, Razvan Pascanu, Timothy Lillicrap`
    | :venue:`NeurIPS 2018`

`Transfer of Deep Reactive Policies for MDP Planning
<http://www.cse.iitd.ac.in/~mausam/papers/nips18.pdf>`_
    | :author:`Aniket Bajpai, Sankalp Garg, Mausam`
    | :venue:`NeurIPS 2018`

`Neural Graph Evolution: Towards Efficient Automatic Robot Design
<https://openreview.net/pdf?id=BkgWHnR5tm>`_
    | :author:`Tingwu Wang, Yuhao Zhou, Sanja Fidler, Jimmy Ba`
    | :venue:`ICLR 2019`

Combinatorial Optimization
--------------------------

`Combinatorial Optimization with Graph Convolutional Networks and Guided Tree Search
<https://arxiv.org/abs/1810.10659>`_
    | :author:`Zhuwen Li, Qifeng Chen, Vladlen Koltun`
    | :venue:`NeurIPS 2018`

`Reinforcement Learning for Solving the Vehicle Routing Problem
<https://arxiv.org/abs/1802.04240>`_
    | :author:`Mohammadreza Nazari, Afshin Oroojlooy, Lawrence V. Snyder, Martin Takáč`
    | :venue:`NeurIPS 2018`

Adversarial Attack and Robustness
------------------

`Adversarial Attack on Graph Structured Data
<https://arxiv.org/abs/1806.02371>`_
    | :author:`Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, Le Song`
    | :venue:`ICML 2018`

`Adversarial Attacks on Neural Networks for Graph Data
<https://arxiv.org/abs/1805.07984>`_
    | :author:`Daniel Zügner, Amir Akbarnejad, Stephan Günnemann`
    | :venue:`KDD 2018`

`Adversarial Attacks on Graph Neural Networks via Meta Learning
<https://arxiv.org/abs/1902.08412>`_
    | :author:`Daniel Zügner, Stephan Günnemann`
    | :venue:`ICLR 2019`

`Robust Graph Convolutional Networks Against Adversarial Attacks
<http://pengcui.thumedialab.com/papers/RGCN.pdf>`_
    | :author:`Dingyuan Zhu, Ziwei Zhang, Peng Cui, Wenwu Zhu`
    | :venue:`KDD 2019`

`Certifiable Robustness and Robust Training for Graph Convolutional Networks
<https://arxiv.org/pdf/1906.12269.pdf>`_
    | :author:`Daniel Zügner, Stephan Günnemann`
    | :venue:`KDD 2019`

Meta Learning
-------------

`Learning Steady-States of Iterative Algorithms over Graphs
<http://proceedings.mlr.press/v80/dai18a.html>`_
    | :author:`Hanjun Dai, Zornitsa Kozareva, Bo Dai, Alex Smola, Le Song`
    | :venue:`ICML 2018`


Structure Learning
------------------

`Few-Shot Learning with Graph Neural Networks
<https://arxiv.org/abs/1711.04043>`_
    | :author:`Victor Garcia, Joan Bruna`
    | :venue:`ICLR 2018`

`Neural Relational Inference for Interacting Systems
<https://arxiv.org/abs/1802.04687>`_
    | :author:`Thomas Kipf, Ethan Fetaya, Kuan-Chieh Wang, Max Welling, Richard Zemel`
    | :venue:`ICML 2018`

`Brain Signal Classification via Learning Connectivity Structure
<https://arxiv.org/abs/1905.11678>`_
    | :author:`Soobeom Jang, Seong-Eun Moon, Jong-Seok Lee`
    | :venue:`arXiv 1905`

`A Flexible Generative Framework for Graph-based Semi-supervised Learning
<https://arxiv.org/abs/1905.10769>`_
    | :author:`Jiaqi Ma, Weijing Tang, Ji Zhu, Qiaozhu Mei`
    | :venue:`arXiv 1905`

`Joint embedding of structure and features via graph convolutional networks
<https://arxiv.org/abs/1905.08636>`_
    | :author:`Sébastien Lerique, Jacob Levy Abitbol, Márton Karsai`
    | :venue:`arXiv 1905`

`Variational Spectral Graph Convolutional Networks
<https://arxiv.org/abs/1906.01852>`_
    | :author:`Louis Tiao, Pantelis Elinas, Harrison Nguyen, Edwin V. Bonilla`
    | :venue:`arXiv 1906`

`Learning to Propagate Labels: Transductive Propagation Network for Few-shot Learning
<https://arxiv.org/abs/1805.10002>`_
    | :author:`Yanbin Liu, Juho Lee, Minseop Park, Saehoon Kim, Eunho Yang, Sung Ju Hwang, Yi Yang`
    | :venue:`ICLR 2019`

`Graph Learning Network: A Structure Learning Algorithm
<https://arxiv.org/abs/1905.12665>`_
    | :author:`Darwin Saire Pilco, Adín Ramírez Rivera`
    | :venue:`ICML 2019 Workshop`

`Learning Discrete Structures for Graph Neural Networks
<https://arxiv.org/abs/1903.11960>`_
    | :author:`Luca Franceschi, Mathias Niepert, Massimiliano Pontil, Xiao He`
    | :venue:`ICML 2019`

`Graphite: Iterative Generative Modeling of Graphs
<https://arxiv.org/abs/1803.10459>`_
    | :author:`Aditya Grover, Aaron Zweig, Stefano Ermon`
    | :venue:`ICML 2019`

Bioinformatics and Chemistry
--------------

`Protein Interface Prediction using Graph Convolutional Networks
<https://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks.pdf>`_
    | :author:`Alex Fout, Jonathon Byrd, Basir Shariat, Asa Ben-Hur`
    | :venue:`NeurIPS 2017`

`Modeling Polypharmacy Side Effects with Graph Convolutional Networks
<https://arxiv.org/abs/1802.00543>`_
    | :author:`Marinka Zitnik, Monica Agrawal, Jure Leskovec`
    | :venue:`Bioinformatics 2018`

`NeoDTI: Neural Integration of Neighbor Information from a Heterogeneous Network for Discovering New
Drug–target Interactions
<https://academic.oup.com/bioinformatics/article-abstract/35/1/104/5047760?redirectedFrom=fulltext>`_
    | :author:`Fangping Wan, Lixiang Hong, An Xiao, Tao Jiang, Jianyang Zeng`
    | :venue:`Bioinformatics 2018`

`SELFIES: a Robust Representation of Semantically Constrained Graphs with an Example Application in Chemistry
<https://arxiv.org/pdf/1905.13741.pdf>`_
    | :author:`Mario Krenn, Florian Häse, AkshatKumar Nigam, Pascal Friederich, Alán Aspuru-Guzik`
    | :venue:`arXiv 1905`

`Drug-Drug Adverse Effect Prediction with Graph Co-Attention
<https://arxiv.org/pdf/1905.00534.pdf>`_
    | :author:`Andreea Deac, Yu-Hsiang Huang, Petar Veličković, Pietro Liò, Jian Tang`
    | :venue:`arXiv 1905`

`GCN-MF: Disease-Gene Association Identification By Graph Convolutional Networks and Matrix Factorization
<https://www.kdd.org/kdd2019/accepted-papers/view/gcn-mf-disease-gene-association-identification-by-graph-convolutional-netwo>`_
    | :author:`Peng Han, Peng Yang, Peilin Zhao, Shuo Shang, Yong Liu, Jiayu Zhou, Xin Gao, Panos Kalnis`
    | :venue:`KDD 2019`

`Detecting drug-drug interactions using artificial neural networks and classic graph similarity measures
<https://arxiv.org/pdf/1903.04571.pdf>`_
    | :author:`Guy Shtar, Lior Rokach, Bracha Shapira`
    | :venue:`arXiv 1903`

`PGCN: Disease gene prioritization by disease and gene embedding through graph convolutional neural networks
<https://www.biorxiv.org/content/biorxiv/early/2019/01/28/532226.full.pdf>`_
    | :author:`Yu Li, Hiroyuki Kuwahara, Peng Yang, Le Song, Xin Gao`
    | :venue:`bioRxiv 2019`

`Identifying Protein-Protein Interaction using Tree LSTM and Structured Attention
<https://ieeexplore.ieee.org/abstract/document/8665584>`_
    | :author:`Mahtab Ahmed, Jumayel Islam, Muhammad Rifayat Samee, Robert E. Mercer`
    | :venue:`ICSC 2019`

Theorem Proving
---------------

`Premise Selection for Theorem Proving by Deep Graph Embedding
<https://arxiv.org/abs/1709.09994>`_
    | :author:`Mingzhe Wang, Yihe Tang, Jian Wang, Jia Deng`
    | :venue:`NeurIPS 2017`

Graph Generation
================

`GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models
<https://arxiv.org/abs/1802.08773>`_
    | :author:`Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec`
    | :venue:`ICML 2018`

`NetGAN: Generating Graphs via Random Walks
<https://arxiv.org/abs/1803.00816>`_
    | :author:`Aleksandar Bojchevski, Oleksandr Shchur, Daniel Zügner, Stephan Günnemann`
    | :venue:`ICML 2018`

`Learning Deep Generative Models of Graphs
<https://arxiv.org/abs/1803.03324>`_
    | :author:`Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia`
    | :venue:`ICML 2018`

`Junction Tree Variational Autoencoder for Molecular Graph Generation
<https://arxiv.org/abs/1802.04364>`_
    | :author:`Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICML 2018`

`MolGAN: An implicit generative model for small molecular graphs
<https://arxiv.org/abs/1805.11973>`_
    | :author:`Nicola De Cao, Thomas Kipf`
    | :venue:`arXiv 1805`

`Generative Modeling for Protein Structures
<https://papers.nips.cc/paper/7978-generative-modeling-for-protein-structures.pdf>`_
    | :author:`Namrata Anand, Po-Ssu Huang`
    | :venue:`NeurIPS 2018`

`Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders
<https://arxiv.org/abs/1809.02630>`_
    | :author:`Tengfei Ma, Jie Chen, Cao Xiao`
    | :venue:`NeurIPS 2018`

`Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation
<https://arxiv.org/abs/1806.02473>`_
    | :author:`Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec`
    | :venue:`NeurIPS 2018`

`Constrained Graph Variational Autoencoders for Molecule Design
<https://arxiv.org/abs/1805.09076>`_
    | :author:`Qi Liu, Miltiadis Allamanis, Marc Brockschmidt, Alexander L. Gaunt`
    | :venue:`NeurIPS 2018`

`Learning Multimodal Graph-to-Graph Translation for Molecule Optimization
<https://arxiv.org/abs/1812.01070>`_
    | :author:`Wengong Jin, Kevin Yang, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICLR 2019`

`Generative Code Modeling with Graphs
<https://openreview.net/forum?id=Bke4KsA5FX>`_
    | :author:`Marc Brockschmidt, Miltiadis Allamanis, Alexander L. Gaunt, Oleksandr Polozov`
    | :venue:`ICLR 2019`

`DAG-GNN: DAG Structure Learning with Graph Neural Networks
<https://arxiv.org/abs/1904.10098>`_
    | :author:`Yue Yu, Jie Chen, Tian Gao, Mo Yu`
    | :venue:`ICML 2019`

`Graph to Graph: a Topology Aware Approach for Graph Structures Learning and Generation
<http://proceedings.mlr.press/v89/sun19c.html>`_
    | :author:`Mingming Sun, Ping Li`
    | :venue:`AISTATS 2019`


Graph Layout and High-dimensional Data Visualization
====================================================

`Visualizing Data using t-SNE
<http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf>`_
    | :author:`Laurens van der Maaten, Geoffrey Hinton`
    | :venue:`JMLR 2008`

`Visualizing non-metric similarities in multiple maps
<https://link.springer.com/content/pdf/10.1007/s10994-011-5273-4.pdf>`_
    | :author:`Laurens van der Maaten, Geoffrey Hinton`
    | :venue:`ML 2012`

`Visualizing Large-scale and High-dimensional Data
<https://arxiv.org/pdf/1602.00370>`_
    | :author:`Jian Tang, Jingzhou Liu, Ming Zhang, Qiaozhu Mei`
    | :venue:`WWW 2016`

`GraphTSNE: A Visualization Technique for Graph-Structured Data
<https://arxiv.org/pdf/1904.06915.pdf>`_
    | :author:`Yao Yang Leow, Thomas Laurent, Xavier Bresson`
    | :venue:`ICLR 2019 Workshop`

Graph Representation Learning Systems
=====================================

`GraphVite: A High-Performance CPU-GPU Hybrid System for Node Embedding
<https://arxiv.org/pdf/1903.00757>`_
    | :author:`Zhaocheng Zhu, Shizhen Xu, Meng Qu, Jian Tang`
    | :venue:`WWW 2019`

`PyTorch-BigGraph: A Large-scale Graph Embedding System
<https://arxiv.org/pdf/1903.12287>`_
    | :author:`Adam Lerer, Ledell Wu, Jiajun Shen, Timothee Lacroix, Luca Wehrstedt,
        Abhijit Bose, Alex Peysakhovich`
    | :venue:`SysML 2019`

`AliGraph: A Comprehensive Graph Neural Network Platform
<https://arxiv.org/pdf/1902.08730>`_
    | :author:`Rong Zhu, Kun Zhao, Hongxia Yang, Wei Lin, Chang Zhou, Baole Ai,
        Yong Li, Jingren Zhou`
    | :venue:`VLDB 2019`

`Deep Graph Library
<https://www.dgl.ai>`_
    | :author:`DGL Team`

`AmpliGraph
<https://github.com/Accenture/AmpliGraph>`_
    | :author:`Luca Costabello, Sumit Pai, Chan Le Van, Rory McGrath, Nicholas McCarthy, Pedro Tabacof`

`Euler
<https://github.com/alibaba/euler>`_
    | :author:`Alimama Engineering Platform Team, Alimama Search Advertising Algorithm Team`

Datasets
========
