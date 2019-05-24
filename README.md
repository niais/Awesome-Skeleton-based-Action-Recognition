# Awesome-Skeleton-based-Action-Recognition

```txt
If you have any problems, suggestions or improvements, please submit the issue or PR.
```

---

- Other GITHUB Repos for Skeleton-based Action Recognition Papers
  - [<https://github.com/XiaoCode-er/Skeleton-Based-Action-Recognition-Papers>](https://github.com/XiaoCode-er/Skeleton-Based-Action-Recognition-Papers)
  - [<https://github.com/cagbal/Skeleton-Based-Action-Recognition-Papers-and-Notes>](https://github.com/cagbal/Skeleton-Based-Action-Recognition-Papers-and-Notes)

---

## TODO

- [ ] Paper list  
  - [ ] paper links
  - [ ] available codes
  - [ ] more journal papers
- [ ] Leader board
  - [ ] NTU-RGB+D
  <!-- - [ ] SYSU
  - [ ] SBU
  - [ ] N-UCLA -->

## Contents

- [Awesome-Skeleton-based-Action-Recognition](#awesome-skeleton-based-action-recognition)
  - [TODO](#todo)
  - [Contents](#contents)
  - [Misc](#misc)
  - [Datasets](#datasets)
  - [Papers](#papers)
    - [arXiv papers](#arxiv-papers)
    - [2019](#2019)
    - [2018](#2018)
    - [2017](#2017)
    - [2016](#2016)
    - [2015](#2015)
    - [before 2015](#before-2015)
  - [LeaderBoard](#leaderboard)
    - [NTU-RGB+D](#ntu-rgbd)

## Misc

- Microsoft kinect sensor and its effect (**IEEE Multimedia 2012**)
  
## Datasets

- NTU RGB+D Dataset (**NTU-RGB+D**)
- SYSU 3D Human-Object Interaction Dataset (**SYSU**)
- UWA3D Multiview Activity II Dataset (**UWA3D**)
- Northwestern-UCLA Dataset (**N-UCLA**)
- SBU Kinect Interaction Dataset (**SBU**)

## Papers

### arXiv papers

This section only includes the last ten papers since 2018 in [arXiv.org](arXiv.org). Note that arXiv papers **without available codes** are not included into [the leaderboard of performance](#LeaderBoard).

- Skeleton-Based Action Recognition with Synchronous Local and Non-local Spatio-temporal Learning and Frequency Attention [[paper](https://arxiv.org/pdf/1811.04237.pdf)]
<!-- ### Survey -->

### 2019

- **[AS-GCN]**] Actional-Structural Graph Convolutional Networks for Skeleton-based Action Recognition (**CVPR2019**)
- **[AGC-LSTM]** An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition (**CVPR2019**)

### 2018

- Beyond Joints: Learning Representations from Primitive Geometries for Skeleton-based Action Recognition and Detection (***TIP 2018***)
- **[DPRL]** Deep progressive reinforcement learning for skeleton-based action recognition (**CVPR2018**)
- **[SR-TSL]** Skeleton based action recognition with spatial reasoning and temporal stack learning (**ECCV2018**)
- **[HCN]** Co-occurrence feature learning from skeleton data for action recognition and detection with hierarchical aggregation (**IJCAI2018**) [[Reimplementation](https://github.com/huguyuehuhu/HCN-pytorch)]
- Memory attention networks for skeleton-based action recognition (**IJCAI2018**)
- **[ST-GCN]** Spatial temporal graph convolutional networks for skeleton-based action recognition (**AAAI2018**) [[code](https://github.com/yysijie/st-gcn)]
- Spatio-temporal graph convolution for skeleton based action recognition (**AAAI2018**)
- Beyond Joints: Learning Representations from Primitive Geometries for  Skeleton-based Action Recognition and Detection (**TIP2018**) [paper] [[code](https://github.com/hongsong-wang/Beyond-Joints)]

### 2017

- Jointly learning heterogeneous features for RGB-D activity recognition (***TPAMI 2017***)
- **[Visualization CNN]** Enhanced skeleton visualization for view invariant human action recognition (***Pattern Recognition 2017***)
- Global context-aware attention lstm networks for 3d action recognition (**CVPR2017**)
- **[Two-stream RNN]** Modeling temporal dynamics and spatial configurations of actions using two-stream recurrent neural networks (**CVPR2017**)
- **[C-CNN + MTLN]** A new representation of skeleton sequences for 3d action recognition (**CVPR2017**)
- **[Temporal Conv]** Interpretable 3d human action analysis with temporal convolutional networks (**CVPR2017**)
- **[Ensemble TS-LSTM]** Ensemble deep learning for skeleton-based action recognition using temporal sliding lstm networks (**ICCV2017**)
- **[VA-LSTM]** View adaptive recurrent neural networks for high performance human action recognition from skeleton data (**ICCV2017**)
- Learning action recognition model from depth and skeleton videos (**ICCV2017**)
- **[STA-LSTM]** An end-to-end spatio-temporal attention model for human action recognition from skeleton data (**AAAI2017**)
- Skeleton-based action recognition using LSTM and CNN (*ICME Workshop 2017*)
- Skeleton-based action recognition with convolutional neural networks (*ICME Workshop 2017*)
- PKU-MMD: A large scale benchmark for continuous multi-modal human action understanding (*ACMMM Workshop 2017*)
- Interpretable 3d human action analysis with temporal convolutional networks (*CVPR Workshop 2017*)
  
### 2016

- **[Trust Gate ST-LSTM]** Spatio-temporal lstm with trust gates for 3d human action recognition (**ECCV2016**)
- **[Part-aware LSTM]** NTU RGB+D: A Large Scale Dataset for 3D Human Activity Analysis (**CVPR2016**) [[paper](https://)]
- Rolling rotations for recognizing human actions from 3d skeletal data (**CVPR2016**)
- Co-occurrence feature learning for skeleton based action recognition using regularized deep lstm networks (**AAAI2016**)

### 2015

- Skeleton based action recognition with convolutional neural network (**ACPR2015**)
- **[H-RNN]** Hierarchical recurrent neural network for skeleton based action recognition (**CVPR2015**)
- Jointly learning heterogeneous features for rgb-d activity recognition (**CVPR2015**)
  
### before 2015

- [**LieGroup**] Human action recognition by representing 3d skeletons as points in a lie group (**CVPR2014**)
- Human action recognition using a temporal hierarchy of covariance
descriptors on 3d joint locations (**IJCAI2013**)

## LeaderBoard

The section is being continually updated. Note that some values have superscript, which indicates their source. We only show results on large-scale dataset NTU-RGB+D.

### NTU-RGB+D

| Year | Methods              | Cross-Subject | Cross-View |
| ---- | -------------------- | :-----------: | :--------: |
| 2014 | Lie Group            | 50.1          | 52.8       |
| 2015 | H-RNN                | 59.1          | 64.0       |
| 2016 | Part-aware LSTM      | 62.9          | 70.3       |
| 2016 | Trust Gate ST-LSTM   | 69.2          | 77.7       |
| 2017 | Two-stream RNN       | 71.3          | 79.5       |
| 2017 | STA-LSTM             | 73.4          | 81.2       |
| 2017 | Ensemble TS-LSTM     | 74.6          | 81.3       |
| 2017 | Visualization CNN    | 76.0          | 82.6       |
| 2017 | C-CNN + MTLN         | 79.6          | 84.8       |
| 2017 | Temporal Conv        | 74.3          | 83.1       |
| 2017 | VA-LSTM              | 79.4          | 87.6       |
| 2018 | ST-GCN               | 81.5          | 88.3       |
| 2018 | DPRL                 | 83.5          | 89.8       |
| 2018 | HCN                  | 86.5          | 91.1       |
| 2018 | SR-TSL               | 84.8          | 92.4       |
| 2019 | AS-GCN               | 86.8          | 94.2       |
| 2019 | AGC-LSTM (Joint)     | 87.5          | 93.5       |
| 2019 | AGC-LSTM (Part)      | 87.5          | 93.8       |
| 2019 | AGC-LSTM(Joint&Part) | 89.2          | 95.0       |
