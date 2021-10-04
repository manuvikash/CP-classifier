# FiST-GCN: Frequency-informed Spatial-temporal Graph Convolutional Network
![Image text](https://github.com/zhz95/hzz/blob/master/net2.png)

Cerebral Palsy Prediction using Frequency-informed Spatial-temporal Graph Convolutional Networks

Early diagnosis and intervention is clinically considered as the paramount part of the treatment of cerebral palsy. Designing an efficient automatic prediction system is essential for cerebral palsy early diagnosis. However, the existing deep learning-based methods did not use the frequency information of human motion, which is highly relevant to cerebral palsy. This paper proposes a frequency-informed spatial-temporal graph convolutional network and validates it on the MINI-RGBD dataset. We design a frequency-binning method  that retains the critical frequency of the human joint position data while filtering the noise. We employ an ablation study to validate the advantage of our method and provide an automatic empirical algorithmic for this method. Our method outperforms state-of-the-art researches.

For orginal ST-GCN code, please refer to https://github.com/yysijie/st-gcn/blob/master/OLD_README.md

# Initialization
python >= 3.7

pytorch

# Library requirement and installation
`
pip install requirement.txt
`
`
cd torchlight; python setup.py install; cd ..
`
# Getting started

The command of training models with Leave-One-Out Cross-Validation
```
python start.py
```

