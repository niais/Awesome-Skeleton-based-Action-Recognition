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
  - [ ] more papers published before 2016
- [ ] Leaderboard
  - [x] NTU RGB+D
  - [ ] NTU RGB+D 120
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
    - [NTU-RGB+D 120](#ntu-rgbd-120)

## Misc

- Microsoft Kinect sensor and its effect (**IEEE Multimedia 2012**)
  
## Datasets

- *(New! 2019)* **NTU RGB+D 120 Dataset** [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp),[Github](https://github.com/shahroudy/NTURGB-D)]
- NTU RGB+D Dataset [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp),[Github](https://github.com/shahroudy/NTURGB-D)]
- *(New! 2018)* VARYING-VIEW RGB-D ACTION DATASET [[arxiv](https://arxiv.org/pdf/1904.10681.pdf)]
- (2017) SYSU 3D Human-Object Interaction Dataset (**SYSU**)
- (2015) UWA3D Multiview Activity II Dataset (**UWA3D**)
- (2014) Northwestern-UCLA Dataset (**N-UCLA**)
<!-- - SBU Kinect Interaction Dataset (**SBU**) -->

This section only shows some popular or new datasets, other available datasets for 3D action recognition and their statistics can be found in the following Table from the journal paper of **NTU RGB+D 120 Dataset** ([TPAMI](https://arxiv.org/pdf/1905.04757.pdf)).
![datasets](./datasets.jpg)

## Papers

### arXiv papers

This section only includes the last five papers since 2018 in [arXiv.org](arXiv.org). Note that arXiv papers **without available codes** are not included in [the leaderboard of performance](#LeaderBoard).

- Semantics-Guided Neural Networks for Efficient Skeleton-Based Human Action Recognition [[arxiv](https://arxiv.org/pdf/1904.01189.pdf)]
- Optimized Skeleton-based Action Recognition via Sparsified Graph Regression [[arxiv](https://arxiv.org/pdf/1811.12013.pdf)]
- Skeleton-Based Action Recognition with Synchronous Local and Non-local Spatio-temporal Learning and Frequency Attention [[arxiv](https://arxiv.org/pdf/1811.04237.pdf)]
- Skeleton-based Activity Recognition with Local Order Preserving Match of Linear Patches [[arxiv](https://arxiv.org/pdf/1811.00256.pdf)]
- Graph Edge Convolutional Neural Networks for Skeleton Based Action Recognition [[arxiv](https://arxiv.org/pdf/1805.06184.pdf)]
<!-- ### Survey -->

### 2019

- NTU-RGB+D 120: A Large-Scale Benchmark for 3D Human Activity Understanding (***TPAMI 2019***) [[arxiv](https://arxiv.org/pdf/1905.04757.pdf)] [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp)] [[Github](https://github.com/shahroudy/NTURGB-D)]
- **[AS-GCN]**] Actional-Structural Graph Convolutional Networks for Skeleton-based Action Recognition (**CVPR2019**)
- **[AGC-LSTM]** An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition (**CVPR2019**)

### 2018

- Beyond Joints: Learning Representations from Primitive Geometries for Skeleton-based Action Recognition and Detection (***TIP 2018***) [paper] [[code](https://github.com/hongsong-wang/Beyond-Joints)]
- **[DPRL]** Deep progressive reinforcement learning for skeleton-based action recognition (**CVPR 2018**)
- **[SR-TSL]** Skeleton based action recognition with spatial reasoning and temporal stack learning (**ECCV 2018**)
- **[HCN]** Co-occurrence feature learning from skeleton data for action recognition and detection with hierarchical aggregation (**IJCAI 2018**) [[Reimplementation](https://github.com/huguyuehuhu/HCN-pytorch)]
- Memory attention networks for skeleton-based action recognition (**IJCAI 2018**)
- **[ST-GCN]** Spatial temporal graph convolutional networks for skeleton-based action recognition (**AAAI 2018**) [[code](https://github.com/yysijie/st-gcn)]
- Spatio-temporal graph convolution for skeleton based action recognition (**AAAI 2018**)
- Part-based Graph Convolutional Network for Action Recognition (**BMVC 2018**)
- A Fine-to-Coarse Convolutional Neural Network for 3D Human Action Recognition (**BMVC 2018**)
- A Large-scale Varying-view RGB-D Action Dataset for Arbitrary-view Human Action Recognition (**ACMMM 2018**) [[arxiv](https://arxiv.org/pdf/1904.10681.pdf)]
  
### 2017

- Jointly learning heterogeneous features for RGB-D activity recognition (***TPAMI 2017***)
- **[Visualization CNN]** Enhanced skeleton visualization for view invariant human action recognition (***Pattern Recognition 2017***)
- Global context-aware attention lstm networks for 3d action recognition (**CVPR 2017**)
- **[Two-stream RNN]** Modeling temporal dynamics and spatial configurations of actions using two-stream recurrent neural networks (**CVPR 2017**)
- **[C-CNN + MTLN]** A new representation of skeleton sequences for 3d action recognition (**CVPR 2017**)
- **[Temporal Conv]** Interpretable 3d human action analysis with temporal convolutional networks (**CVPR 2017**)
- **[Ensemble TS-LSTM]** Ensemble deep learning for skeleton-based action recognition using temporal sliding lstm networks (**ICCV 2017**)
- **[VA-LSTM]** View adaptive recurrent neural networks for high performance human action recognition from skeleton data (**ICCV 2017**)
- Learning action recognition model from depth and skeleton videos (**ICCV 2017**)
- **[STA-LSTM]** An end-to-end spatio-temporal attention model for human action recognition from skeleton data (**AAAI 2017**)
- Skeleton-based action recognition using LSTM and CNN (*ICME Workshop 2017*)
- Skeleton-based action recognition with convolutional neural networks (*ICME Workshop 2017*)
- PKU-MMD: A large scale benchmark for continuous multi-modal human action understanding (*ACMMM Workshop 2017*)
- Interpretable 3d human action analysis with temporal convolutional networks (*CVPR Workshop 2017*)
  
### 2016

- **[Trust Gate ST-LSTM]** Spatio-temporal lstm with trust gates for 3d human action recognition (**ECCV 2016**)
- **[Part-aware LSTM]** NTU RGB+D: A Large Scale Dataset for 3D Human Activity Analysis (**CVPR 2016**) [[paper](https://)]
- Rolling rotations for recognizing human actions from 3d skeletal data (**CVPR 2016**)
- Co-occurrence feature learning for skeleton based action recognition using regularized deep lstm networks (**AAAI 2016**)

### 2015

- Skeleton based action recognition with convolutional neural network (**ACPR 2015**)
- **[H-RNN]** Hierarchical recurrent neural network for skeleton based action recognition (**CVPR 2015**)
- Jointly learning heterogeneous features for rgb-d activity recognition (**CVPR 2015**)
  
### before 2015

- [**LieGroup**] Human action recognition by representing 3d skeletons as points in a lie group (**CVPR 2014**)
- Human action recognition using a temporal hierarchy of covariance
descriptors on 3d joint locations (**IJCAI 2013**)

## LeaderBoard

The section is being continually updated. Note that some values have a superscript, which indicates their source. We only show results on large-scale dataset NTU-RGB+D and NTU-RGB+D 120.

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
| 2019 | AGC-LSTM (Joint&Part)| **89.2**      | **95.0**   |

### NTU-RGB+D 120

Existing methods have not been tested on this new dataset yet.
