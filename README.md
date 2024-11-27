# Cell Segmentation in QMIF Data by Fine-tuning a Stardist2D Model

get the original stardist package here: [StarDist GitHub Repository](https://github.com/stardist/stardist)

## Labeling for training image
Used Fiji LABKIT plugin to annotate manually 50 images for cell boundary segmentation.
![Segmentation Example](images/gt_pred.png)

## Prediction after training 
Prediction after 32 rays model 
![Segmentation Example](images/pred.png)

## Results from training
Results from a 16 ray model 
![Segmentation Example](images/results_from_training.png)
