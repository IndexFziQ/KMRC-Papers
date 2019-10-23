# Papers on Knowledge-based Machine Reading Comprehension.

A list of recent papers about **Knowledge-based Machine Reading Comprehension** (**KMRC**).

Contributed by [Luxi Xing](https://github.com/XingLuxi) and [Yuqiang Xie](https://github.com/IndexFziQ).

Institute of Information Engineering, Chinese Academy of Sciences, Beijing, China. 

Update on **Oct. 23, 2019**.

(the current version only contains the works published on the conferences or journals, we will continuously update this list.)

-------

## [Content](#content)

1. [Survey](#survey-papers)
2. [Cloze Style Tasks](#cloze-style-tasks)
3. [Span Extraction Tasks](#span-extraction-tasks)
4. [Multiple Choice Tasks](#multiple-choice-tasks)
5. [Generation Tasks](#generation-tasks)
6. [Datasets](#benchmark-datasets)

Note: papers about KBQA will be not included in this list.

## [Survey Papers](#content)

1. **Commonsense Reasoning for Natural Language Understanding: A Survey of Benchmarks, Resources, and Approaches**. 2019. [[paper](https://arxiv.org/abs/1904.01172) / [note](https://zhuanlan.zhihu.com/p/80883568)]
    
    Authors: *Shane Storks, Qianzi Gao, Joyce Y. Chai*
    
1. **Neural Machine Reading Comprehension: Methods and Trends**. 2019. [[paper](https://arxiv.org/abs/1907.01118)]
    
    Authors: *Shanshan Liu, Xin Zhang, Sheng Zhang, Hui Wang, Weiming Zhang*
    
1. **Machine Reading Comprehension: a Literature Review**. 2019. [[paper](https://arxiv.org/abs/1907.01686)]
    
    Authors: *Xin Zhang, An Yang, Sujian Li, Yizhong Wang*
    

## [Cloze Style Tasks](#content)

1. **World Knowledge for Reading Comprehension: Rare Entity Prediction with Hierarchical LSTMs Using External Descriptions**. EMNLP,2017.
    
    Authors: *Teng Long, Emmanuel Bengio, Ryan Lowe Jackie Chi Kit Cheung, Doina Precup*
    
    Links: [paper](https://www.aclweb.org/anthology/D17-1086)
    
    Tasks: Rare Entity Prediction;
    
1. **Reasoning with Heterogeneous Knowledge for Commonsense Machine Comprehension**. ACL,2017.
    
    Authors: *Hongyu Lin, Le Sun, Xianpei Han*
    
    Links: [paper](http://aclweb.org/anthology/D17-1216)
    
    Tasks: SCT;

1. **Knowledgeable Reader: Enhancing Cloze-Style Reading Comprehension with External Commonsense Knowledge**. ACL,2018. 
    
    Authors: *Todor Mihaylov, Anette Frank*
    
    Links: [paper](http://aclweb.org/anthology/P18-1076) / code / [note](http://xingluxi.github.io/2019/01/09/paper-knreader/)
    
    Tasks: Common Nouns;
    
1. **A Multi-Attention based Neural Network with External Knowledge for Story Ending Predicting Task**. COLING,2018.
    
    Authors: *Qian Li, Ziwei Li, Jin-Mao Wei, Yanhui Gu, Adam Jatowt, Zhenglu Yang*
    
    Links: [paper](http://www.aclweb.org/anthology/C18-1149)
    
    Tasks: SCT;
    
1. **Incorporating Structured Commonsense Knowledge in Story Completion**. AAAI,2018.
    
    Authors: *Jiaao Chen, Jianshu Chen, Zhou Yu*
    
    Links: [paper](https://arxiv.org/abs/1811.00625)
    
    Tasks: SCT;

2. **Story Ending Prediction by Transferable BERT**. IJCAI,2019.
    
    Authors: *Zhongyang Li, Xiao Ding, Ting Liu*
    
    Links: [paper](https://arxiv.org/abs/1905.07504)
    
    Tasks: SCT;


## [Span Extraction Tasks](#content)

1. **Dynamic Integration of Background Knowledge in Neural NLU Systems**. arxiv,2018.
    
    Authors: *Dirk Weissenborn, Tomas Kocisky, Chris Dyer*
    
    Links: [paper](https://arxiv.org/pdf/1706.02596.pdf)
    
    Tasks: SQuAD; TriviaQA;

1. **Explicit Utilization of General Knowledge in Machine Reading Comprehension**. ACL,2019.
    
    Authors: *Chao Wang, Hui Jiang*
    
    Links: [paper](https://www.aclweb.org/anthology/P19-1219) / [note](http://xingluxi.github.io/2019/07/17/paper-acl2019-kar/)
    
    Tasks: SQuAD;

1. **Enhancing Pre-Trained Language Representations with Rich Knowledge for Machine Reading Comprehension**. ACL,2019.
    
    Authors: *An Yang, Quan Wang, Jing Liu, Kai Liu, Yajuan Lyu, Hua Wu, Qiaoqiao She, Sujian Li*
    
    Links: [paper](https://www.aclweb.org/anthology/P19-1226/) / [note](http://xingluxi.github.io/2019/07/29/paper-acl2019-kt-net/)
    
    Tasks: SQuAD; ReCoRD;

## [Multiple Choice Tasks](#content)

1. **Yuanfudao at SemEval-2018 Task 11: Three-way Attention and Relational Knowledge for Commonsense Machine Comprehension**. SemEval,2018.
    
    Author: *Liang Wang, Meng Sun, Wei Zhao, Kewei Shen, Jingming Liu*
    
    Links: [paper](https://www.aclweb.org/anthology/S18-1120/) / [code](https://github.com/intfloat/commonsense-rc)
    
    Tasks: SemEval-2018 Task 11;

2. **Improving Question Answering by Commonsense-Based Pre-Training**. AAAI,2019.
    
    Authors: *Wanjun Zhong, Duyu Tang, Nan Duan, Ming Zhou, Jiahai Wang, Jian Yin*
    
    Links: [paper](https://arxiv.org/abs/1809.03568)
    
    Tasks: ARC; OpenBookQA;  SemEval-2018 Task 11;
    
1. **Improving Machine Reading Comprehension with General Reading Strategies**. NAACL,2019.
    
    Authors: *Kai Sun, Dian Yu, Dong Yu, Claire Cardie*
    
    Links: [paper](https://www.aclweb.org/anthology/N19-1270/) / [code](https://github.com/nlpdata/strategy/)
    
    Tasks: ARC; OpenBookQA; MCTest; SemEval-2018 Task 11; SCT; MultiRC;
    
1. **Ranking and Selecting Multi-Hop Knowledge Paths to Better Predict Human Needs**. NAACL,2019.
    
    Authors: *Debjit Paul, Anette Frank*
    
    Links: [paper](https://www.aclweb.org/anthology/papers/N/N19/N19-1368/) / [code](https://github.com/debjitpaul/Multi-Hop-Knowledge-Paths-Human-Needs)
    
    Tasks: story commonsense;
    
1. **Incorporating Relation Knowledge into Commonsense Reading Comprehension with Multi-task Learning**. CIKM,2019.
    
    Author: *Jiangnan Xia, Chen Wu, Ming Yan*
    
    Links: [paper](https://arxiv.org/abs/1908.04530)
    
    Tasks: SemEval-2018 Task 11 / SCT;
    
1. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning**. ACL,2019.
    
    Authors: *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher*
    
    Links: [paper](https://www.aclweb.org/anthology/P19-1487.pdf) / [code](https://github.com/salesforce/cos-e) / [note](http://xingluxi.github.io/2019/07/10/paper-acl2019-cos-e/)
    
    Tasks: CommonsenseQA;
    
1. **Careful Selection of Knowledge to solve Open Book Question Answering**. ACL,2019.
    
    Authors: *Pratyay Banerjee, Kuntal Kumar Pal, Arindam Mitra, Chitta Baral*
    
    Links: [paper](https://arxiv.org/abs/1907.10738)
    
    Tasks: OpenBookQA;
    
1. **Improving Question Answering with External Knowledge**. EMNLP-MRQA,2019.
    
    Authors: *Xiaoman Pan, Kai Sun, Dian Yu, Jianshu Chen, Heng Ji, Claire Cardie, Dong Yu*
    
    Links: [paper](https://arxiv.org/pdf/1902.00993.pdf) / [note](http://xingluxi.github.io/2019/08/26/paper-2019-edl-md/)
    
    Tasks: ARC; OpenBookQA;
    
1. **KagNet: Knowledge-Aware Graph Networks for Commonsense Reasoning**. EMNLP,2019.
    
    Authors: *Bill Yuchen Lin, Xinyue Chen, Jamin Chen, Xiang Ren*
    
    Links: [paper](https://arxiv.org/abs/1909.02151) / [code](https://github.com/INK-USC/KagNet) / [note](https://zhuanlan.zhihu.com/p/81917730)
    
    Tasks: CommonsenseQA;
    
1. **What’s Missing: A Knowledge Gap Guided Approach for Multi-hop Question Answering**. EMNLP,2019.
    
    Authors: *Tushar Khot, Ashish Sabharwal, Peter Clark*
    
    Links: [paper](https://arxiv.org/abs/1909.09253)/ [note](https://zhuanlan.zhihu.com/p/85852386)
    
    Tasks: OpenBookQA;
    
1. **BIG MOOD: Relating Transformers to Explicit Commonsense Knowledge**. EMNLP-COIN,2019.
    
    Authors: *Jeff Da*
    
    Links: [paper](http://arxiv.org/abs/1910.07713)
    
    Tasks: MCScripts-v2;

## [Generation Tasks](#content)
Also known as **Free-form Answer Tasks**

1. **Commonsense for Generative Multi-Hop Question Answering Tasks**. EMNLP,2018.
    
    Authors: *Lisa Bauer, Yicheng Wang, Mohit Bansal*
    
    Links: [paper](https://www.aclweb.org/anthology/D18-1454/) / [code](https://github.com/yicheng-w/CommonSenseMultiHopQA) / [note](http://xingluxi.github.io/2019/02/21/paper-emnlp2018-mhpgm/)
    
    Tasks: NarrativeQA; QAngaroo-WikiHop;
    
1. **COMET: Commonsense Transformers for Automatic Knowledge Graph Construction**. ACL,2019.
    
    Authors: *Antoine Bosselut, Hannah Rashkin, Maarten Sap, Chaitanya Malaviya, Asli Celikyilmaz, Yejin Choi*
    
    Links: [paper](https://arxiv.org/abs/1906.05317) / [code](https://github.com/atcbosselut/comet-commonsense) / [note](https://indexfziq.github.io/2019/07/03/COMET/)
    
    Tasks: Atomic;
    
1. **Incorporating External Knowledge into Machine Reading for Generative Question Answering**. EMNLP,2019.
    
    Authors: *Bin Bi, Chen Wu, Ming Yan, Wei Wang, Jiangnan Xia, Chenliang Li*
    
    Links: [paper](http://arxiv.org/abs/1909.02745) / [note](http://xingluxi.github.io/2019/10/13/paper-emnlp2019-keag/)
    
    Tasks: MS MARCO;


## [Benchmark Datasets](#content)

1. [**COPA**] Choice of Plausible Alternatives: An Evaluation of Commonsense Causal Reasoning. AAAI,2011. [[paper](http://ict.usc.edu/~gordon/publications/AAAI-SPRING11A.PDF) / [data](http://people.ict.usc.edu/~gordon/copa.html)]
    
    Authors: *Melissa Roemmele, Cosmin Adrian Bejan, Andrew S. Gordon*
    
    * Type: Multiple-Choice;
    
1. [**WSC**] The Winograd Schema Challenge. AAAI,2011. [[paper](https://www.aaai.org/ocs/index.php/KR/KR12/paper/download/4492/4924) /[data](https://cs.nyu.edu/faculty/davise/papers/WinogradSchemas/WS.html)]
    
    Authors: *Hector J. Levesque, Ernest Davis, Leora Morgenstern*
    * Type: Multiple-Choice;

2. [**ROCStories**; **SCT**] A Corpus and Cloze Evaluation for Deeper Understanding of Commonsense Stories. NAACL,2016. [[paper](https://www.aclweb.org/anthology/N16-1098/) / [data](https://www.cs.rochester.edu/nlp/rocstories/)]
    
    Authors: *Nasrin Mostafazadeh, Nathanael Chambers, Xiaodong He, Devi Parikh, Dhruv Batra, Lucy Vanderwende, Pushmeet Kohli, James Allen*

    Type: Cloze;
    
1. [**NarrativeQA**] The NarrativeQA Reading Comprehension Challenge. TACL,2018. [[paper](https://arxiv.org/abs/1712.07040) / [data](https://github.com/deepmind/narrativeqa)]
    
    Authors: *Tomáš Kočiský, Jonathan Schwarz, Phil Blunsom, Chris Dyer, Karl Moritz Hermann, Gábor Melis, Edward Grefenstette*
    
    Type: Generation;
    
1. [**SemEval-2018 Task 11**] MCScript: A Novel Dataset for Assessing Machine Comprehension Using Script Knowledge. LERC,2018. [[paper](https://arxiv.org/abs/1803.05223) / [data](http://www.sfb1102.uni-saarland.de/?page_id=2582)]
    
    Authors: *Simon Ostermann, Ashutosh Modi, Michael Roth, Stefan Thater, Manfred Pinkal*
    
    Type: Multiple-Choice;
    
1. [**story-commonsense**] Modeling Naive Psychology of Characters in Simple Commonsense Stories. ACL,2018. [[paper](https://www.aclweb.org/anthology/P18-1213/) / [data](http://uwnlp.github.io/storycommonsense)]
    
    Authors: *Hannah Rashkin, Antoine Bosselut, Maarten Sap, Kevin Knight, Yejin Choi*
    
    Type: Multiple-Choice;
    
1. **Event2Mind**: Commonsense Inference on Events, Intents, and Reactions. ACL,2018. [[paper](https://www.aclweb.org/anthology/P18-1043/) / [data](https://uwnlp.github.io/event2mind/)]
    
    Authors: *Hannah Rashkin, Maarten Sap, Emily Allaway, Noah A. Smith, Yejin Choi*
    
    Types: Generation;

1. **ATOMIC**: An Atlas of Machine Commonsense for If-Then Reasoning. AAAI,2019. [[paper](https://homes.cs.washington.edu/~msap/atomic/data/sap2019atomic.pdf) / [data](https://homes.cs.washington.edu/~msap/atomic/)]
    
    Authors: *Maarten Sap, Ronan LeBras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi*
    
    Types: Generation;

1. [**ARC**] Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge. 2018. [[paper](http://ai2-website.s3.amazonaws.com/publications/AI2ReasoningChallenge2018.pdf) / [data](http://data.allenai.org/arc/)]
    
    Authors: *Peter Clark, Isaac Cowhey, Oren Etzioni, Tushar Khot, Ashish Sabharwal, Carissa Schoenick, Oyvind Tafjord*
  
    Type: Multiple-Choice;
    
1. [**OpenBookQA**] Can a Suit of Armor Conduct Electricity? A New Dataset for Open Book Question Answering. EMNLP,2018. [[paper](https://www.aclweb.org/anthology/D18-1260/) / [data](https://leaderboard.allenai.org/open_book_qa)]
    
    Authors: *Todor Mihaylov, Peter Clark, Tushar Khot, Ashish Sabharwal*

    Type: Multiple-Choice;
    
1. **ReCoRD**: Bridging the Gap between Human and Machine Commonsense Reading Comprehension. 2018. [[paper](https://arxiv.org/abs/1810.12885) / [data](https://sheng-z.github.io/ReCoRD-explorer/)]
    
    Authors: *Sheng Zhang, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Kevin Duh, Benjamin Van Durme*
    
    Type: Cloze;
    
1. **CommonsenseQA**: A Question Answering Challenge Targeting Commonsense Knowledge. NAACL,2019. [[paper](https://www.aclweb.org/anthology/N19-1421/) / [data](https://www.tau-nlp.org/commonsenseqa)]
    
    Authors: *Alon Talmor, Jonathan Herzig, Nicholas Lourie, Jonathan Berant*
    
    Type: Multiple-Choice;
    
1. **ChID**: A Large-scale Chinese IDiom Dataset for Cloze Test. ACL,2019. [[paper](https://www.aclweb.org/anthology/P19-1075) / [data](https://github.com/chujiezheng/ChID-Dataset)]
    
    Authors: *Chujie Zheng, Minlie Huang, Aixin Sun*

    Type: Cloze;
    
1. [**sense-making**] Does it Make Sense? And Why? A Pilot Study for Sense Making and Explanation. ACL,2019. [[paper](https://www.aclweb.org/anthology/P19-1393/) / [data]( https://github.com/wangcunxiang/SenMaking-and-Explanation)]
    
    Authors: *Cunxiang Wang, Shuailong Liang, Yue Zhang, Xiaonan Li, Tian Gao*
    
    Type: Multiple-Choice;
    
1. **HellaSwag**: Can a Machine Really Finish Your Sentence? ACL,2019. [[paper](https://arxiv.org/abs/1905.07830) / [data](https://rowanzellers.com/hellaswag/)]
    
    Authors: *Rowan Zellers, Ari Holtzman, Yonatan Bisk, Ali Farhadi, Yejin Choi*

    Type: Multiple-Choice;
    
1. **SocialIQA**: Commonsense Reasoning about Social Interactions. EMNLP,2019. [[paper](https://arxiv.org/abs/1904.09728) / [data](https://maartensap.github.io/social-iqa/)]
    
    Authors: *Maarten Sap, Hannah Rashkin, Derek Chen, Ronan LeBras, Yejin Choi*

    Type: Multiple-Choice;

1. [**ANLI**] Abductive Commonsense Reasoning. 2019. [[paper](https://arxiv.org/abs/1908.05739) / [data](https://leaderboard.allenai.org/anli/submissions/get-started)]
    
    Authors: *Chandra Bhagavatula, Ronan Le Bras, Chaitanya Malaviya, Keisuke Sakaguchi, Ari Holtzman, Hannah Rashkin, Doug Downey, Scott Wen-tau Yih, Yejin Choi*

    Type: Multiple-Choice;

1. **Cosmos QA**: Machine Reading Comprehension with Contextual Commonsense Reasoning. EMNLP,2019. [[paper](https://arxiv.org/abs/1909.00277) / [data](https://wilburone.github.io/cosmos/)]
    
    Authors: *Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi*

    Type: Multiple-Choice;

Note: *Only consider the benchmark datasets/tasks which require knowledge to complete.*


## Other Paper List About MRC

[thunlp/RCPapers](https://github.com/thunlp/RCPapers)