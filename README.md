# Papers-reader
Write down the papers I have read.

A list of recent papers about **Knowledge-enhanced language model** (**KeLM**).
Update on **July. 12, 2020**.
(We will continuously update this list.)

-------
## [Content](#content)
1. [Survey](#survey-papers)
2. [Related papers](#related-papers)

## [Related papers](#content)
1.**Enriching Pre-trained Language Model with Entity Information for Relation Classification** *CIKM2019*. [[paper](https://arxiv.org/abs/1905.08284) / [note](https://blog.csdn.net/qq_36426650/article/details/96629835)]
>Wu S, He Y. Enriching pre-trained language model with entity information for relation classification[C]//Proceedings of the 28th ACM International Conference on Information and Knowledge Management. 2019: 2361-2364.
**要点**
- 为了能够定位两个目标实体，并将其信息转移到BERT中，在将整个问题喂入BERT前，在目标实体前后添加token，亦即符号“$”和“#”;
- 使用每个字符输入的相加平均值表示实体向量.
<img src="./images/Snipaste_2020-07-12_15-35-43.png" width="600"  alt="model structure"/><br/>
