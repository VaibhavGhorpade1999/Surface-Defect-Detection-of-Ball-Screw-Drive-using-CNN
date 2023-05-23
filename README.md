# Surface-Defect-Detection-Ball-Screw-Drive-using-CNN
## Abstract:
- The dataset contains of 21835 150x150 Pixel RGB images of the surface of Ball Screw Drives. 
- 11075 of these images are images without surface defects whereas the rest shows images with surface defects in form of so called pittings. 
- So the dataset is evenly split over the classes. Pittings result from surface disruption and can ultimately lead to the breakdown of the component. 
- To keep the availability of machines high it is important to find surface defects in time. 
- The here presented dataset gives researchers and practitioners the possibility to train and test models for the classification of surface defects on machine tool elements.

## Description:
- Images in "N" folder are images without defect whereas images with "P" folder are images showing Pittings.

## Work Done:
- The development process involves several key steps. First, the dataset is preprocessed to ensure uniformity and improve the model's training efficiency. This includes resizing, normalization, and augmentation techniques to increase the dataset size and address any class imbalance issues.
- Next, the VGG19 model is loaded and adapted for transfer learning. The pre-trained layers are frozen to preserve the learned features, while a custom classification head is added to the network. The weights of the added layers are then trained on the ball screw drive defect dataset using techniques such as backpropagation and gradient descent.
- To evaluate the performance of the trained model, a comprehensive set of metrics is employed, including accuracy, precision, recall, and F1 score. 

## Result:

| Metric    | Value     |
|-----------|-----------|
| Accuracy  | 97.2%     |
| Precision | 96.9574%  |
| Recall    | 97.3523%  |
| F1 ratio  | 97.1544%  |


## Data Source:
- [KITOpenData](https://bwdatadiss.kit.edu/dataset/323#headingFileList)
