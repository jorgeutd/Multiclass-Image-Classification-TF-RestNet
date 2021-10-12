
# Multiclass-Image-Classification-TF-RestNet

## Project Description

This is a Transfer learning based approach to predict the class of an image (cat, dog or panda) by fine-tuning RestNet50 using Tensorflow/ Keras with multi GPU dsitributed training on the Zoo dataset.

This notebook is part of my deep learning DAAN 570 class, I used a AWS sagemaker instance for multi GPU runtime training and S3 for initial storage.


## Dataset shape

Images of dogs, cats and pandas

| Dogs | Cats | Pandas |
| :-------------: | :-------------:| 
| 1,000 | 1,000 | 1,000 |

## Sources:

* ResNet50 - Keras Applications are deep learning models that are made available alongside pre-trained weights: https://keras.io/api/applications/
* Classify ImageNet classes with ResNet50 : https://keras.io/api/applications/#classify-imagenet-classes-with-resnet50


## Resources

* Deep Learning for Computer Vision with Python by Dr. Adrian Rosebrock: https://www.pyimagesearch.com/deep-learning-computer-vision-python-book/