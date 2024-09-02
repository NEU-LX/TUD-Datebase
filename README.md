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
DDIT has 391 images for training and 261 images for testing. TUD has 614 images for training and 410 images for testing. There are also 53 normal thyroid images in TUD.

The datasets can be obtained from here:
链接：https://pan.baidu.com/s/1o5n2QlntTqfkuO-eh6bBDw?pwd=qwer 
提取码：qwer
