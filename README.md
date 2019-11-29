# Deep Regression Tracking with Shrinkage Loss

### Introduction

This is the research code for the ECCV 2018 paper: 

:tada:

Pytorch version is release:
Requirement
--
Python 2.7 (I use Anaconda 2.* here. If you use Python3, you may get the very different results!)
Python-opencv
PyTorch 0.40
other common packages such as numpy, etc

--

##Data curation


[Xiankai Lu](https://github.com/carrierlxk),  [Chao Ma](https://sites.google.com/site/chaoma99/), [Bingbing Ni](https://scholar.google.com/citations?user=eUbmKwYAAAAJ&hl=en), [Xiaokang Yang](http://english.seiee.sjtu.edu.cn/english/detail/842_802.htm), [Ian Reid](https://cs.adelaide.edu.au/~ianr/), and [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/), " Deep Regression Tracking with Shrinkage Loss", ECCV 2018. 

![](../master/images/framework.png)

The pipeline is built upon the FCNT tracker and CRT paper (CRT: Convolutional Regression for Visual Tracking) 
https://github.com/scott89/FCNT
### Abstract
Regression trackers directly learn a mapping from regularly dense samples of target objects to soft labels, which are usually generated by a Gaussian function, to estimate target positions. Due to the potential for fast-tracking and easy implementation, regression trackers have received increasing attention recently. However, state-of-the-art deep regression trackers do not perform as well as discriminative correlation filters (DCFs) trackers. We identify the main bottleneck of training regression networks as extreme foreground-background data imbalance. To balance training data, we propose a novel shrinkage loss to penalize the importance of easy training data.  Additionally, we apply residual connections to fuse multiple convolutional layers as well as their output response maps. Without bells and whistles, the proposed deep regression tracking method performs favorably against state-of-the-art trackers, especially in comparison with DCFs trackers, on five benchmark datasets including OTB-2013, OTB-2015, Temple-128, UAV-123 and VOT-2016.


### Results
The tracking results can be download [here](https://github.com/chaoma99/DSLT).
If you find the code useful, please cite
## citation
@inproceedings{lu2018deep,

  title={Deep Regression Tracking with Shrinkage Loss},
  
  author={Lu, Xiankai and Ma, Chao and Ni, Bingbing and Yang, Xiaokang and Reid, Ian and Yang, Ming-Hsuan},
  
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  
  pages={353--369},
  
  year={2018}
}


