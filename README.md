# Unsupervised Selectivity Estimation by Integrating Gaussian Mixture Models and an Autoregressive Model
## Introduction
This repo contains the source code of EDBT 2022 paper, [IAM](https://openproceedings.org/2022/conf/edbt/paper-65.pdf).

IAM first uses Gaussian Mixture Models to learn the distribution of continuous attributes and reduce their domain sizes. Then feeds the reduced data with new attributes to an autoregressive model to learn the joint data distribution.
![text-1](https://github.com/mzz235711/IAM/blob/main/model.jpg "") | ![text-2](https://github.com/mzz235711/IAM/blob/main/mm.jpg "")
|:---:|:---:|
Overview of IAM|Architecture of a Gaussian Mixture Model

## Citation
If you find this work helpful, please cite [our paper](https://openproceedings.org/2022/conf/edbt/paper-65.pdf):
```latex
@inproceedings{DBLP:conf/edbt/MengWCZ022,
  author    = {Zizhong Meng and
               Peizhi Wu and
               Gao Cong and
               Rong Zhu and
               Shuai Ma},
  title     = {Unsupervised Selectivity Estimation by Integrating Gaussian Mixture
               Models and an Autoregressive Model},
  booktitle = {Proceedings of the 25th International Conference on Extending Database
               Technology},
  pages     = {2:247--2:259},
  year      = {2022},
}
```

## Acknowledgement
The source code is developed based on [Neurocard](https://github.com/neurocard/neurocard). Thanks to the contributors of Neurocard.
