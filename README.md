

# Awesome Machine Learning for Temporal Point Processes Resources
We would like to maintain a list of resources that utilize machine learning technologies to model temporal point processes. 

We mark work contributed by [Thinklab](http://thinklab.sjtu.edu.cn) with ✨.

*Maintained by members in SJTU-Thinklab: Mingquan Feng, Yunhao Zhang, Liangliang Shi and Junchi Yan.*

*We are looking for post-docs interested in machine learning especially for learning combinatorial solvers, dynamic graphs, and reinforcement learning. Please send your up-to-date resume via yanjunchi AT sjtu.edu.cn.* 

## [Content](#content)

* [1. Survey Papers](#1-survey-papers)
* [2. Deep TPP](#2-modeling-papers)
    * [2.1 RNN and Transformer](#21-rnn-and-transformer)
    * [2.2 ODE and SDE](#22-ode-and-sde)
* [3. Traditional TPP](#3-tradtional-tpp)
* [4. Applications](#4-applications)




## 1. Survey Papers

1. **A review of self-exciting spatio-temporal point processes and their applications** JSTOR, 2018. [journal](https://www.jstor.org/stable/26770999?casa_token=Y49nXOAn5l8AAAAA:NmosnJySOB8wHG2r_6tyieWoaHhNdlZ2rI6q0pBkNtd5G_B5h45AwxL58fxLZZiqVWwSOKk5n0ufbZvwuaJ-QITKULDwRf6MQu53ED1p5r5HncxVSbCN)

    *Reinhart, Alex.*

2. **✨Recent advance in temporal point process: from machine learning perspective** SJTU, 2019. [paper](https://thinklab.sjtu.edu.cn/src/pp_survey.pdf)

    *Yan, Junchi*

3. **Neural temporal point processes: A review** Arxiv, 2021. [paper](https://arxiv.org/abs/2104.03528)

    *Shchur, Oleksandr, Ali Caner Türkmen, Tim Januschowski, and Stephan Günnemann*

## 2. Deep TPP

### 2.1 RNN and Transformer

1. **Deep Reinforcement Learning of Marked Temporal Point Processes** NIPS, 2018. [paper](https://arxiv.org/pdf/1805.09360.pdf)

    *Utkarsh Upadhyay, Abir De, Manuel Gomez-Rodriguez*

### 2.2 ODE and SDE
1. **Neural Spatio-Temporal Point Processes** ICLR, 2021. [paper](https://arxiv.org/pdf/2011.04583.pdf), [code](https://github.com/facebookresearch/neural_stpp)

    *Ricky T. Q. Chen, Brandon Amos, Maximilian Nickel*

2. **Latent ODEs for Irregularly-Sampled Time Series** NeurIPS, 2019. [paper](https://papers.nips.cc/paper/2019/file/42a6845a557bef704ad8ac9cb4461d43-Paper.pdf), [code](https://github.com/YuliaRubanova/latent_ode) 

    *Yulia Rubanova, Ricky T. Q. Chen, David Duvenaud*

3. **Neural Jump Stochastic Differential Equations** NeurIPS, 2019. [paper](https://arxiv.org/pdf/1905.10403.pdf), [code](https://github.com/000Justin000/torchdiffeq/tree/jj585)

    *Junteng Jia, Austin R. Benson*

4. **Hawkes Processes with Stochastic Excitations**  ICML, 2016. [paper](https://arxiv.org/pdf/1609.06831.pdf)

    *Young Lee, Kar Wai Lim, Cheng Soon Ong*

## 3. Traditional TPP

1. **Learning Social Infectivity in Sparse Low-rank Networks Using Multi-dimensional Hawkes Processes**  AISTATS, 2013. [paper](http://proceedings.mlr.press/v31/zhou13a.pdf), [code](https://github.com/HongtengXu/Hawkes-Process-Toolkit)

    *Ke Zhou, Hongyuan Zha, and Le Song*

2. **Learning Granger Causality for Hawkes Processes** ICML, 2016. [paper](https://arxiv.org/pdf/1905.10403.pdf), [code](https://arxiv.org/pdf/1602.04511.pdf)

    *Hongteng Xu, Mehrdad Farajtabar, Hongyuan Zha*

3. **A Dirichlet Mixture Model of Hawkes Processes for Event Sequence Clustering**  NIPS, 2017. [paper](https://arxiv.org/pdf/1701.09177.pdf)

    *Hongteng Xu, Hongyuan Zha*

4. **Learning Hawkes Processes from Short Doubly-Censored Event Sequences** ICML, 2017. [paper](https://arxiv.org/pdf/1702.07013.pdf)

    *Hongteng Xu, Dixin Luo, Hongyuan Zha*

5. **Decoupled Learning for Factorial Marked Temporal Point Processes**  SIGKDD, 2018. [paper](https://arxiv.org/pdf/1801.06805v1.pdf)

    *Weichang Wu, Junchi Yan, Xiaokang Yang, Hongyuan Zha*


## 4. Applications

1. **Learning Parametric Models for Social Infectivity in Multi-Dimensional Hawkes Processes**  AAAI, 2014. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/8733)

    *Liangda Li, Hongyuan Zha*

2. **SEISMIC: A Self-Exciting Point Process Model for Predicting Tweet Popularity** KDD, 2015. [paper](https://dl.acm.org/doi/abs/10.1145/2783258.2783401)

    *Qingyuan Zhao, Murat A. Erdogdu, Hera Y. He, Anand Rajaraman, Jure Leskovec*

3. **Trailer Generation via a Point Process-Based Visual Attractiveness Model**  IJCAI, 2015. [paper](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/view/11296/10969)

    *Hongteng Xu, Yi Zhen, Hongyuan Zha*

4. **On Machine Learning towards Predictive Sales Pipeline Analytics**  AAAI, 2015. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9444)

    *Junchi Yan, Chao Zhang, Hongyuan Zha, Min Gong, Changhua Sun, Jin Huang, S. Chu, Xiaokang Yang*

5. **PInfer: Learning to Infer Concurrent Request Paths from System Kernel Events** ICAC, 2016. [paper](https://rhee.systems/pubs/pinfer-icac16.pdf)

    *Hongteng Xu, Xia Ning, Hui Zhang, Junghwan Rhee, Guofei Jiang*

6. **Modeling Contagious Merger and Acquisition via Point Processes with a Profile Regression Prior** IJCAI, 2016. [paper](https://www.ijcai.org/Proceedings/16/Papers/382.pdf)

    *Junchi Yan, Shuai Xiao, Changsheng Li, Bo Jin, Xiangfeng Wang, Bin Ke, Xiaokang Yang, Hongyuan Zha*

7. **Patient Flow Prediction via Discriminative Learning of Mutually-Correcting Processes**  TKDE, 2016. [paper](https://arxiv.org/pdf/1602.05112.pdf)

    *Hongteng Xu , Weichang Wu , Shamim Nemati , Hongyuan Zha*

8. **Expecting to be HIP: Hawkes Intensity Processes for Social Media Popularity** WWW, 2017. [paper](https://arxiv.org/pdf/1602.06033.pdf)

    *Marian-Andrei Rizoiu, Lexing Xie, Scott Sanner, Manuel Cebrian, Honglin Yu, Pascal Van Hentenryck*

9. **On Predictive Patent Valuation: Forecasting Patent Citations and Their Types** AAAI, 2017. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14385)

    *Xin Liu, Junchi Yan, Shuai Xiao, Xiangfeng Wang, H. Zha, S. Chu*

10. **LMPP: A Large Margin Point Process Combining Reinforcement and Competition for Modeling Hashtag Popularity**  IJCAI, 2017. [paper](https://www.ijcai.org/proceedings/2017/0373.pdf)

    *Bidisha Samanta, A. De, Abhijnan Chakraborty, Niloy Ganguly*

11. **Shaping Opinion Dynamics in Social Networks** AAMAS, 2018. [paper](https://ifaamas.org/Proceedings/aamas2018/pdfs/p1336.pdf)

    *Abir De, Sourangshu Bhattacharya, Niloy Ganguly*

12. **Adversarial Training Model Unifying Feature Driven and Point Process Perspectives for Event Popularity Prediction**  CIKM, 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271714)

    *Qitian Wu, Chaoqi Yang, Hengrui Zhang, Xiaofeng Gao, Paul Weng, Guihai Chen*

13. **CRPP: Competing Recurrent Point Process for Modeling Visibility Dynamics in Information Diffusion**  CIKM, 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271726)

    *Avirup Saha, Bidisha Samanta, Niloy Ganguly, Abir De*

14. **Recurrent Spatio-Temporal Point Process for Check-in Time Prediction**  CIKM, 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3272003)

    *Guolei Yang, Ying Cai, Chandan K. Reddy *

15. **Modeling Sequential Online Interactive Behaviors with Temporal Point Process**  CIKM, 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271782)

    *Renqin Cai, Xueying Bai, Zhenrui Wang, Yuling Shi, Parikshit Sondhi, Hongning Wang *

16. **INITIATOR: Noise-contrastive Estimation for Marked Temporal Point Process**  IJCAI, 2018. [paper](https://www.ijcai.org/Proceedings/2018/0303.pdf)

    *Ruocheng Guo, Jundong Li, Huan Liu*

17. **Learning Network Traffic Dynamics Using Temporal Point Process**  IEEE INFOCOM 2019. [paper](https://ieeexplore.ieee.org/abstract/document/8737622)

    *Avirup Saha; Niloy Ganguly; Sandip Chakraborty; Abir De*

18. **Understanding species distribution in dynamic populations: a new approach using spatio-temporal point process models**  Ecography, 2019, 42(6): 1092-1102. [journal](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/ecog.03771)

    *Andrea Soriano-Redondo, Charlotte M. Jones-Todd, Stuart Bearhop, Geoff M. Hilton, Leigh Lock, Andrew Stanbury, Stephen C. Votier and Janine B. Illian*

19. **Modeling Event Propagation via Graph Biased Temporal Point Process**  IEEE Transactions on Neural Networks and Learning Systems, 2020. [paper](https://ieeexplore.ieee.org/abstract/document/9138462)

    *Weichang Wu; Huanxi Liu; Xiaohu Zhang; Yu Liu; Hongyuan Zha*

20. **VigDet: Knowledge Informed Neural Temporal Point Process for Coordination Detection on Social Media**  NeurIPS 2021. [paper](https://arxiv.org/pdf/2110.15454.pdf)

    *Yizhou Zhang, Karishma Sharma, Yan Liu*