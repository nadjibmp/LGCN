# Large-Scale Learnable Graph Convolutional Networks (KDD18)

Created by [Hongyang Gao](http://eecs.wsu.edu/~hgao/), [Zhengyang Wang](http://www.eecs.wsu.edu/~zwang6/) and [Shuiwang Ji](http://www.eecs.wsu.edu/~sji/) at Washington State University.

## Introduction

Large-Scale Learnable Graph Convolutional Networks provide an efficient way (LGCL and LGCN) for learnable graph convolution.

Detailed information about LGCL and LGCN is provided in (https://dl.acm.org/citation.cfm?id=3219947).

## Citation

If using this code, please cite our paper.

```
@inproceedings{gao2018large,
  title={Large-Scale Learnable Graph Convolutional Networks},
  author={Gao, Hongyang and Wang, Zhengyang and Ji, Shuiwang},
  booktitle={Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining},
  pages={1416--1424},
  year={2018},
  organization={ACM}
}
```

## Start training

After configure the network, we can start to train. Run
```
python main.py
```
The training results on Cora dataset will be displayed.
