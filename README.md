# Natural Scene Memorability Dataset
©2020 IRC-JiaxinLu

The open dataset of the paper:

> Jiaxin Lu, Mai Xu, Ren Yang, Zulin Wang, "Understanding and Predicting the Memorability of Outdoor Natural Scenes", in IEEE Transactions on Image Processing (T-IP), 2020. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9025769). 

If our paper and dataset are useful for your research, please cite:
```
@article{lu2020understanding,
  title={Understanding and Predicting the Memorability of Outdoor Natural Scenes},
  author={Lu, Jiaxin and Xu, Mai and Yang, Ren and Wang, Zulin},
  journal={IEEE Transactions on Image Processing},
  volume={29},
  pages={4927--4941},
  year={2020},
  publisher={IEEE}
}
```

## LNSIM Dataset
LNSIM dataset is a large-scale outdoor natural scene image memorability database, containing 2,632 outdoor natural scene images with their ground truth memorability scores. All images are voted by several participants and the memorability scores of these images are obtained by the memory game mentioned in the paper. Moreover, hrs.mat includes the ground-truth memorability score corresponding to each image.

## How to use

Image_data: outdoor natural scene images.

Random_splits: the ground-truth memorability scores of natural scene images in our database. Since we intend to train and test models on the memorability scores rated by different subjects, we split the memorability scores of all subjects into two groups and calculate the average scores of each group. We randomly split the scores for 25 times. In each split, the average score of the first and second groups are in "subject_hrs1.mat" and "subject_hrs2.mat", respectively.

## Corresponding code
[The test Code](https://github.com/RenYang-home/Natural-Scene-Memorability) of the proposed approach is publicly released.

## Contact
If you find any bug of our codes or have any question, please do not hesitate to contact:

Jiaxin Lu (lu-jia-xin@163.com)

Ren Yang (r.yangchn@gmail.com)
