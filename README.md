# TUD-Datebase  and DDTI-Datebase

ThyroidDatasets  are used for thyroid nodule segmentation, including DDTI an TUD. 

The structure is as follows:

ThyroidDatasets
├── DDTI
│   ├── images
│   │   ├── training
│   │   ├── test
│   ├── annotations
│   │   ├── training
│   │   ├── test
├── TUD
│   ├── images
│   │   ├── training
│   │   ├── test
│   ├── annotations
│   │   ├── training
│   │   ├── test
│   ├── normal_thyroid

All images have been resized to 512x512. The segmentation label is within the range of [0,1], not [0255].
DDIT has 391 images for training and 261 images for testing. TUD has 614 images for training and 410 images for testing.

The dataset can be obtained from here:
链接：https://pan.baidu.com/s/1bM88wsmFTPs8aOGeTE5rSg?pwd=qwer 
提取码：qwer
