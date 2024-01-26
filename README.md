# Image_Classification_Using_Vision_Transformer
The "An Image is Worth 16x16 Words" paper highlights the power and versatility of the Vision Transformer (ViT) model. By applying the attention mechanisms of the Transformer architecture to image data, the ViT has opened up new possibilities for leveraging self-attention and capturing complex image patterns, challenging the dominance of conventional CNN-based approaches in computer vision.

While the Transformer architecture has become the de-facto standard for natural language processing tasks, its applications to computer vision remain limited. In vision, attention is either applied in conjunction with convolutional networks, or used to replace certain components of convolutional networks while keeping their overall structure in place. The paper shows that this reliance on CNNs is not necessary and a pure transformer applied directly to sequences of image patches can perform very well on image classification tasks. When pre-trained on large amounts of data and transferred to multiple mid-sized or small image recognition benchmarks (ImageNet, CIFAR-100, VTAB, etc.), Vision Transformer (ViT) attains excellent results compared to state-of-the-art convolutional networks while requiring substantially fewer computational resources to train.


![ViT](https://github.com/quinbez/Image_Classification_Using_Vision_Transformer/assets/109418929/863da2f8-3c37-4681-a29e-4915b5fd8c06)

This repository contains the an end-to-end project for an image classification model. The goal is to train a model that can accurately classify input flower images into different classes. It utilizes the Vision Transformer (ViT) architecture, which has shown promising results in image classification tasks.

### Features
* Preprocessing to prepare the dataset for training.
* Patch Extraction.
* Class Tokens and Positional Embeddings.
* Creating layers used in Transformer's encoder.
* Implementation of the Vision Transformer (ViT) model.
* Training the model on the dataset.
* Evaluating the trained model's performance.
* Pretrained weights for the ViT model.

### Dataset
The project uses the Kaggle Flower Classification dataset, a collection of images depicting various types of flowers. The dataset consists of images classified into 5 different flower classes. It is split into training and test sets for model development and evaluation.

git clone https://github.com/quinbez/Image_Classification_Using_Vision_Transformer
