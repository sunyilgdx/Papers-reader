# Papers-reader
Write down the papers I have read.

A list of recent papers about **Knowledge-enhanced language model**(K-papers) and **Domain adaptation**(D-papers).
Update on **July. 12, 2020**.
(We will continuously update this list.)

-------
## [Content](#content)
1. [K-Papers](#k-papers)
2. [D-Papers](#d-papers)
3. [Related papers](#related-papers)
4. [Others](#others)


## [K-Papers](#content)
1. **Knowledgeable Reader: Enhancing Cloze-Style Reading Comprehension with External Commonsense Knowledge**

    Authors: *Todor Mihaylov, Anette Frank*
    
    Department: *Research Training Group AIPHES Department of Computational Linguistics, Heidelberg University Heidelberg, Germany*
<img src="./images/Snipaste_2020-07-12_17-12-19.png" width="600"  alt="model structure"/><br/>
2. ****

## [D-Papers](#content) 
1. **Instance Weighting for Domain Adaptation via Trading off Sample Selection Bias and Variance** *IJCAI 2018*  [[paper](https://www.ijcai.org/Proceedings/2018/0624.pdf)]

2. **Task Refinement Learning for Improved Accuracy and Stability of Unsupervised Domain Adaptation** *ACL 2019*  [[paper](https://www.aclweb.org/anthology/P19-1591.pdf)]

3. **Unsupervised Domain Adaptation for Clinical Negation Detection** *BioNLP 2017* [[paper](https://www.aclweb.org/anthology/W17-2320.pdf)]

4. **Domain Adaptive Training BERT for Response Selection** *arxiv 2019* [[paper](https://arxiv.org/abs/1908.04812)]

5. **Learning to select data for transfer learning with Bayesian Optimization** *EMNLP 2017* [[paper](https://arxiv.org/abs/1707.05246) / [note](https://ruder.io/learning-select-data/index.html)]

    Authors: *Sebastian Ruder, Barbara Plank* 

6.  **Neural Transfer Learning for Natural Language Processing (PhD thesis)** *PhD 2019* [[paper](https://ruder.io/thesis/neural_transfer_learning_for_nlp.pdf) / [note](https://ruder.io/thesis/index.html)]


## [Related papers](#content)
1. **Enriching Pre-trained Language Model with Entity Information for Relation Classification** *CIKM2019*. [[paper](https://arxiv.org/abs/1905.08284) / [note](https://blog.csdn.net/qq_36426650/article/details/96629835)]
    Authors: *Shanchan Wu, Yifan He*

2. **Multiway Attention Networks for Modeling Sentence Pairs** *IJCAI 2018*  [[paper](https://pdfs.semanticscholar.org/2b32/b4fa1e28c256745f1573b5444b1b2c8df30e.pdf)]

**要点**
- 使用多种注意力机制
<img src="./images/Snipaste_2020-07-12_17-11-36.png" width="600"  alt="model structure"/><br/>


**要点**
- 为了能够定位两个目标实体，并将其信息转移到BERT中，在将整个问题喂入BERT前，在目标实体前后添加token，亦即符号“$”和“#”;
- 使用每个字符输入的相加平均值表示实体向量.

<img src="./images/Snipaste_2020-07-12_15-35-43.png" width="600"  alt="model structure"/><br/>

## [Others](#content)
1. [BERT相关论文列表](https://www.ctolib.com/tomohideshibata-BERT-related-papers.html)
2. [Must-read papers on KRL/KE](https://github.com/thunlp/KRLPapers)
3. [预训练词向量/句向量模型的精选列表](https://www.ctolib.com/Separius-awesome-sentence-embedding.html)
