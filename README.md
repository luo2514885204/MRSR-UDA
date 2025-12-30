## Unsupervised Domain Adaptation for Hyperspectral Image Classification via Masked Robustness Learning and Class Structure Regularization
This is a code demo for the paper "Unsupervised Domain Adaptation for Hyperspectral Image Classification via Masked Robustness Learning and Class Structure Regularization"


## Requirements
CUDA = 12.4

Python = 3.7

Pytorch = 1.12.1

sklearn = 1.0.1

numpy = 1.21.5

cleanlab = 1.0

## dataset

You can download the hyperspectral datasets in mat format at: https://pan.baidu.com/s/14pqanFPK3JQhDIxrjzSn3g?pwd=l3wf, and move the files to `./datasets` folder.

An example dataset folder has the following structure:

```
datasets
├── Houston
│   ├── Houston13.mat
│   └── Houston13_7gt.mat
│   ├── Houston18.mat
│   └── Houston18_7gt.mat
├── YC
│   ├── ZY_YC_data147.mat
│   └── ZY_YC_gt7.mat
│   ├── GF_YC_data.mat
│   └── GF_YC_gt.mat
```

## Usage:
Take MRSR-UDA method on the YC dataset as an example: 
1. Open a terminal or put it into a pycharm project. 
2. Put the dataset into the correct path. 
3. Run ZY_YC-GF_YC.py.

