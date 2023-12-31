# NAS GAN
This repository is a Course project for the course: "Deep Learning for Visual Recognition" at Aarhus University. 

In this project, our goal has been to create a model, that is able to transform a synthetic image to a real looking images.
To achieve this, we took inspiration from [CycleGAN](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) and aimed to enhance it further by incorporating Neural Architecture Search.
---
The infrastucture of the code has been taken from https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix, where we added our contributions in.
---
To download the dataset:
```
cd ./data
wget http://csr.bu.edu/ftp/visda17/clf/train.tar
tar xvf train.tar

wget http://csr.bu.edu/ftp/visda17/clf/validation.tar
tar xvf validation.tar  

wget http://csr.bu.edu/ftp/visda17/clf/test.tar
tar xvf test.tar

wget https://raw.githubusercontent.com/VisionLearningGroup/taskcv-2017-public/master/classification/data/image_list.txt
```
---

## Colab Notebook
is present in the Repo: [NAS_GAN.ipynb](https://github.com/PhilippHa3/NAS_GAN_AU/blob/main/NAS_GAN.ipynb)