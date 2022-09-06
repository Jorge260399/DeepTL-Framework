## Introduction

In this repository, you will find the source code of all the scripts developed for the experimental phase of the paper &quot;**Deep Transfer Learning for Banana Ripeness Classification**&quot;.

## Content
- **1. Image Preprocessing**

In this file, you will find the procedures carried out for the preprocessing of the images, which were: NLM Filter for Image Denoising and Rembg tool for background removal.

- **2. CNN without TL**

In this experiment, the concatenated color and textural features obtained from the images above were used. These features were employed to feed the models that implemented the Multiclass SVM techniques based on OVO classification (VBMSVM, DAGMSVM) and Random Forest.

- **3. MobileNetV2 Pretrained Model**

For the second experiment, the concatenated color and textural features were used, applying the PCA dimensionality reduction technique. The methods that were implemented in this experiment are Multiclass SVM based on OVO classification (VBMSVM, DAGMSVM) and Random Forest.

- **4. InceptionV3 Pretrained Model**

In the third experiment, the implementation of the CNN-based TL deep learning technique was performed.

- **5. SqueezeNet Pretrained Model**

In the third experiment, the implementation of the CNN-based TL deep learning technique was performed.

## Principal Libraries
- OpenCV
- Tensorflow
- Rembg
- Keras
