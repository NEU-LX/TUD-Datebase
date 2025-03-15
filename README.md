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

All images have been resized to 512x512. The segmentation label is within the range of [0, 1], not [0, 255].
DDIT has 391 images for training and 261 images for testing. TUD has 614 images for training and 410 images for testing.

To reduce data bias, it is recommended that users perform K-fold cross validation on the data.

The data can be obtained from here: 
link：https://pan.baidu.com/s/1AfmVMjZvhcj_9yGkTrsgiA?pwd=qwer 
code：qwer


@article{li2024thyroid,
  title={Thyroid Ultrasound Image Database and Marker Mask Inpainting Method for Research and Development},
  author={Li, Xiang and Fu, Chong and Xu, Sen and Sham, Chiu-Wing},
  journal={Ultrasound in Medicine \& Biology},
  volume={50},
  number={4},
  pages={509--519},
  year={2024},
  publisher={Elsevier}
}
