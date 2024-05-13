# Emotion Detection Using Facial Expression Models

## Model 1: Custom ResNet-18 (FacialRecog.ipynb)
This is a slightly modified version of the baseline model provided in the reference repo. 
- This attained an accuracy of around 63%. 

## Model 2: Custom ResNet-50 (Resnet.ipynb)
This is our own custom ResNet-50 model inspired by the custom ResNet-18, where we trained using Adam, added regularizers and a plateaued learning rate scheduler. 
- This attained an accuracy of around 65%.

## Model 3: Pretrained ResNet-50 (PretrainedResnet.ipynb)
This uses keras' pretrained ResNet-50 model with the grayscale images transformed to RGB images, with the plateaued learning rate scheduler. 
- This attained an accuracy of around 60%.

## Model 4: Pretrained VGG-16 (VGGFacialRecog.ipynb)
This uses keras' pretrained VGG-16 model with the grayscale images transformed to RGB images.
- This attained an accuracy of around 67%.

## Model 5: Pretrained MobileNet (MobileNetFacialRecog.ipynb)
This uses keras' pretrained MobileNet model with the grayscale images transformed to RGB images.
- This attained an accuracy of around 55%.


