# AdaMatting
an unofficial pytorch implementation of ICCV 2019 paper "Disentangled Image Matting"  
this project is not finished

## Dependencies
+ python 3.6  
+ pytorch 1.4.0  
+ tensorboardX  
+ opencv  

## Datasets
### Adobe Composition-1k Dataset
[Contact author](https://sites.google.com/view/deepimagematting) for the dataset.  
### MSCOCO
[train2014.zip](http://images.cocodataset.org/zips/train2014.zip)  
### PASCAL VOC
[PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/):  
+ [VOCtrainval_14-Jul-2008.tar](http://host.robots.ox.ac.uk/pascal/VOC/voc2008/VOCtrainval_14-Jul-2008.tar)  
+ [VOC2008test.tar](http://host.robots.ox.ac.uk/pascal/VOC/voc2008/index.html)  

## Usage
### Composite the data
```bash
$ bash ./prep.sh
```
### Train
```bash
$ bash ./train.sh
```
### Test
TODO
