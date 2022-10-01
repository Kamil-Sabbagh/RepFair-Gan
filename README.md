# RepFair-Gan

First install the data set:
```
gdown 1fUutrowiOMg67XzpTNYiRc75pbPIG_9N
```
then we need to unzip the data:
```
unzip fairface-img-margin025-trainval.zip
```
Then we need to setup the dataset:
```
mkdir dataset
mv train dataset/train
```
Then we need to make sure that the GPU is fully configured, [check the tutorial](https://www.tensorflow.org/install/pip)