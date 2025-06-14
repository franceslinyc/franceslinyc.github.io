---
layout: post
title:  "Some referenes"
date:   2023-09-04 08:05:00
categories: jekyll update
published: false
---
### Methods for big spatial data -- from statistics 

Sun, Y., Li, B., & Genton, M. G. (2012). Geostatistics for large datasets. In Advances and challenges in space-time modelling of natural events (pp. 55-77). Springer Berlin Heidelberg.

Bradley, J. R., Cressie, N., & Shi, T. (2016). A comparison of spatial predictors when datasets could be very large.

[Heaton, M. J., Datta, A., Finley, A. O., Furrer, R., Guinness, J., Guhaniyogi, R., ... & Zammit-Mangion, A. (2019). A case study competition among methods for analyzing large spatial data. Journal of Agricultural, Biological and Environmental Statistics, 24, 398-425.](https://www.scienceopen.com/document_file/44268d42-af9d-4a92-8004-cc2b0855bd0a/PubMedCentral/44268d42-af9d-4a92-8004-cc2b0855bd0a.pdf)


### Methods for big spatial data -- from ML/AI

[Das, S., Roy, S., & Sambasivan, R. (2018). Fast gaussian process regression for big data. Big data research, 14, 12-26.](https://arxiv.org/pdf/1509.05142.pdf)

- Apply the proposed method for regression tasks for various datasets: Combined Cycle Power Plant, Ailerons from LIAD (Laboratory of Artificial Intelligence and Decision), Elevators from LIAD, California Housing from LIAD, Airline Delay from DOT, Household Power Consumption from UCI, and the sinc function.

- Compare to other methods such as Sparse Gaussian Process and Stochastic Variational Gaussian Process.

[Liu, H., Ong, Y. S., Shen, X., & Cai, J. (2020). When Gaussian process meets big data: A review of scalable GPs. IEEE transactions on neural networks and learning systems, 31(11), 4405-4423.](https://arxiv.org/pdf/1807.01065.pdf)

[Jakkala, K. (2021). Deep Gaussian processes: A survey. arXiv preprint arXiv:2106.12135.](https://arxiv.org/pdf/2106.12135.pdf)

[Hazra, A., Nag, P., Yadav, R., & Sun, Y. (2023). Exploring the Efficacy of Statistical and Deep Learning Methods for Large Spatial Datasets: A Case Study. arXiv preprint arXiv:2308.05812.](https://arxiv.org/pdf/2308.05812.pdf)

- The results showed that proper statistical models (BCL, GpGp, GpGp0, SPDE, and NNGP) consistently outperformed other (i.e., deep learning and algorithmic) approaches (DeepGP, DeepKriging, Gap-fill, FRK) on all five simulated competition datasets and also the total precipitable water (TPW) dataset.

[Hensman, J., Fusi, N., & Lawrence, N. D. (2013). Gaussian processes for big data. arXiv preprint arXiv:1309.6835.](https://arxiv.org/pdf/1309.6835.pdf)

[Titsias, M. (2009, April). Variational learning of inducing variables in sparse Gaussian processes. In Artificial intelligence and statistics (pp. 567-574). PMLR.](http://proceedings.mlr.press/v5/titsias09a/titsias09a.pdf)



### Methods for spatial data -- from statistics

### Methods for spatial data -- from ML/AI

[Jiang, Z. (2018). A survey on spatial prediction methods. IEEE Transactions on Knowledge and Data Engineering, 31(9), 1645-1664.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8444678)

- Provide a systematic review on the principles and methods on spatial prediction.

- Provide a taxonomy of existing spatial prediction methods, as shown in Fig. 1.

[Shekhar, S., Evans, M. R., Kang, J. M., & Mohan, P. (2011). Identifying patterns in spatial information: A survey of methods. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery, 1(3), 193-214.](http://i2pc.es/coss/Docencia/SignalProcessingReviews/Shekhar2011.pdf)

### GP (Gaussian process) models

### Variants of GPs

### NNGPs (Nearest-neighbor Gaussian process)

Datta, A., Banerjee, S., Finley, A. O., & Gelfand, A. E. (2016). Hierarchical nearest-neighbor Gaussian process models for large geostatistical datasets. Journal of the American Statistical Association, 111(514), 800-812.

Finley, A. O., Datta, A., Cook, B. D., Morton, D. C., Andersen, H. E., & Banerjee, S. (2019). Efficient algorithms for Bayesian nearest neighbor Gaussian processes. Journal of Computational and Graphical Statistics, 28(2), 401-414.

### NNMPs (Nearest-neighbor mixture process)

[Zheng, X., Kottas, A., & Sansó, B. (2022a). On construction and estimation of stationary mixture transition distribution models. Journal of Computational and Graphical Statistics, 31(1), 283-293.](https://arxiv.org/pdf/2010.12696.pdf)

[Zheng, X., Kottas, A., & Sansó, B. (2022b). Nearest-Neighbor Mixture Models for Non-Gaussian Spatial Processes. arXiv preprint arXiv:2107.07736.](https://arxiv.org/pdf/2107.07736)

[Zheng, X., Kottas, A., & Sansó, B. (2022c). Bayesian Geostatistical Modeling for Discrete-Valued Processes. arXiv preprint arXiv:2111.01840.](https://onlinelibrary.wiley.com/doi/full/10.1002/env.2805)

### Deep learning for spatial data

[Wang, H., Guan, Y., & Reich, B. (2019, November). Nearest-neighbor neural networks for geostatistics. In 2019 international conference on data mining workshops (ICDMW) (pp. 196-205). IEEE.](https://arxiv.org/pdf/1903.12125.pdf)

[Zammit-Mangion, A., Ng, T. L. J., Vu, Q., & Filippone, M. (2022). Deep compositional spatial models. Journal of the American Statistical Association, 117(540), 1787-1808.](https://arxiv.org/pdf/1906.02840.pdf)

[Hazra, A., Nag, P., Yadav, R., & Sun, Y. (2023). Exploring the Efficacy of Statistical and Deep Learning Methods for Large Spatial Datasets: A Case Study. arXiv preprint arXiv:2308.05812.](https://arxiv.org/pdf/2308.05812.pdf)

#### Deep GPs

[Damianou, A., & Lawrence, N. D. (2013, April). Deep gaussian processes. In Artificial intelligence and statistics (pp. 207-215). PMLR.](http://proceedings.mlr.press/v31/damianou13a.pdf)

[Jakkala, K. (2021). Deep Gaussian processes: A survey. arXiv preprint arXiv:2106.12135.](https://arxiv.org/pdf/2106.12135.pdf)

#### Deep kriging

[Chen, W., Li, Y., Reich, B. J., & Sun, Y. (2020). Deepkriging: Spatially dependent deep neural networks for spatial prediction. arXiv preprint arXiv:2007.11972.](https://arxiv.org/pdf/2007.11972.pdf)

#### Convolutional Gaussian Processes

[Van der Wilk, M., Rasmussen, C. E., & Hensman, J. (2017). Convolutional gaussian processes. Advances in Neural Information Processing Systems, 30.](https://proceedings.neurips.cc/paper_files/paper/2017/file/1c54985e4f95b7819ca0357c0cb9a09f-Paper.pdf)

[Blomqvist, K., Kaski, S., & Heinonen, M. (2020). Deep convolutional Gaussian processes. In Machine Learning and Knowledge Discovery in Databases: European Conference, ECML PKDD 2019, Würzburg, Germany, September 16–20, 2019, Proceedings, Part II (pp. 582-597). Springer International Publishing.](https://arxiv.org/pdf/1810.03052.pdf)

#### DGMRF

[Sidén, P., & Lindsten, F. (2020, November). Deep gaussian markov random fields. In International conference on machine learning (pp. 8916-8926). PMLR.](http://proceedings.mlr.press/v119/siden20a/siden20a.pdf)

- Establish a formal connection between GMRFs and convolutional neural networks (CNNs).

- Refer to Lindgren et al., 2011 for the link between GPs and GMRFs. 

- DGMRF outperforms all the methods from the competition on all criteria (e.g. MAE, RMSE, CRPS, INT) except CVG, where it is slightly worse than NNGP (Nearest-neighbor Gaussian process). 




### Deep learning

[Schmidhuber, J. (2015). Deep learning in neural networks: An overview. Neural networks, 61, 85-117.](https://arxiv.org/pdf/1404.7828.pdf)

[LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. nature, 521(7553), 436-444.](https://creativecoding.soe.ucsc.edu/courses/cs523/slides/week3/DeepLearning_LeCun.pdf)

Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press.

[Fan, J., Ma, C., & Zhong, Y. (2021). A selective overview of deep learning. Statistical science: a review journal of the Institute of Mathematical Statistics, 36(2), 264.](https://arxiv.org/abs/1904.05526)

- Discuss: What is deep learning? What are the new characteristics of deep learning, compared with classical methods? What are the theoretical foundations of deep learning? from a statistical point of view. 



### Methods for spatiotemporal data

[Shekhar, S., Jiang, Z., Ali, R. Y., Eftelioglu, E., Tang, X., Gunturi, V. M., & Zhou, X. (2015). Spatiotemporal data mining: A computational perspective. ISPRS International Journal of Geo-Information, 4(4), 2306-2338.](https://www.mdpi.com/2220-9964/4/4/2306)

[Atluri, G., Karpatne, A., & Kumar, V. (2018). Spatio-temporal data mining: A survey of problems and methods. ACM Computing Surveys (CSUR), 51(4), 1-41.](https://dl.acm.org/doi/pdf/10.1145/3161602)



### Generative mixture models 

#### Mixture-based models

Harshvardhan, G. M., Gourisaria, M. K., Pandey, M., & Rautaray, S. S. (2020). A comprehensive survey and analysis of generative models in machine learning. Computer Science Review, 38, 100285.


### Copula-based models 

#### Copula

#### Copula-based models for non-Gaussian time series

Escarela, G., Mena, R. H., & Castillo-Morales, A. (2006). A flexible class of parametric transition regression models based on copulas: application to poliomyelitis incidence. Statistical Methods in Medical Research, 15(6), 593-609.

Huang, X. W., & Emura, T. (2022). Computational methods for a copula-based Markov chain model with a binomial time series. Communications in Statistics-Simulation and Computation, 1-18.

#### Copula-based models for non-Gaussian spatial data

### Methods for time series (temporal data)

Hassan, M. Y. (2021). The deep learning LSTM and MTD models best predict acute respiratory infection among under-five-year old children in Somaliland. Symmetry, 13(7), 1156.

- The results of this study have shown that no model is a panacea over the other two models, but they demonstrated that the deep learning LSTM (long short term memory) and EM-algorithm based MTD (mixture transitions distribution) models slightly outperformed the classical SARIMA (seasonal autoregressive integrated moving averages) model in predicting ARI (acute respiratory infection) values. 


### Big data

[Sagiroglu, S., & Sinanc, D. (2013, May). Big data: A review. In 2013 international conference on collaboration technologies and systems (CTS) (pp. 42-47). IEEE.](https://academics.uccs.edu/~ooluwada/courses/datamining/ExtraReading/Big_data_A_review.pdf)

### Big spatial data

### Big time series

