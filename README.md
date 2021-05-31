# FiST-GCN: Frequency-informed Spatial-temporal Graph Convolutional Network
Cerebral Palsy Prediction using Frequency-informed Spatial-temporal Graph Convolutional Networks

Early diagnosis of cerebral palsy and intervention is clinically considered as the paramount part of the treatment of cerebral palsy. Designing an efficient automatic prediction system is essential for cerebral palsy early diagnosis. However, the existing deep learning-based methods did not use the frequency information highly relevant to CP and limited by the challenge of small training data size. This paper proposes a frequency-informed spatial-temporal graph convolutional network and validates it on the MINI-RGBD dataset. We design a frequency-binning method  that retains the critical frequency of the data while filtering the noise. We employ an ablation study to validate the advantage of our method and provide an automatic empirical algorithmic for this method. Our method outperforms state-of-the-art researches by achieving a 100% prediction accuracy.

For orginal ST-GCN code, please refer to https://github.com/yysijie/st-gcn/blob/master/OLD_README.md

# Requirement
See in requirement.txt

# Getting started

The command of training models with Leave-One-Out Cross-Validation
```
python start.py
```

