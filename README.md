## Introduction

In this repository, you will find the source code of all the scripts developed for the experimental phase of the paper &quot;**Deep Transfer Learning for Banana Ripeness Classification**&quot;.

## Content
- **1. Image Preprocessing**

In this file, you will find the procedures carried out for the preprocessing of the images, which were: NLM Filter for Image Denoising and Rembg tool for background removal.

- **2. CNN without TL**

In this experiment, we used our own architecture to build the CNN, using an input shape of 224x224.

- **3. MobileNetV2 Pretrained Model**

For the second experiment, we used the pre-trained MobileNetV2 model, adding the classification layers to build the CNN, using a 224x224 input shape.

- **4. InceptionV3 Pretrained Model**

In the third experiment, we used the pre-trained InceptionV3 model, adding the classification layers to build the CNN, using a 299x299 input shape.

- **5. SqueezeNet Pretrained Model**

In the fourth experiment, we used the pre-trained SqueezeNet model, adding the classification layers to build the CNN, using a 227x227 input shape.

## Principal Libraries
- OpenCV
- Tensorflow
- Rembg
- Keras
