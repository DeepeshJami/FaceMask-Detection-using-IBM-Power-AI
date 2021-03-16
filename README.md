# FaceMask-Detection-using-IBM-Power-AI
 
Trained weights file (password: s7ph), 40,000 generation results (training on GTX 1080Ti for 1000 generations takes about 30 minutes)

### Rely

yolo v2, recommended for cross-windows and linux versions 

Training data volume: 4045 Test data volume: 405 evaluation 
result:rely yolo v2, recommended for cross-windows and linux versions 
Training data volume: 4045 Test data volume: 405 evaluation result:

## Implementation
```
git clone https://github.com/AlexeyAB/darknet
vim Makefile

GPU=1
CUDNN=1
OPENCV=1

make -j8

```

Remember to download the local path as DARKNET_ROOT, put this project under DARKNET_ROOT

### Training
```
sh train.sh
```

### Testing a Single Image
```
sh test.sh
```
### Evaluation of test set
```
sh evaluate.sh
```
