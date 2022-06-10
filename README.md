# EE
ee paper 
based on https://github.com/carrie0307/DL_EventExtractionPapers.

在自己读文章的时候，感觉分类更重要了，按自己的想法，简单对22年6月以来读的文章进行分类。

Event Extraction (EE) 是 Information Extraction (IE) 的一个分支，包含两个子任务：
  - Event Detection (ED): recognize event triggers
  - Event Argument Extraction (EAE): identify/recognize/extract/fill role

# DATASET
- [MAVEN: A Massive General Domain Event Detection Dataset](https://aclanthology.org/2020.emnlp-main.129/)
- [LEVEN: A Large-Scale Chinese Legal Event Detection Dataset](https://aclanthology.org/2022.findings-acl.17/)
- [Roles Across Multiple Sentences (RAMS)](https://nlp.jhu.edu/rams/)
- DuEE: A Large-Scale Dataset for Chinese Event Extraction in Real-World Scenarios



# EAE:隐式事件抽取（event argument extraction）
### GAN-生成式
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


### Multi-Role

- ACL2022-findings: Query and Extract: Refining Event Extraction as Type-oriented Binary Decoding

  - Authors: Sijia Wang, Mo Yu, Shiyu Chang, Lichao Sun, Lifu Huang
  - url: https://arxiv.org/abs/2110.07476

- ACL2022: Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction

  - Authors: Yubo Ma, Zehao Wang, Yixin Cao, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao
  - url: https://aclanthology.org/2022.acl-long.466


### 图神经-GCN

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

# DA：数据增强（Data Augmentation）

- ACL2022: ClarET: Pre-training a Correlation-Aware Context-To-Event Transformer for Event-Centric Generation and Classification

  - Authors: Yucheng Zhou, Tao Shen, Xiubo Geng, Guodong Long, Daxin Jiang
  - url: https://aclanthology.org/2022.acl-long.183/




# ED:事件检测（event detection）
- ACL2022: **Saliency as Evidence: Event Detection with Trigger Saliency Attribution**

  - Authors: Jian Liu, Yufeng Chen, Jinan Xu
  - url: https://aclanthology.org/2022.acl-long.313/

- NAACL2022-findings: Event Detection for Suicide Understanding

  Authors: Luis Fernando Guzman-Nateras, Viet Dac Lai, Amir Pouran Ben Veyseh, Franck Dernoncourt, Thien Huu Nguyen
  - url: https://openreview.net/pdf?id=SelBkQGB-q

- NAACL2022-findings: Zero-Shot Event Detection Based on Ordered Contrastive Learning and Prompt-Based

  - Authors: Senhui Zhang, Tao Ji, Wendi Ji, Xiaoling Wang
  - url: https://github.com/KindRoach/NAACL-ZEOP
