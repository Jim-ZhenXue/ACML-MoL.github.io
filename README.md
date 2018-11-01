# Motivation and Objectives 

Multi-output learning [1][13] aims to predict multiple outputs for an input, where the output values are characterized by diverse data types, such as binary, nominal, ordinal and real-valued variables. Such learning tasks arise in a variety of real-world applications, ranging from document classification, computer emulation, sensor network analysis, concept-based information retrieval, human action/causal induction, to video analysis, image annotation/retrieval, gene function prediction and brain science. Due to its popularity in applications, multi-output learning has also been widely explored in machine learning community, such as multi-label/multi-class classification [2][8], multi-target regression, hierarchical classification with class taxonomies, label sequence learning, sequence alignment learning, and supervised grammar learning, and so on.

The theoretical properties of existing approaches for multi-output data are still not well understood. This triggers practitioners to develop novel methodologies [5][9][11] and theories [3] to deeply understand multi-output learning tasks. Moreover, the emerging trends of ultrahigh input and output dimensionality [7], and the complexly structured objects [4], lead to formidable challenges for multi-output learning. Therefore, it is imperative to propose practical mechanisms and efficient optimization algorithms [8][10][12] for large-scale applications. Deep learning has gained much popularity in today’s research, and has been developed in recent years to deal with multi-label and multi-class classification problems. However, it remains non-trivial for practitioners to design novel deep neural networks [6] that are appropriate for more comprehensive multi-output learning domains.

# Topics of Interest 

Interested topics include, but are not limited to: 

- Novel deep learning methods for multi-output learning tasks. 

- Novel modellings for multi-output learning from new perspectives. 

- Statistical theory analysis for multiple output learning. 

- Large-scale optimization algorithms for multiple output learning. 

- Sparse representation learning for large-scale multiple output learning. 

- Active learning for multi-output data. 

- Online learning for multi-output data. 

- Metric learning for multi-output data. 

- Multi-output learning with noisy data. 

- Multi-output learning with imbalanced data. 

# Submission Guidelines 

