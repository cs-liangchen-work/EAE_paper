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





### QA/MRC

- **EMNLP2020: Event Extraction by Answering (Almost) Natural Questions**

  - Authors: Xinya Du and Claire Cardie
  - url: https://arxiv.org/abs/2004.13625

- EMNLP2020: Event Extraction as Machine Reading Comprehension

  - Authors: Jian Liu, Yubo Chen, Kang Liu, Wei Bi and Xiaojiang Liu
  - url: https://www.aclweb.org/anthology/2020.emnlp-main.128/

- EMNLP2021: Machine Reading Comprehension as Data Augmentation: A Case Study on Implicit Event Argument Extraction

  - Authors: Jian Liu, Yufeng Chen, Jinan Xu
  - url: https://aclanthology.org/2021.emnlp-main.214.pdf



### 图神经-GCN

- ACL2021: Document-Level Event Argument Extraction via Optimal Transport

  - Authors: Amir Pouran Ben Veyseh, Minh Van Nguyen, Franck Dernoncourt, Bonan Min and Thien Huu Nguyen
  - url: https://aclanthology.org/2022.findings-acl.130/




# ED:事件检测（event detection）
- ACL2022: **Saliency as Evidence: Event Detection with Trigger Saliency Attribution**

  - Authors: Jian Liu, Yufeng Chen, Jinan Xu
  - url: https://aclanthology.org/2022.acl-long.313/
