# Brain-Haemorrhage-detection-and-Patient-Monitoring
![image](https://user-images.githubusercontent.com/42277997/121149746-8b097300-c860-11eb-9e4c-be150ceeeeb9.png)

## Problem Statement:
Intracerebral haemorrhage is an important public health problem leading to high rates of death and disability in adults. Although the number of hospital admissions for intracerebral haemorrhage has increased worldwide in the past 10 years, mortality has not fallen. Results of clinical trials and observational studies suggest that coordinated primary and specialty care is associated with lower mortality than is typical community practice. Development of treatment goals for critical care, and new sequences of care and specialty practice can improve outcome after intracerebral haemorrhage.
The utilization of deep learning for clinical applications has expanded exponentially in the most recent decade. Regardless of whether it's to recognize diabetes utilizing retino-treatment, foresee pneumonia from Chest X-beams or check cells and measure organs utilizing image segmentation, deep learning is being used all over. Datasets are now being made uninhibitedly accessible for experts to fabricate models with.

##Introduction
Intracerebral hemorrhage is an important public health problem leading to high rates of death and disability in adults. Although the number of hospital admissions for intracerebral hemorrhage has increased worldwide in the past 10 years, mortality has not fallen. Results of clinical trials and observational studies suggest that coordinated primary and specialty care is associated with lower mortality than is typical community practice. Development of treatment goals for critical care, and new sequences of care and specialty practice can improve outcome after intracerebral hemorrhage.
The utilization of deep learning for clinical applications has expanded exponentially in the most recent decade. Regardless of whether it's to recognize diabetes utilizing retino-treatment, foresee pneumonia from Chest X-beams or check cells and measure organs utilizing image segmentation, deep learning is being used all over. Datasets are now being made uninhibitedly accessible for experts to fabricate models with. Moreover, with the advent of IoT, we can provide remote healthcare to patients who have been diagnosed with life-threatening diseases.
Keeping all these points in mind, we aim to develop an end-to-end solution involving automated brain hemorrhage detection using computed tomography and provide remote health monitoring

## Problem Goal(s):
Brain haemorrhage is a severe threat to human life, and its timely and correct diagnosis and treatment are of great importance. Multiple types of brain haemorrhage can be distinguished depending on the location and character of bleeding. In most of the healthcare institutions, diagnosis is confirmed only after a doctor has manually examined the computed topography (CT) scans. This can lead to delayed diagnosis and can prove hazardous to the patient’s health. Our goal is to automate this entire process, hence providing early diagnosis which can go a long way in providing timely treatment and increasing the chances of saving a patient’s life.

## Solution

Deep Learning applied in healthcare can contribute to saving time between medical imaging, diagnosis and beginning treatment. Automated diagnosis can be done within seconds, thanks to these computer vision models.

Although deep learning can help to detect anomalies in medical imaging, finding valuable datasets and pre-processing this data could be painful.

In this project, I will diagnose brain hemorrhage by using deep learning, Computed Tomographies (CT) of the brain.

To achieve a good accuracy I tried to use different data augmentations.

Now, What’s data augmentation?

We know that the more data we have, our model will perform better. But collecting a good amount of data from the wild could be a hard task.

Data augmentation is a technique used in deep learning that augments the size of the current data instead of collecting data from the wild.

Some data augmentations examples are: adding noise or applying data transformations such horizontal and vertical flips and color distortions.

By augmenting your dataset, you can achieve excellent results with a small amount of data. I did a little research about data augmentations used specifically for medical imaging and it happens that when you add contrast to the images, model achieves a better accuracy. A variety of augmentation strategies can be used to get better results. Training the model

I chose Keras Deep Learning framework with Tensorflow backend to get the best results for Image Preprocessing and CNN(Resnet 52) for better accuracy and results

80% of the dataset was used for training and 20% for testing.

## Demo
Video Link: https://drive.google.com/file/d/1bTB9np5Jbv-qz5WiqrJQGKItkjI3eSnP/view?usp=sharing

![image](https://user-images.githubusercontent.com/42277997/121150329-0d923280-c861-11eb-9cbf-22f507bef30d.png)
![image](https://user-images.githubusercontent.com/42277997/121150992-9f01a480-c861-11eb-8a79-2ae06aa2c6b7.png)
![image](https://user-images.githubusercontent.com/42277997/121151124-bb054600-c861-11eb-8ee6-f851a5711893.png)

