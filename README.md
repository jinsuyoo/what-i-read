# What I Read

## 2021

### February

#### About Face SR

[AAAI 2020] Joint Super-Resolution and Alignment of Tiny Faces, Yin et al. \
[paper](https://arxiv.org/pdf/1911.08566.pdf) | [code](https://github.com/YuYin1/JASRNet)
- Jointly train sr network and facial landmark detection network. (multi-task learning: face sr + face alignment)
- Two tasks share encoder and separate decoder.

#### About Graph Neural Network

[IJCAI 2020] G2RL: Geometry-Guided Representation Learning for Facial Action Unit Intensity Estimation, Fan and Lin \
[paper](https://www.ijcai.org/Proceedings/2020/0102.pdf)
- Incorporated additional facial landmark detection to facial AU intensity estimation task.
- Exploited GCN for facial landmark detection. (constructed graph using single frame.)
- Nodes: 2D coordinates of the landmarks.
- Adjacency matrix: Euclidean distances between the nodes.

### January

#### About Graph Neural Network

[ICLR 2017] Semi-Supervised Classification with Graph Convolutional Networks, Kipf and Welling \
[paper](https://openreview.net/pdf?id=SJU4ayYgl) | [blog](http://tkipf.github.io/graph-convolutional-networks/)
- Introduced convolution operation on a graph structure. 
- Achieved two key properties of the CNNs (1) weight sharing and (2) local connectivity on a graph.
- Enables to stack DEEP convolutional layers for GNN.

[ECCV 2018] Videos as Space-Time Region Graphs, Wang and Gupta \
[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaolong_Wang_Videos_as_Space-Time_ECCV_2018_paper.pdf)
- Represented (ojects in the) videos as spatial-temporal graph.
- Used GCN for reasoning among the nodes.

[AAAI 2018] Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition, Yan et al. \
[paper](https://arxiv.org/pdf/1801.07455.pdf) | [code](https://github.com/open-mmlab/mmskeleton)

[CVPR 2020] Spatial-Temporal Graph Convolutional Network for Video-based
Person Re-identification, Yang et al. \
[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Spatial-Temporal_Graph_Convolutional_Network_for_Video-Based_Person_Re-Identification_CVPR_2020_paper.pdf)