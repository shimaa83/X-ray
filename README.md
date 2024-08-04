# using deep learning to classify x-ray image
# steps:

1. Import Libraries
2. EDA
3. create dataset
4. images preprocess and use class weight to solve imbalance problem
5. Training the Model
6. Compute Accuracy
7. Making Predictions
8. Conclusion
# we try several model :
1. first model: simple deep learning model 
 :: Accuracy: 0.78 -  Recall: 0.72  - F1 Score: 0.73
2. second model we did some fine tuning by adding drop out layer:
::Accuracy: 0.73  -   Recall: 0.64  - F1 Score: 0.64
3. third model anther fine tuning by adding dense layer:
 ::Accuracy: 0.74 - Recall: 0.66 - F1 Score: 0.65
4. anther pretrained model vgg19
::Accuracy: 0.78  - Recall: 0.70 -F1 Score: 0.72
5. then we try pretrained model vgg16
 ::Accuracy: 0.79   -    Recall: 0.72  - F1 Score: 0.73
 # the highest accuracy and f1score is vgg16 so we use this model in reference
