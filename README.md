# On Evaluating Physical Backdoor Attacks to Camera and LiDAR Perception in Autonomous Vehicles.


## Introduction
In this work, we provide three levels of backdoor attack evaluation for perception of Autonomous Driving (AD):
+ Dataset simulation;
+ LGSVL, a production-grade autonoumos driving simulator;
+ Physical autonomous vehicles: UGV and Baidu Apollo;

We target three foundamental functions in AD systems including obstacle detection, lane detection and traffic light detection, to reveal severe security threat to Autonomous Vehicles (AV). 

## Installation
First, create a conda virtual environment and activate it:
```
conda create -n avba python=3.8 -y
conda activate avba
```
Then, clone this directory and install other packages:
```
git clone git@github.com:avsecurity123/BA_ADS_Evaluation.git
cd BA_ADS_Evaluation
pip install -r requirements.txt
```

## Train a new model
### Data preparation

## Well-trained backdoor models and poisoned datasets
Please download the models and poisoned datasets in Drive:
[Models and Datasets](https://entuedu-my.sharepoint.com/:f:/g/personal/xingshuo001_e_ntu_edu_sg/EpOauaxGG1pNjegCv-NyFzYBa3lpIMFJPHKdegJsx7dzCg?e=4xC13J)
## Datasets simulation

Follow the steps to pre-process: 
[kitti](http://www.cvlibs.net/datasets/kitti/)

## LGSVL simulator

## Physical evaluation with AVs.

## BibTex
If you find avba useful in your research, please use the following BibTeX entry for citation.
```BibTeX


```
