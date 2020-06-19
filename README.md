SNU GCN Class, Final Report. 2019-21762 Daeho Um.

Hyper graph Neural Networks.
Yifan Feng et al. AAAI 2019.


    @article{feng2018hypergraph,
      title={Hypergraph Neural Networks},
      author={Feng, Yifan and You, Haoxuan and Zhang, Zizhao and Ji, Rongrong and Gao, Yue},
      journal={AAAI 2019},
      year={2018}
    }

### Installation
- install Pytorch 0.4.0 and yaml.
- The code has been tested with Python 3.6, Pytorch 0.4.0 and CUDA 10.1 on Ubuntu 16.04.

### Usage
- configure the “data_root” and “result_root” path in config/config.yaml.
- Download ModelNet40_mvcnn_gvcnn_feature, NTU2012_mvcnn_gvcnn_feature and move them to data folder.
- python train.py
