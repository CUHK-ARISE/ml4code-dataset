# A Collection of Datasets for Big Code Analysis

A collection of datasets (and other resources) for [big code analysis](https://ml4code.github.io/papers.html).

If you want to contribute to this list, please send a pull request.

## Datasets

| Name          | Description                                                  | Tag                                  | Language          | Link                                                         |
| ------------- | ------------------------------------------------------------ | ------------------------------------ | ----------------- | ------------------------------------------------------------ |
| CodeSearchNet | Dataset and benchmarks for code retrieval using natural language | Code Retrieval, NLP                  | Multiple (Python) | [link](https://github.com/github/CodeSearchNet)              |
| PY150         | 150k Python programs and corresponding abstract syntax trees, released by OOPSLA'16 _Probabilistic Model for Code with Decision Trees_                                | General                              | Python            | [link](https://www.sri.inf.ethz.ch/py150)                    |
| OJ-104            | Code from a Online Judge System, consisting of 104 classes of C programs, released by AAAI'16 _Convolutional Neural Networks over Tree Structures for Programming Language Processing._ | Code Classification, Clone Dectetion | C                 | [link](https://sites.google.com/site/treebasedcnn/), also used in [ASTNN](https://github.com/zhangj111/astnn)                   |
| code2seq      | Datset released by the ICLR paper _code2vec_, _code2seq_, etc.   | Code Completion                      | Java, C#          | [link](https://github.com/tech-srl/code2seq#datasets)        |
| BigCloneBench | BigCloneBench is a clone detection benchmark of known clones in the dataset source repository. | Clone Dectetion                      | Java              | [link](https://github.com/clonebench/BigCloneBench)          |
| Google Code Jam | Projects collected from Google Code Jam competition. | Clone Dectetion                      | Java              | [link](https://github.com/parasol-aser/deepsim/tree/master/dataset)          |
| CodeChef      | Program classification dataset released by kaggle        | Code Classification                  | Java              | [link](https://www.kaggle.com/arjoonn/codechef-competitive-programming) |
| OOPSLA19Li    | Datset released by the OOPSLA'19 _Improving Bug Detection via Context-based Code Representation Learning and Attention-based Neural Networks_ | Bug Detection                        | Java              | [link](https://github.com/OOPSLA-2019-BugDetection/OOPSLA-2019-BugDetection) |
| Devign        | Dataset released by NeurIPS'19 *Devign: Effective Vulnerability Identification by Learning Comprehensive Program Semantics via Graph Neural Networks* | Vulnerability Identification         | C              | [link](https://sites.google.com/view/devign)                 |
| Draper        | The dataset consists of the source code of 1.27 million functions mined from open source software, labelled by static analysis for potential vulnerabilities. The dataset is released by ICMLA'18 _Automated Vulnerability Detection in Source Code Using Deep Representation Learning_  | Vulnerability Identification         | C               | [link](https://osf.io/d45bw/)                 |
| VulDeePecker | Semantics-based Vulnerability Candidate (SeVC) dataset. Dataset released by NDSS'18 _VulDeePecker: A Deep Learning-Based System for Vulnerability Detection_ | Vulnerability Detection | C/C++ | [link](https://github.com/CGCL-codes/VulDeePecker)  |
| SySeVR |  The Semantics-based Vulnerability Candidate (SeVC) dataset released by arXiv'18 _SySeVR: A Framework for Using Deep Learning to Detect Vulnerabilities_ | Vulnerability Detection | C | [link](https://github.com/SySeVR/SySeVR) |
| Seahymn | Vulnerable functions from 9 open-source software projects | Vulnerability Detection | C | [link](https://github.com/Seahymn2019/Function-level-Vulnerability-Dataset) |
| RAISE19Ferenc | Dataset released by RAISE'19 *Challenging Machine Learning Algorithms in Predicting Vulnerable JavaScript Functions* | Vulnerability Detection | JavaScript | [link](http://www.inf.u-szeged.hu/~ferenc/papers/JSVulnerabilityDataSet/) |
| TypeWriter | Dataset released by FSE'20 *TypeWriter: Neural Type Prediction with Search-based Validation* | Type Inference | Python | [link](http://software-lab.org/projects/TypeWriter/data.tar.gz) |
| DeepTyper | Dataset released by FSE'18 *Deep Learning Type Inference* | Type Inference | JavaScript | [link](https://github.com/DeepTyper/DeepTyper/blob/master/data/repo-SHAs.txt) |
| Typlus | Dataset released by PLDI'20 paper *Typilus: Neural Type Hints* | Type Inference | Python | [link](https://github.com/typilus/typilus/blob/master/src/data_preparation/metadata/popularLibs.txt) |

## Resources
- [[CSUR'18] A Survey of Machine Learning for Big Code and Naturalness](https://ml4code.github.io/papers.html)
- [[CSUR'20] Deep Learning for Source Code Modeling and Generation: Models, Applications, and Challenges](https://dl.acm.org/doi/10.1145/3383458)
- [Awsome Machine Learning on Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code)
