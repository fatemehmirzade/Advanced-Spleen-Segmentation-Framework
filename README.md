# Unet-model-for-spleen-segmentation

## Introduction
The project is based on ultrasound imaging data for patient spleens and seeks to develop an algorithm for region of spleen segmentation, identify the regions, and localize them within the images in an accurate manner. In addition, spleen dimension avails different quantitative measurements that can be used as an adjunct to diagnostic stools in looking at pathologic conditions like infections.

## Data Preparation
Ultrasound Imaging Data
The data of the ultrasound imaging from patients' spleens is used for the development and training of the segmentation algorithms.
Steps in Data preprocessing are:
Ultrasounds images will be normalized.
Increases in variability and robustness in the data set.
Now, split the data into a training set, a validation set, and a test set.
Hyperparameters and Training
U-Net Architecture
The Unet network architecture was chosen as the base for the design of the computational framework because it has already shown good performance in the field of medical image analysis, mainly for tasks that involve high-fidelity delineation of anatomical structures. The Unet model follows an encoder/decoder paradigm facilitated with skip-connections, thus allowing global context and fine suture detail to be captured inside the images.

![image](https://github.com/user-attachments/assets/a549f452-fad6-4647-a9fc-9ec14bb33fad)
|:-:|
|Augmented data

## Immediacy Parameters
Key parameters for training include:
Learning rate
Group size
Number of Epochs
Dice coefficient loss or cross-entropy loss functions.
Optimizer: Adam

## Training Stage
Train the Unet model with the prepared dataset. A description of the training loop is exhibit below:
The loss function is to be minimized.
Periodically evaluate the model on the validation set to monitor performance and tune the hyperparameters if necessary.
Applying early stopping to prevent overfitting.
Running Monitoring and Results
Performance Indicators

![image](https://github.com/user-attachments/assets/42734457-039e-4264-a54b-abd39ef4850c)
|:-:|
|Training and Validation accuracy 

![image](https://github.com/user-attachments/assets/9a04d1c7-2d40-49a2-9911-32e65eace3f9)
|:-:|
|Training and Validation loss


## Test Results
Empirical verification of the promising results on a separate test dataset by the trained Unet model: This shows an accuracy of 0.91, suggesting a well-fitted model that can segment the region of spleen in ultrasound images. This further adds metrics for model performance audit, such as Dice coefficient and also precision-recall scores. Conclusion This attests to how the architecture of the Unet network would be useful and employed to segment medical images. A value of accuracy up to 0.91 has been derived, which supports it to be better in segmentation of spleen regions on ultrasound slices and thus holding ground for it for application in diagnostic processing pathologies related to the spleen.
