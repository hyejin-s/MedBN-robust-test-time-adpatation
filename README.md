# MedBN-robust-test-time-adpatation
[CVPR 2024] Official implementation of "MedBN: Robust Test Time Adaptation against Malicious Test Samples"


## Requirements

## Datasets

## Usage

Examples for running code for CIFAR10-C
```
python test_attack.py --cfg ./cfgs/cifar10/[method].yaml \
MODEL.ARCH resnet26 MODEL.NORM [bn/med] ATTACK.STEPS 100 ATTACK.SOURCE 40 
```


If you have any questions, please contact Hyejin Park by [parkebbi2@gmail.com]


## Citation
If our MedBN method are helpful in your research, please consider citing our paper:
```
here
```


## Acknowledgement
The code is inspired by [DIA](https://github.com/inspire-group/tta_risk), [TENT](https://github.com/DequanWang/tent), [EATA](https://github.com/mr-eggplant/EATA), [SAR](https://github.com/mr-eggplant/SAR/tree/main), and [SoTTA](https://github.com/taeckyung/SoTTA).
