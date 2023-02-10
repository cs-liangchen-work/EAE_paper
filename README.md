# EE
ee paper 
based on https://github.com/carrie0307/DL_EventExtractionPapers.

在自己读文章的时候，感觉分类更重要了，按自己的想法，简单对22年6月以来读的文章进行分类。

只包含2020以来nlp3大主会的文章、

Event Extraction (EE) 是 Information Extraction (IE) 的一个分支，包含两个子任务：
  - Event Detection (ED): recognize event triggers
  - Event Argument Extraction (EAE): identify/recognize/extract/fill role

# DATASET
- [MAVEN: A Massive General Domain Event Detection Dataset](https://aclanthology.org/2020.emnlp-main.129/)
- [LEVEN: A Large-Scale Chinese Legal Event Detection Dataset](https://aclanthology.org/2022.findings-acl.17/)
- [Roles Across Multiple Sentences (RAMS)](https://nlp.jhu.edu/rams/)
- DuEE: A Large-Scale Dataset for Chinese Event Extraction in Real-World Scenarios
- MINION: a Large-Scale and Diverse Dataset for Multilingual Event Detection
- [Duee-fin: a document-level event extraction dataset in the financial domain released by baidu](https://aistudio.baidu.com/aistudio/competition/detail/46/0/task-definition)
- [MuCPAD: A Multi-Domain Chinese Predicate-Argument Dataset](https://arxiv.org/abs/2205.06703)
- [DocEE: A Large-Scale and Fine-grained Benchmark for Document-level Event Extraction](https://openreview.net/forum?id=rMMzsmmzHbq)
- [Event Extraction from Historical Texts: A New Dataset for Black Rebellions](https://aclanthology.org/2021.findings-acl.211/)
- [MAVEN: A Massive General Domain Event Detection Dataset](https://aclanthology.org/2020.emnlp-main.129/)
- [PHEE: A Dataset for Pharmacovigilance Event Extraction from Text](https://aclanthology.org/2022.emnlp-main.376/)
- [MEE: A Novel Multilingual Event Extraction Dataset](https://aclanthology.org/2022.emnlp-main.652/)

数据集研究：

- [BERTering RAMS: What and How Much does BERT Already Know About Event Arguments? - A Study on the RAMS Dataset](https://aclanthology.org/2020.blackboxnlp-1.1/)

# EAE:隐式事件抽取（event argument extraction）
### GEN-生成式
- arxiv2020: **Document-level Event-based Extraction Using Generative Template-filling Transformers**

  - Authors: Xinya Du, Alexander Rush, Claire Cardie
  - url: https://arxiv.org/abs/2008.09249

- NAACL2021: **Template Filling with Generative Transformers**

  - Authors: Xinya Du, Alexander Rush, Claire Cardie
  - url: https://aclanthology.org/2021.naacl-main.70/

- NAACL2021: **Document-Level Event Argument Extraction by Conditional Generation**

  - Authors: Sha Li, Heng Ji, Jiawei Han
  - url: https://www.aclweb.org/anthology/2021.naacl-main.69/

- ACL2022: Dynamic Prefix-Tuning for Generative Template-based Event Extraction

  - Authors: Xiao Liu, Heyan Huang, Ge Shi, Bo Wang
  - url: https://aclanthology.org/2022.acl-long.358

- ACL2022-findings: Event Transition Planning for Open-ended Text Generation

  - Authors: Qintong Li, Piji Li, Wei Bi, Zhaochun Ren, Yuxuan Lai, Lingpeng Kong
  - url: https://aclanthology.org/2022.findings-acl.269.pdf

- ACL2022: Multilingual Generative Language Models for Zero-Shot Cross-Lingual Event Argument Extraction

  - Authors: Kuan-Hao Huang, I-Hung Hsu, Prem Natarajan, Kai-Wei Chang, Nanyun Peng
  - url: https://aclanthology.org/2022.acl-long.317.pdf


- NAACL2022: DEGREE: A Data-Efficient Generation-Based Event Extraction Model

  - Authors: I-Hung Hsu, Kuan-Hao Huang, Elizabeth Boschee, Scott Miller, Prem Natarajan, Kai-Wei Chang, Nanyun Peng
  - url: https://arxiv.org/pdf/2108.12724.pdf


- NAACL2022-findings: EA2E: Improving Consistency with Event Awareness for Document-Level Argument Extraction

  - Authors: Qi Zeng, Qiusi Zhan, Heng Ji
  - url: https://arxiv.org/abs/2205.14847v1

- EACL2021: GRIT: Generative Role-filler Transformers for Document-level Event Entity Extraction

  - Authors: Xinya Du, Alexander M. Rush, Claire Cardie
  - url: https://arxiv.org/abs/2008.09249

- ACL2021： TEXT2EVENT: Controllable Sequence-to-Structure Generation for End-to-end Event Extraction

  - Authors: 
  - url: 

- ACL2021: Document-level Event Extraction via Parallel Prediction Networks

  - Authors: Hang Yang, Dianbo Sui, Yubo Chen, Kang Liu, Jun Zhao, Taifeng Wang
  - url: https://aclanthology.org/2021.acl-long.492/


### QA/MRC

- EMNLP2020: **Event Extraction by Answering (Almost) Natural Questions**

  - Authors: Xinya Du and Claire Cardie
  - url: https://arxiv.org/abs/2004.13625

- EMNLP2020: **Event Extraction as Machine Reading Comprehension**

  - Authors: Jian Liu, Yubo Chen, Kang Liu, Wei Bi and Xiaojiang Liu
  - url: https://www.aclweb.org/anthology/2020.emnlp-main.128/

- EMNLP2021: **Machine Reading Comprehension as Data Augmentation: A Case Study on Implicit Event Argument Extraction**

  - Authors: Jian Liu, Yufeng Chen, Jinan Xu
  - url: https://aclanthology.org/2021.emnlp-main.214.pdf


### Others span-based

- ACL2020: Multi-Sentence Argument Linking

  - Authors: Seth Ebner, Patrick Xia, Ryan Culkin, Kyle Rawlins, Benjamin Van DurmeA
  - url: https://www.aclweb.org/anthology/2020.acl-main.718/

- ACL2020: A Two-Step Approach for Implicit Event Argument Detection

  - Authors: Zhisong Zhang, Xiang Kong, Zhengzhong Liu, Xuezhe Ma and Eduard Hovy
  - url: https://www.aclweb.org/anthology/2020.acl-main.667/
  - code: https://github.com/zzsfornlp/zmsp



### Multi-Role

- ACL2022-findings: Query and Extract: Refining Event Extraction as Type-oriented Binary Decoding

  - Authors: Sijia Wang, Mo Yu, Shiyu Chang, Lichao Sun, Lifu Huang
  - url: https://arxiv.org/abs/2110.07476

- ACL2022: Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction

  - Authors: Yubo Ma, Zehao Wang, Yixin Cao, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao
  - url: https://aclanthology.org/2022.acl-long.466

- ACL2021: Capturing Event Argument Interaction via A Bi-Directional Entity-Level Recurrent Decoder
  
  - Author: Xi Xiangyu, Wei Ye, Shikun Zhang, Quanxiu Wang, Huixing Jiang, Wei Wu
  - url: https://aclanthology.org/2021.acl-long.18/

- EMNLP2020：Reading the Manual: Event Extraction as Definition Comprehension

  - Authors：Yunmo Chen, Tongfei Chen, Seth Ebner, Aaron Steven White, Benjamin Van Durme
  - url：https://aclanthology.org/2020.spnlp-1.9/
 
- ACL2021: Trigger is Not Sufficient: Exploiting Frame-aware Knowledge for Implicit Event Argument Extraction

  - Author: Kaiwen Wei, Xian Sun, Zequn Zhang, Jingyuan Zhang, Guo Zhi, Li Jin
  - url: https://aclanthology.org/2021.acl-long.360.pdf

### Multi-event

- NAACL2022-findings: EA2E: Improving Consistency with Event Awareness for Document-Level Argument Extraction

  - Authors: Qi Zeng, Qiusi Zhan, Heng Ji
  - url: https://arxiv.org/abs/2205.14847v1

- ACL2022: Dynamic Global Memory for Document-level Argument Extraction

  - Authors: Xinya Du, Sha Li, Heng Ji
  - url: https://aclanthology.org/2022.acl-long.361/

- NAACL2022: RAAT: Relation-Augmented Attention Transformer for Relation Modeling in Document-Level Event Extraction

  - Authors: Yuan Liang, Zhuoxuan Jiang, di yin, Bo Ren
  - url: https://arxiv.org/abs/2206.03377

- ACL2021：Document-level Event Extraction via Heterogeneous Graph-based Interaction Model with a Tracker

  - Author：Runxin Xu, Tianyu Liu, Lei Li, Baobao Chang
  - url：https://aclanthology.org/2021.acl-long.274/

- ACL2021: Document-level Event Extraction with Efficient End-to-end Learning of Cross-event Dependencies

  - Authors：
  - url：https://aclanthology.org/2021.nuse-1.4.pdf

### 图神经-GCN

- EMNLP2022: EventGraph: Event Extraction as Semantic Graph Parsing

  - Authors: Huiling You, David Samuel, Samia Touileb, Lilja Øvrelid
  - url: https://aclanthology.org/2022.case-1.2/



- ACL2021: Document-Level Event Argument Extraction via Optimal Transport

  - Authors: Amir Pouran Ben Veyseh, Minh Van Nguyen, Franck Dernoncourt, Bonan Min and Thien Huu Nguyen
  - url: https://aclanthology.org/2022.findings-acl.130/

- ACL2022-findings: A Graph Enhanced BERT Model for Event Prediction

  - Authors: Li Du, Xiao Ding, Yue Zhang, ting liu, Bing Qin
  - url: https://aclanthology.org/2022.findings-acl.206/

- ACL2022: MMEKG: Multi-modal Event Knowledge Graph towards Universal Representation across Modalities

  - Authors: Yubo Ma, Zehao Wang, Mukai Li, Yixin Cao, Meiqi Chen, Xinze Li, Wenqi Sun, Kunquan Deng, Kun Wang, Aixin Sun, Jing Shao
  - url: https://aclanthology.org/2022.acl-demo.23/

- NAACL2022: Event Schema Induction with Double Graph Autoencoders

  - Authors: Xiaomeng Jin, Manling Li, Heng Ji
  - url: https://blender.cs.illinois.edu/paper/schema2022.pdf

- NAACL2022: **A Two-Stream AMR-enhanced Model for Document-level Event Argument Extraction**

  - Authors: Runxin Xu, Peiyi Wang, Tianyu Liu, Shuang Zeng, Baobao Chang, Zhifang Sui
  - url: https://arxiv.org/abs/2205.00241
  - code：https://github.com/PKUnlp-icler/TSAR

- NAACL2022: Document-Level Event Argument Extraction by Leveraging Redundant Information and Closed Boundary Loss

  - Authors: Hanzhang Zhou, Kezhi Mao
  - url: https://openreview.net/forum?id=SclmqMGrb9

- EMNLP2021: The Future is not One-dimensional: Complex Event Schema Induction by Graph Modeling for Event Prediction

  - Authors: Manling Li, Sha Li, Zhenhailong Wang, Lifu Huang, Kyunghyun Cho, Heng Ji, Jiawei Han, Clare Voss
  - url: https://aclanthology.org/2021.emnlp-main.422.pdf

- ACL2021：Document-level Event Extraction via Heterogeneous Graph-based Interaction Model with a Tracker

  - Author：Runxin Xu, Tianyu Liu, Lei Li, Baobao Chang
  - url：https://aclanthology.org/2021.acl-long.274/

- EMNLP2020：Graph Transformer Networks with Syntactic and Semantic Structures for Event Argument Extraction

  - Author：Amir Pouran Ben Veyseh, Tuan Ngo Nguyen, Thien Huu Nguyen
  - url：https://aclanthology.org/2020.findings-emnlp.326/

### 多轮对话

- EMNLP2020：Event Extraction as Multi-turn Question Answering

  - Authors：Fayuan Li, Weihua Peng, Yuguang Chen, Quan Wang, Lu Pan, Yajuan Lyu, Yong Zhu
  - url：https://aclanthology.org/2020.findings-emnlp.73/

- EMNLP2020：Biomedical Event Extraction as Multi-turn Question Answering

  - Authors：Xing David Wang, Leon Weber, Ulf Leser
  - url：https://aclanthology.org/2020.louhi-1.10/

### Others
- NAACL2022-findings: Textual Entailment for Event Argument Extraction: Zero- and Few-Shot with Multi-Source Learning
  - 文本蕴含
  - Authors: Oscar Sainz, Itziar Gonzalez-Dios, Oier Lopez de Lacalle, Bonan Min, Eneko Agirre
  - url: https://arxiv.org/abs/2205.01376
  
- ACL2021: Zero-shot Event Extraction via Transfer Learning: Challenges and Insights

  - 文本蕴含
  - Authors: Qing Lyu, Hongming Zhang, Elior Sulem, Dan Roth
  - url: https://aclanthology.org/2021.acl-short.42/

- ACL2021-CLEVE: Contrastive Pre-training for Event Extraction
  
  - 对比学习
  - Authors：Ziqi Wang, Xiaozhi Wang, Xu Han, Yankai Lin, Lei Hou, Zhiyuan Liu, Peng Li, Juanzi Li, Jie Zhou
  - url：https://aclanthology.org/2021.acl-long.491/

- ACL2021: Modality and Negation in Event Extraction

  - Linguistic modality，依存树
  - Authors: Sander Bijl de Vroe, Liane Guillou, Miloš Stanojević, Nick McKenna, Mark Steedman
  - url: https://aclanthology.org/2021.case-1.6/


- ACL2021: ArgFuse: A Weakly-Supervised Framework for Document-Level Event Argument Aggregation

  - Event Argument Aggregation：先句子级别提取，再文档级别过滤、
  - Authors: Debanjana Kar, Sudeshna Sarkar, Pawan Goyal
  - url: https://aclanthology.org/2021.case-1.5/

- ACL2021：Document-level Event Extraction with Efficient End-to-end Learning of Cross-event Dependencies

  - joint learning event mention extraction, event coreference, and entity coreference
  - Authors：Kung-Hsiang Huang, Nanyun Peng
  - url：https://aclanthology.org/2021.nuse-1.4/

- ACL2020：Document-Level Event Role Filler Extraction using Multi-Granularity Contextualized Encoding

  - Multi-Granularity Contextualized Encoding：句子级 单个句子，文档集 多个句子一起的。
  - Authors: Xinya Du, Claire Cardie
  - url: https://aclanthology.org/2020.acl-main.714/


# DA：数据增强（Data Augmentation）

- ACL2022: ClarET: Pre-training a Correlation-Aware Context-To-Event Transformer for Event-Centric Generation and Classification

  - Authors: Yucheng Zhou, Tao Shen, Xiubo Geng, Guodong Long, Daxin Jiang
  - url: https://aclanthology.org/2022.acl-long.183/

- EMNLP2021: Corpus-based Open-Domain Event Type Induction

  - Authors: Jiaming Shen, Yunyi Zhang, Heng Ji, Jiawei Han
  - url: https://aclanthology.org/2021.emnlp-main.441.pdf

- EMNLP2020: Resource-Enhanced Neural Model for Event Argument Extraction

  - Authors: Jie Ma, Shuai Wang, Rishita Anubhai, Miguel Ballesteros, Yaser Al-Onaizan
  - url: https://aclanthology.org/2020.findings-emnlp.318/

- EMNLP2019：Exploring Pre-trained Language Models for Event Extraction and Generation

  - Authors: Sen Yang, Dawei Feng, Linbo Qiao, Zhigang Kan, Dongsheng Li
  - url: https://aclanthology.org/P19-1522.pdf


# 多模态

- ACL2020：Cross-media Structured Common Space for Multimedia Event Extraction

  - Authors：Manling Li, Alireza Zareian, Qi Zeng, Spencer Whitehead, Di Lu, Heng Ji, Shih-Fu Chang
  - url：https://aclanthology.org/2020.acl-main.230/
  


# 可解释性（Interpretability）

- ACL2020：Exploring Interpretability in Event Extraction: Multitask Learning of a Neural Event Classifier and an Explanation Decoder

  - Authors：Zheng Tang, Gus Hahn-Powell, Mihai Surdeanu
  - url：https://aclanthology.org/2020.acl-srw.23/


# ED:事件检测（event detection）
- ACL2022: **Saliency as Evidence: Event Detection with Trigger Saliency Attribution**

  - Authors: Jian Liu, Yufeng Chen, Jinan Xu
  - url: https://aclanthology.org/2022.acl-long.313/

- NAACL2022-findings: Event Detection for Suicide Understanding

  - Authors: Luis Fernando Guzman-Nateras, Viet Dac Lai, Amir Pouran Ben Veyseh, Franck Dernoncourt, Thien Huu Nguyen
  - url: https://openreview.net/pdf?id=SelBkQGB-q

- NAACL2022-findings: Zero-Shot Event Detection Based on Ordered Contrastive Learning and Prompt-Based

  - Authors: Senhui Zhang, Tao Ji, Wendi Ji, Xiaoling Wang
  - url: https://github.com/KindRoach/NAACL-ZEOP

- NAACL2022: Cross-Lingual Event Detection via Optimized Adversarial Training

  - Authors: Luis Fernando Guzman-Nateras, Minh Van Nguyen, Thien Huu Nguyen
  - url: https://openreview.net/forum?id=SlxGJEGHZq

- ACL2022: Low Resource Causal Event Detection from Biomedical Literature

  - Authors: Zhengzhong Liang, Enrique Noriega-Atala, Clayton Morrison, Mihai Surdeanu
  - url: https://aclanthology.org/2022.bionlp-1.24/
  
- ACL2021：OntoED: Low-resource Event Detection with Ontology Embedding

  - Author：Shumin Deng, Ningyu Zhang, Luoqiu Li, Chen Hui, Tou Huaixiao, Mosha Chen, Fei Huang, Huajun Chen
  - url: https://aclanthology.org/2021.acl-long.220/

- ACL2021: MLBiNet: A Cross-Sentence Collective Event Detection Network
 
  - Authors: Dongfang Lou, Zhilin Liao, Shumin Deng, Ningyu Zhang, Huajun Chen
  - url: https://aclanthology.org/2021.acl-long.373/

- ACL2021: Event Detection as Graph Parsing

  - Authors: Jianye Xie, Haotong Sun, Junsheng Zhou, Weiguang Qu, Xinyu Dai
  - url: https://aclanthology.org/2021.findings-acl.142/

- ACL2021: Few-Shot Event Detection with Prototypical Amortized Conditional Random Field
  
  - Author：Xin Cong, Shiyao Cui, Bowen Yu, Tingwen Liu, Wang Yubin, Bin Wang
  - url：https://aclanthology.org/2021.findings-acl.3/

- ACL2021：Trade the Event: Corporate Events Detection for News-Based Event-Driven Trading

  - Author：Zhihan Zhou, Liqian Ma, Han Liu
  - url：https://aclanthology.org/2021.findings-acl.186/

- ACL2021: Unsupervised Domain Adaptation for Event Detection using Domain-specific Adapters

  - Author: Nghia Ngo Trung, Duy Phung, Thien Huu Nguyen
  - url: https://aclanthology.org/2021.findings-acl.351/

- ACL2020: Improving Event Detection via Open-domain Trigger Knowledge

  - Author：Meihan Tong, Bin Xu, Shuai Wang, Yixin Cao, Lei Hou, Juanzi Li, Jun Xie
  - url：https://aclanthology.org/2020.acl-main.522/

- ACL2020：Towards Open Domain Event Trigger Identification using Adversarial Domain Adaptation

  - Author: Aakanksha Naik, Carolyn Rose
  - url: https://aclanthology.org/2020.acl-main.681/

- ACL2020：Extensively Matching for Few-shot Learning Event Detection

  - Author: Viet Dac Lai, Thien Huu Nguyen, Franck Dernoncourt
  - url: https://aclanthology.org/2020.nuse-1.5/

- EMNLP2020：Semi-supervised New Event Type Induction and Event Detection

  - Author: Lifu Huang, Heng Ji
  - url: https://aclanthology.org/2020.emnlp-main.53/
 
- EMNLP2020：Incremental Event Detection via Knowledge Consolidation Networks

  - Author: Pengfei Cao, Yubo Chen, Jun Zhao, Taifeng Wang
  - url: https://aclanthology.org/2020.emnlp-main.52/
 
- EMNLP2020：How Does Context Matter? On the Robustness of Event Detection with Context-Selective Mask Generalization

  - Author: Jian Liu, Yubo Chen, Kang Liu, Yantao Jia, Zhicheng Sheng
  - url: https://aclanthology.org/2020.findings-emnlp.229/

- EMNLP2020：Introducing a New Dataset for Event Detection in Cybersecurity Texts

  - Author: Hieu Man Duc Trong, Duc Trong Le, Amir Pouran Ben Veyseh, Thuat Nguyen, Thien Huu Nguyen
  - url: https://aclanthology.org/2020.emnlp-main.433/

- EMNLP2020：Event Detection: Gate Diversity and Syntactic Importance Scores for Graph Convolution Neural Networks

  - Author: Viet Dac Lai, Tuan Ngo Nguyen, Thien Huu Nguyen
  - url: https://aclanthology.org/2020.emnlp-main.435/


- EMNLP2020：Edge-Enhanced Graph Convolution Networks for Event Detection with Syntactic Relation

  - Author: Shiyao Cui, Bowen Yu, Tingwen Liu, Zhenyu Zhang, Xuebin Wang, Jinqiao Shi
  - url: https://aclanthology.org/2020.findings-emnlp.211/

- NAACL2021：GTN-ED: Event Detection Using Graph Transformer Networks

  - Authors：Sanghamitra Dutta, Liang Ma, Tanay Kumar Saha, Di Liu, Joel Tetreault, Alejandro Jaimes
  - url：https://aclanthology.org/2021.textgraphs-1.13/

- EMNLP2022：Few-Shot Cross-Lingual Learning for Event Detection

  - Author: Luis Guzman Nateras, Viet Lai, Franck Dernoncourt, Thien Nguyen
  - url: https://aclanthology.org/2022.mrl-1.2/

- EMNLP2022：Event-Based Knowledge MLM for Arabic Event Detection

  - Author: Asma Z Yamani, Amjad K Alsulami, Rabeah A Al-Zaidy
  - url: https://aclanthology.org/2022.wanlp-1.25/
 
- EMNLP2022：ArabIE: Joint Entity, Relation and Event Extraction for Arabic

  - Author: Niama El Khbir, Nadi Tomeh, Thierry Charnois
  - url: https://aclanthology.org/2022.wanlp-1.31/
 
- EMNLP2022：MUSIED: A Benchmark for Event Detection from Multi-Source Heterogeneous Informal Texts

  - Author: Xiangyu Xi, Jianwei Lv, Shuaipeng Liu, Wei Ye, Fan Yang, Guanglu Wan
  - url: https://aclanthology.org/2022.emnlp-main.191/

- EMNLP2022：HCL-TAT: A Hybrid Contrastive Learning Method for Few-shot Event Detection with Task-Adaptive Threshold

  - Author: Ruihan Zhang, Wei Wei, Xian-Ling Mao, Rui Fang, Dangyang Chen
  - url: https://aclanthology.org/2022.findings-emnlp.130/
 
- EMNLP2022：Knowledge-Enhanced Self-Supervised Prototypical Network for Few-Shot Event Detection

  - Author: Kailin Zhao, Xiaolong Jin, Long Bai, Jiafeng Guo, Xueqi Cheng
  - url: https://aclanthology.org/2022.findings-emnlp.467/

- EMNLP2022：A Hybrid Knowledge and Transformer-Based Model for Event Detection with Automatic Self-Attention Threshold, Layer and Head Selection

  - Author: Thierry Desot, Orphee De Clercq, Veronique Hoste
  - url: https://aclanthology.org/2022.case-1.4/
 

# Multi-Language:

- ACL2022: Multilingual Generative Language Models for Zero-Shot Cross-Lingual Event Argument Extraction

  - Authors: Kuan-Hao Huang, I-Hung Hsu, Prem Natarajan, Kai-Wei Chang, Nanyun Peng
  - url: https://aclanthology.org/2022.acl-long.317.pdf

- NAACL2022: Cross-Lingual Event Detection via Optimized Adversarial Training

  - Authors: Luis Fernando Guzman-Nateras, Minh Van Nguyen, Thien Huu Nguyen
  - url: https://openreview.net/forum?id=SlxGJEGHZq




# Special-domain

- ACL2022: BEEDS: Large-Scale Biomedical Event Extraction using Distant Supervision and Question Answering

  - 生物医学
  - Authors: Xing David Wang, Ulf Leser, Leon Weber
  - url: https://aclanthology.org/2022.bionlp-1.28/

- ACL2021：PROTEST-ER: Retraining BERT for Protest Event Extraction

  - Authors：Tommaso Caselli, Osman Mutlu, Angelo Basile, Ali Hürriyetoğlu
  - url：https://aclanthology.org/2021.case-1.4/

- ACL2022：Global Locality in Biomedical Relation and Event Extraction

  - Authors：Elaheh ShafieiBavani, Antonio Jimeno Yepes, Xu Zhong, David Martinez Iraola
  - url：https://aclanthology.org/2020.bionlp-1.21/

- EMNLP2020：Biomedical Event Extraction as Sequence Labeling

  - Authors：Alan Ramponi, Rob van der Goot, Rosario Lombardo, Barbara Plank
  - url：https://aclanthology.org/2020.emnlp-main.431/

- EMNLP2020：Biomedical Event Extraction with Hierarchical Knowledge Graphs

  - Authors: Kung-Hsiang Huang, Mu Yang, Nanyun Peng
  - https://aclanthology.org/2020.findings-emnlp.114/


# 综述类文章

- ACL2021：Event-Centric Natural Language Processing

- NAACL2022：New Frontiers of Information Extraction

  - Authors：Muhao Chen, Lifu Huang, Manling Li, Ben Zhou, Heng Ji, Dan Roth
  - https://aclanthology.org/2022.naacl-tutorials.3/
