# Case-Study-Image-Classification-using-Transfer-Learning
A study of different pre-trained deep learning models and their tuning approaches on a Brain Tumour MRI Image Dataset. 

Dataset Source: https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri

# Tasks Completed:

1) Image pre-processing and visualization of the labels.

2) Data Augmentation

3) Model developed with 4 different pre-trained models
  1.1 MobileNet
  1.2 Xception
  1.3 EfficientNetB0
  1.4 EfficientNetB1
  
4) Analysis of the accuaracy of the train and test.

5) Fine tuning

# Approaches of handling the overfitting:

1. Introduce regularisation using lambda
2. Vary the learning rate of the optimizer
3. Add dropout/batchnormalization layer
4. Use call backs like Early Stopping, Model Check point, ReduceLRon Plateau etc.
5. Try different augmentaion options. It increases the generic behaviour.

 # Conclusion:
 
 EfficientNetB0 with calllbacks and dropout has given the best performance >90% accuracy on both train and test.
 
 ![image](https://user-images.githubusercontent.com/70081663/121815275-3b2d1080-cc93-11eb-99a2-a9a946db49f1.png)