Workshop submissions and camera ready versions will be handled by Microsoft CMT. Click [https://cmt3.research.microsoft.com/ACMLMoL2018](https://cmt3.research.microsoft.com/ACMLMoL2018) for submission. 

Papers should be formatted according to the ACML formatting instructions for the Conference Track. The submissions with 2 pages will be considered for the poster, while submissions with at least 6 pages will be considered for the oral presentation. The selective oral papers will be invited for IEEE TNNLS Special Issue on "Structured Multi-output Learning: Modelling, Algorithm, Theory and Applications" ([https://cis.ieee.org/images/files/Documents/Transactions/TNNLS/TNNLS_SMLMATA-CFP.pdf](https://cis.ieee.org/images/files/Documents/Transactions/TNNLS/TNNLS_SMLMATA-CFP.pdf)).

ACML-MoL is a non-archival venue and there will be no published proceedings. The papers will be posted on the workshop website. It will be possible to submit to other conferences and journals both in parallel to and after ACML-MoL'18. Besides, we also welcome submissions to ACML-MoL that are under review at other conferences and workshops. 

At least one author from each accepted paper must register for the workshop. Please see the ACML 2018 Website for information about accommodation and registration.

# Tentative Schedule

8:45 - 9:00    Opening 

9:00 - 10:00   Keynote talk by **Tao Qin**

*Title: Recent Advances in Neural Machine Translation*

Abstract: Machine translation is a challenging machine learning problem as it needs to predict a complex output (a sequence of words) given an input. In this talk, we will present recent advances in neural machine translation, including (1) advanced models, from RNN to CNN and Transformer, (2) improved word representations, e.g., FRAGE, (3) advanced training algorithms, e.g., multi-agent dual learning and dual learning, and (4) efficent infernece, e.g., nan-autoregressive models.


10:00 - 10:20   Coffee Break 

10:20 - 10:40   Invited talk by **Joey Tianyi Zhou**

*Title: DATNet: Dual Adversarial Transfer for Low-resource Named Entity Recognition*

10:40 - 11:00   Invited talk by **Quanming Yao**

*Title: Learning with Heterogeneous Side Information Fusion for Recommender Systems*

11:00 - 11:20   Paper talk 1

11:20 - 11:40   Paper talk 2

11:40 - 13:30   Lunch

13:30 - 14:30   Keynote talk by **Le Song**

<small> *Title: Syntax-Directed Variational Autoencoder for Structure Output* <small>
 
<sub><sup> Abstract: Deep generative models have been enjoying success in modeling continuous data. However it remains challenging to capture the representations for discrete structures with formal grammars and semantics, e.g., computer programs and molecular structures. How to generate both syntactically and semantically correct data still remains largely an open problem. Inspired by the theory of compiler where the syntax and semantics check is done via syntax-directed translation (SDT), we propose a novel syntax-directed variational autoencoder (SD-VAE) by introducing stochastic lazy attributes. This approach converts the offline SDT check into on-the-fly generated guidance for constraining the decoder. Comparing to the state-of-the-art methods, our approach enforces constraints on the output space so that the output will be not only syntactically valid, but also semantically reasonable. We evaluate the proposed model with applications in programming language and molecules, including reconstruction and program/molecule optimization. The results demonstrate the effectiveness in incorporating syntactic and semantic constraints in discrete generative models, which is significantly better than current state-of-the-art approaches.<sub><sup>

14:30 - 14:50   Invited talk by **Liang Feng**

*Title: Multi-task Optimization through Denoising Autoencoding*

14:50 - 15:10   Paper talk 3

15:10 - 15:30   Closing

# Important Dates 

Submission:     13 Oct, 2018. 

Notification:   30 Oct, 2018. 

Workshop:       14 Nov, 2018. 

# Organizers

Weiwei Liu, University of New South Wales, Australia. 

Xiaobo Shen, Nanyang Technological University, Singapore. 

Yew-Soon Ong, Nanyang Technological University, Singapore. 

Ivor W. Tsang, University of Technology Sydney, Australia. 

Chen Gong, Nanjing University of Science and Technology, China.

# Reference

[1] Mauricio A. Álvarez, Lorenzo Rosasco, Neil D. Lawrence, Kernels for Vector-Valued Functions: A Review, Foundations and Trends in Machine Learning, 2012.

[2] Weiwei Liu, Ivor W. Tsang, Large Margin Metric Learning for Multi-Label Prediction, AAAI, 2015.

[3] Weiwei Liu, Ivor W. Tsang, On the Optimality of Classifier Chain for Multi-label Classification, NIPS, 2015.

[4] Mingkui Tan, Qinfeng Shi, Anton van den Hengel, Chunhua Shen, Junbin Gao, Fuyuan Hu, Zhen Zhang, Learning graph structure for multi-label image classification via clique generation, CVPR, 2015.

[5] Chen Gong, Dacheng Tao, Jie Yang, Wei Liu, Teaching-to-Learn and Learning-to-Teach for Multi-label Propagation, AAAI, 2016.

[6] Moustapha Cissé, Maruan Al-Shedivat, Samy Bengio, ADIOS: Architectures Deep In Output Space, ICML, 2017.

[7] Weiwei Liu, Ivor W. Tsang, Making Decision Trees Feasible in Ultrahigh Feature and Label Dimensions, JMLR, 2017.

[8] Weiwei Liu, Ivor W. Tsang, Klaus-Robert Müller, An Easy-to-hard Learning Paradigm for Multiple Classes and Multiple Labels, JMLR, 2017.

[9] Chen Gong, Tongliang Liu, Yuanyan Tang, Jian Yang, Jie Yang, Dacheng Tao, A Regularization Approach for Instance-Based Superset Label Learning, TCYB, 2018.

[10] Xiaobo Shen, Weiwei Liu, Ivor W. Tsang, Quan-Sen Sun, Yew-Soon Ong, Compact Multi-Label Learning, AAAI, 2018.

[11] Xiaobo Shen, Weiwei Liu, Ivor W. Tsang, Quan-Sen Sun, Yew-Soon Ong, Multilabel Prediction via Cross-View Search, TNNLS, 2018.

[12] Xiaobo Shen, Weiwei Liu, Yong Luo, Yew-Soon Ong, Ivor W. Tsang, Deep Discrete Prototype Multilabel Learning, IJCAI, 2018.

[13] Weiwei Liu, Donna Xu, Ivor Tsang, Wenjie Zhang, Metric Learning for Multi-output Tasks, TPAMI, 2018.
