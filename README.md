# Machine Learning for Astronomical Source Classification
Exploring Diverse Machine Learning Techniques for Astronomical Source Classification Using Images and Photometric Features.

For any queries, please contact at srinadhml99@gmail.com
Arxiv link: https://arxiv.org/abs/2408.13634

# Classical ML Algorithms 
We studied several classical ML algorithms for classification between Star-Galaxy and Star-Galaxy-Quasar using photometric features alone. The files can be found at **[MLAlgos](./Ex1_SG_BayesianMargNet.ipynb)**.

**Table 1: Classical ML Baselines (DT, RF, GBDT) Performance**

| Experiment | Classification Task | Model | Accuracy (%) | Precision (%) | Recall (%) |
|---|---|---|---|---|---|
| **Experiment 1** | Star-Galaxy | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT | |  |  |
| Compact Train/Test | Star-Galaxy-Quasar | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT |  |  |  |
| **Experiment 2** | Star-Galaxy | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT |  |  |  |
| Faint+Compact Train/Test | Star-Galaxy-Quasar | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT |  |  |  |
| **Experiment 3** | Star-Galaxy | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT |  |  |  |
| Compact Train, Faint+Compact Test | Star-Galaxy-Quasar | DT |  |  |  |
|  |  | RF |  |  |  |
|  |  | GBDT |  |  |  |

# MargNet
Unofficial PyTorch implementation of the paper, **[Photometric identification of compact galaxies, stars and quasars using multiple neural networks](https://academic.oup.com/mnras/article/518/2/3123/6831636?login=false&utm_source=authortollfreelinkguestAccessKey=10ada097-d979-4037-84af-c72d47f5c21b)**.
The official implementation in TensorFlow can be found at **[here](https://github.com/sidchaini/MargNet/tree/main)**. 

# MargFormer
This part of the work (studied as MM ViT) was published in the Journal of **[Astrophysics and Space Science](https://link.springer.com/article/10.1007/s10509-024-04357-9)**. The arxiv pre-print is **[here](https://arxiv.org/pdf/2408.13634)**.


# Bayesian MargNet and Bayesian MargFormer
Bayesian Neural Networks are also studied with MargNet and MargFormer. For reference, you can have a look at the file **[Ex1_SG_BayesianMargNet.ipynb](./Ex1_SG_BayesianMargNet.ipynb)**.

More details will be shared soon.

# Contrastive Learning (CL)
## Self-Supervised (SimCLR)
## Supervised 
For initial experiments please check: https://github.com/srinadh99/Contrastive-Learning-for-Astronomy-

More details and codes will be shared soon.

# Conformal Predictions
For initial experiments, please check, https://github.com/srinadh99/AstroFormer/tree/main/MargFormerCP
