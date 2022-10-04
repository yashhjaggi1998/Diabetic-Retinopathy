# Diabetic-Retinopathy

This is a project to detect diabetes using the retinal images of human eye. This software is particularly useful for 2 reasons:
1. Helps detect the disease early and hence provides the patient with an opportunity to prevent loss of vision.
2. It is a painless process to detect the level of diabetes that a patient has.

The dataset used for this project has been accumulate from public sources and a few hospitals from Pune, India. Here, we have made certan changes in the popular models of Convolutional Networks.

We have used Alexnet and DenseNet models and made proprietory changes to these CNN models in order to improve the accuracy on our dataset. We have achieved an accuracy of 87%. The data cleaning process has been particularly challenging and we have automated the process to augment images as we had very few retinal images of level 5 diabetes. To augment images we have written a custom code and ran the process on GPU to speed up the augmentation.
