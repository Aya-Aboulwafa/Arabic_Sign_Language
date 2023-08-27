
# Table of Content
[Arabic sign language](#Arabic-sign-language)

[Our Dataset](#Our-Dataset)

[Dataset structure](#Dataset-structure)

[Libraries](#Libraries)

[YOLOv5 model](#YOLOv5-model)

[Mean Average Precision (mAP)](#Mean-Average-Precision-(mAP))

[Steps to train the model](#Steps-to-train-the-model)




# Arabic sign language

**The detection model for Arabic sign language (ArSL) is crucial for a number of reasons:**

The deaf and hard-of-hearing communities in Arabic-speaking nations can benefit from improved access to information, education, and communication.

![لغة-الاشارة-1024x837](https://github.com/Aya-Aboulwafa/Arabic_Sign_letters/assets/90108897/a01cdfe8-b591-4fd5-ad72-d423a90b818d)



# Our Dataset

**Dataset link:** https://www.kaggle.com/datasets/ammarsayedtaha/arabic-sign-language-dataset-2022

![image](https://github.com/Aya-Aboulwafa/Arabic_Sign_letters/assets/90108897/f2564e5b-c776-4d63-ba27-f55e32130ddb)

This dataset includes 14202 images of 32 letter signs, collected from 50 individuals with different backgrounds.

## Dataset structure

![image](https://github.com/Aya-Aboulwafa/Arabic_Sign_letters/assets/90108897/1a3a544a-1d93-481e-bc94-a12195fc79ee)

9955 image for train and 4247 image for test

## Libraries

![image](https://github.com/Aya-Aboulwafa/Arabic_Sign_letters/assets/90108897/41240d72-f4d6-4c26-a13c-8fd64ba6d639)

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## YOLOv5 model

**The YOLOv5 model** is part of the YOLO family and is notable for combining bounding box prediction and object classification. It is also the first YOLO model written in the PyTorch framework, making it lighter and easier to use.


## Mean Average Precision (mAP)

Mean Average Precision (mAP) is a metric for evaluating object detection models such as Fast R-CNN, YOLO, and Mask R-CNN.

It is calculated by taking the mean of Average Precision (AP) values calculated over recall values from 0 to 1.

![Confusion_matrix](https://github.com/Aya-Aboulwafa/Arabic_Sign_letters/assets/90108897/dce2500d-28f6-432e-a552-98fa6c9d4b91)


## Steps to train the model

- Install YOLOv5 dependencies.
- Download custom YOLOv5 object detection data.
- Write our YOLOv5 training configuration.
- Run YOLOv5 training.
- Evaluate YOLOv5 training data.
- Visualize YOLOv5 training data.
- Run YOLOv5 inference on test images.
- Export saved YOLOv5 weights for future inference.

