In this project we were provided 30 images for 15 different animals. Unlike where we get many images, here not only we get 30 images only, but many of these images are augmented images themselves. This presents a unique problem where we have very low number of images in training while most of the standard CNN architectures need huge amount images to train.

In order to handle this situation we will first adjust VGG architecture by removing a bit of complexity so that our training images could be trained properly. But while it improved in performance compared to the full VGG-19 architecture, validation accuracy was only 78%, which is acceptable for such a small dataset but we could do better with transfer learning.

This project is divided into three parts:
1. Data Preparation
2. VGG Based Model Training and Analysis
3. InceptionV3 Model Training and Analysis
4. Conclustion
