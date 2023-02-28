# Detected-12-different-rice-diseases

The major production problem confronting rice crops is pests. These diseases caused by bacteria, fungi and other organisms seriously affect crop health and cause important crop losses. The majority of these diseases can be identified during the whole growth stage by close observation of stems and leaves under the supervision of expert rice growers. However, with extensive crop production and few disease detection experts, manual identification of rice crops becomes very complicated. For this reason, to add a solution to this problem, it is necessary to automate the disease identification process, 
allowing to detect patterns that distinguish with higher probability such a rice field. In turn, provide decision-making tools to implement effective crop protection measures for timely control. So, there are several ways to classify images but the most widely used is convolutional neural networks (CNN)  to analyze images and identify specific patterns in them. This approach has been successfully used in the detection of diseases in rice crops, allowing faster and more accurate identification of diseases affecting the crop. This paper presents an improving image classification of rice crop dataset for identifying diseases. Dataset contains 16,225 annotated rice leaf images across 13 classes (12 diseases and normal leaf). We modified the structure and pre-training the CNN changing the transfer learning model, in this case, ResNet34 for ResNet50. The experimental results showed that ResNet50 achieved an accuracy of 97.99\%, surpassing the values obtained by the other transfer learnings (VGG16, MobileNet, Xception and ResNet34) used in the bechmark paper.

**Implentation**

Implementation of resnet 50 model to generate a model that detects different rice diseases by means of photos.

Originally, the paper on which we rely has two versions, a public dataset and a paid dataset, the public dataset is a short version of the original dataset, which can be found at the following link:

https://www.kaggle.com/competitions/paddy-disease-classification/data

However, if you have access to IEEEDataport, you can find the original dataset at the following link:

https://ieee-dataport.org/documents/paddy-doctor-visual-image-dataset-automated-paddy-disease-classification-and-benchmarking

Now, in order to replicate our model, initially there is an .ipynb file in which each part implemented in our model is mentioned, in order to replicate the results.

**Reproduce our results**

1. Import and load the dataset.
2. Split the data into train and test.
3. Setlup a learner model based on resnet50.
4. Fine-tune the resnet50 model.
5. Model predictions, with the test data.
6. Finally, plot the results.

