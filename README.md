# Simple_fcn
fixed a problem for original code (RandomCrop)
### main code heavliy reference this blog [https://zhuanlan.zhihu.com/p/32506912]
### the dataset for solve the data transform problem reference [https://github.com/pochih/FCN-pytorch/blob/master/python/Cityscapes_loader.py]
## Installtion
```bash
pytorch>=1.0 should be fine
os
time
PIL
matplotlib
opencv-python
```
## dataset perpare
```
G:.
├─.ipynb_checkpoints
└─VOCdevkit
    └─VOC2012
        ├─Annotations
        ├─ImageSets
        │  ├─Action
        │  ├─Layout
        │  ├─Main
        │  └─Segmentation
        ├─JPEGImages
        ├─SegmentationClass
        └─SegmentationObject
└─Simple_fcn.ipynb
```

## How to train
follow above you just clik the ""run all"" button ,will be fine!

## Training log and MIOU

| Epoch | Train Loss | Train Acc | Train Mean IU | Valid Loss | Valid Acc | Valid Mean IU |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 108 | 0.07536 | 0.97046 | 0.83511 | 0.46642 | 0.89280 | 0.55141 |

i havn't much time train more params for the model
##### Device
**GTX 1080Ti**

## To do:
  * [ ] convert original caffe params
  * [ ] use backbone VGG
  * [ ] add Densenet 

## Result of my training log please view the simple_fcn.html
#### any questions are welcome!(open a issue)
