# KMRC-Papers

A list of recent papers regarding knowledge-based machine reading comprehension.

Contributed by Luxi Xing and Yuqiang Xie, National Engineering Laboratory for Information Security Technologies, Institute of Information Engineering, Chinese Academy of Sciences, Beijing, China. 

-------
There have been many works on incorporate knowledge into process natural language. Many NLP downstream tasks are designed to test whether integrating external knowledge into semantic computing could improve machine's ability of semantic understanding. Besides, what knowledge is needed for the specific task? There is a long way to go.

## NLP Downstream Tasks

### NLI with Knowledge

| Conf.   | Title | Authors/Org. | Note |
| :-----: | :---  | :----------- | :---:|
| ACL<br>2018 | [Neural Natural Language Inference Models Enhanced with External Knowledge](http://www.aclweb.org/anthology/P18-1224) | Chen, et al.<br>UCTS | [link](https://github.com/XingLuxi/KMRC-Papers/blob/master/note/kim.md) |


### MRC with Knowledge

| Conf.   | Title | Authors/Org. | Note |
| :-----: | :--- | :----------- | :---:|
| ACL<br>2017   | [Leveraging knowledge bases in lstms for improving machine reading](https://doi.org/10.18653/v1/P17-1132)   | Yang, et al.<br>CMU | |
| ACL<br>2017   | [World knowledge for reading comprehension: Rare entity prediction with hierarchical lstms using external descriptions](http://www.aclweb.org/anthology/D17-1086)  | Long, et al.<br>McGill University| |
| EMNLP<br>2017   | [Reasoning with Heterogeneous Knowledge for Commonsense Machine Comprehension](https://www.aclweb.org/anthology/D17-1216)   | Lin, et al.<br>IS,CAS | |
| ACL<br>2018   | [Knowledgeable Reader: Enhancing Cloze-Style Reading Comprehension with External Commonsense Knowledge](http://aclweb.org/anthology/P18-1076)  | Mihaylov, et al.<br>Heidelberg University   | [link](https://github.com/XingLuxi/KMRC-Papers/blob/master/note/knreader.md) |
| AAAI<br>2019 | [Story Ending Generation with Incremental Encoding and Commonsense Knowledge](https://arxiv.org/abs/1808.10113) | Jian Guan, et al.<br>THU |  |
| AAAI<br>2019 | [Knowledge Based Machine Reading Comprehension](https://arxiv.org/pdf/1809.04267.pdf) | Yibo Sun, et al.<br>MSRA |  |
| ACL<br>2019 | [Careful Selection of Knowledge to solve Open Book Question Answering](http://www.public.asu.edu/~cbaral/papers/2019acl-obqa.pdf) | Banerjee, et al.<br>ASU |  |
| ACL<br>2019 | [Explicit Utilization of General Knowledge in Machine Reading Comprehension](https://arxiv.org/abs/1809.03449?context=cs.CL) | Wang, et al.<br>[YUC](http://www.yorku.ca/index.html) |  |

More details refers to this [link](https://github.com/XingLuxi/KMRC-Papers/blob/master/kmrc-area.md) which focuses on KMRC.

### QA with Knowledge

| Conf.   | Title | Authors/Org. | Note |
| :-----: | :---  | :----------- | :---:|
| NAACL<br>2019 |  [UHop-An Unrestricted-Hop Relation Extraction Framework for Knowledge-Based Question Answering](https://www.aclweb.org/anthology/N19-1031) | Chen, et al. |  |
| NAACL<br>2019 |  [Enhancing Key-Value Memory Neural Networks for Knowledge Based Question Answering](https://www.aclweb.org/anthology/N19-1301) | Xu, et al.<br>Tencent AI Lab |  |
| ACL<br>2019 |  [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://arxiv.org/pdf/1905.07098.pdf) | Xiong, et al.<br>UCSB&IBM |  |

### Dialog with Knowledge

| Conf.   | Title | Authors/Org. | Note |
| :-----: | :--- | :----------- | :---:|
| ACL<br>2017   | [Learning Symmetric Collaborative Dialogue Agents with Dynamic Knowledge Graph Embeddings](http://aclweb.org/anthology/P17-1162) | He, et al.<br>Stanford |  |
| IJCAI<br>2018 | [Commonsense Knowledge Aware Conversation Generation with Graph Attention](https://www.ijcai.org/proceedings/2018/0643.pdf) | Zhou, et al.<br>THU |  |
| AAAI<br>2018  | [A Knowledge-Grounded Neural Conversation Model](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/02/A_Knowledge_Grounded_Neural_Conversation_Model.pdf) | Ghazvininejad, et al.<br>Microsoft Research |  |
| AAAI<br>2018   | [Flexible End-to-End Dialogue System for Knowledge Grounded Conversation](https://arxiv.org/pdf/1709.04264.pdf) | Zhu, et al.<br>HKUST | |
| Arxiv<br>2019 | [Learning to Select Knowledge for Response Generation in Dialog Systems](https://arxiv.org/pdf/1902.04911.pdf) | Lian, et al.<br>Baidu | |
| NAACL<br>2019 | [Disentangling Language and Knowledge in Task-Oriented Dialogs](https://www.aclweb.org/anthology/N19-1126) | Raghu, et al.<br>IBM Research | |


### Representation with Knowledge 

| Conf.   | Title | Authors/Org. | Note |
| :-----: | :--- | :----------- | :---:|
| ICLR<br>2017  | [A Neural Knowledge Language Model](https://arxiv.org/pdf/1608.00318v1.pdf)   | Ahn, et al.<br>Université de Montréal | |
| ACL<br>2017   | [Improved Word Representation Learning with Sememes](http://aclweb.org/anthology/P17-1187)    | Niu, et al.<br>THU | |
| ACL<br>2018   | [Cross-lingual Lexical Sememe Prediction](http://aclweb.org/anthology/D18-1033)    | Qi, et al.<br>THU| |
| AAAI<br>2018  | [Improving Neural Fine-Grained Entity Typing with Knowledge Attention](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16321/16167) | Xin, et al.<br>THU | |
| ACL<br>2019  | [ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/abs/1905.07129) | Zhang, et al.<br>THU | |
| ACL<br>2019  | [ERNIE: Enhanced Representation through Knowledge Integration](https://arxiv.org/abs/1904.09223) | Sun, et al.<br>Baidu | |

## Taxonomy

### Level:
1. KMRC area.
2. Relevant research area.
3. Heuristic.
4. Review.

### Field:
- **KMRC:** **K**nowledge-based **M**achine **R**eading **C**omprehension;
- **KDS:** **K**nowledge-based **D**ialogue **S**ystem;
- **KIR:** **K**nowledge-based **I**nformation **R**etrieval;
- **SC:** **S**ememe **C**omputation;
- **NKLM:** **N**eural **K**nowledge **L**anguage **M**odel.

## License
MIT License
