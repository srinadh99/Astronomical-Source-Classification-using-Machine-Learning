# Machine Learning for Astronomical Source Classification
Exploring Diverse Machine Learning Techniques for Astronomical Source Classification Using Images and Photometric Features.

For any queries, please contact at srinadhml99@gmail.com
Arxiv link: https://arxiv.org/abs/2408.13634

# Classical ML Algorithms 
We studied several classical ML algorithms for classification between Star-Galaxy and Star-Galaxy-Quasar using photometric features alone. The files can be found at **[MLAlgos](./Ex1_SG_BayesianMargNet.ipynb)**.

**Table 1: Classical ML Classification Performance**

| Experiment | Classification Task | Accuracy (%) | Precision (%) | Recall (%) |
|---|---|---|---|---|
| **Experiment 1** | Star-Galaxy | 98.1 ± 0.1 | 98.1 ± 0.1 | 98.1 ± 0.1 |
| Compact Train/Test | Star-Galaxy-Quasar | 93.2 ± 0.1 | 93.3 ± 0.1 | 93.2 ± 0.1 |
| **Experiment 2** | Star-Galaxy | 97.1 ± 0.1 | 97.1 ± 0.1 | 97.1 ± 0.1 |
| Faint+Compact Train/Test | Star-Galaxy-Quasar | 86.7 ± 0.1 | 86.8 ± 0.1 | 86.7 ± 0.1 |
| **Experiment 3** | Star-Galaxy | 92.7 ± 0.1 | 93.2 ± 0.1 | 92.7 ± 0.1 |
| Compact Train, Faint+Compact Test | Star-Galaxy-Quasar | 75.2 ± 0.1 | 77.9 ± 0.1 | 75.3 ± 0.1 |


# MargNet
Unofficial PyTorch implementation of the paper, **[Photometric identification of compact galaxies, stars and quasars using multiple neural networks](https://academic.oup.com/mnras/article/518/2/3123/6831636?login=false&utm_source=authortollfreelinkguestAccessKey=10ada097-d979-4037-84af-c72d47f5c21b)**.
The official implementation in TensorFlow can be found at **[here](https://github.com/sidchaini/MargNet/tree/main)**. 

# MargFormer
This part of the work (studied as MM ViT) was published in the Journal of **[Astrophysics and Space Science](https://link.springer.com/article/10.1007/s10509-024-04357-9)**. The arxiv pre-print is **[here](https://arxiv.org/pdf/2408.13634)**.


# Bayesian MargNet and Bayesian Margformer
Bayesian Neural Networks are also studied with MargNet and MargFormer. For reference, you can have a look at the file **[Ex1_SG_BayesianMargNet.ipynb](./Ex1_SG_BayesianMargNet.ipynb)**.

More details will be shared soon.

# Conformal Predictions

