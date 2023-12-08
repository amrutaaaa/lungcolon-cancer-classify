# lungcolon-cancer-classify

Overview
This repository contains the code and documentation for a medical image classification project aimed at identifying different types of tumors in lung and colon tissues. The project uses Convolutional Neural Networks (CNNs) and explores various models, including a basic CNN, transfer learning models (MobileNet, VGG19, ResNet50), and a paper implementation of AlexNet. The final model is an ensemble of a binary classifier and AlexNet, achieving competitive results in terms of accuracy and recall

Results
Best Model:

Ensemble model with a binary classifier for 'lung_scc' and AlexNet achieves an accuracy of 98.54% and recall of 98.54%.
Comparison with Paper:

Our best model outperforms the paper's model in most classes, even without using test labels for preprocessing.
