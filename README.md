# BUILDING_DETECTION

Building detection for gis department using Keras framework


Data Source: https://drive.google.com/open?id=1sfGXpdCHMQAqlWDYvnbPJi8zWqK144TU
 
![unet]("https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/u-net-architecture.png")

### Due to limited computational power trained  with around 177 images.

### Adopted unet as a basic architecture

### image size of 128 x 128 choosen

### Tried with mainly 2 types of architectures:
      1. basic unet + data augemnetation
      2. unet + resnet + data augmentation
      
### Used Dice coefficient and mean iou as metric
### Got better result with simple unet architecture 

### Got results as loss: 0.0502 - dice_coef: 0.9490 - mean_iou: 0.7812 - val_loss: 0.2488 - val_dice_coef: 0.7905 - val_mean_iou: 0.7818

### Results can be further improved with more images and better computational power

Some reaserch pappers followed:
Unet: https://arxiv.org/abs/1505.04597
Deep Residual U-Net: https://arxiv.org/abs/1711.10684





