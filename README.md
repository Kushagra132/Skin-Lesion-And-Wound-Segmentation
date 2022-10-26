# Skin-Lesion-And-Wound-Segmentation
* Determined lesions and wounds’ outline by semantic image segmentation in Dermoscopic and Medical images using and modifying various deep learning architectures to overcome certain specific challenges like low contrast, obscure lesion boundaries etc in medical images.
* Obtained Dice coefficient as high as 93.75% on certain datasets and concluded which architecture and loss function performs better on a particular medical dataset.

# Learning curve and Progress
* Fundamental of Deep Learning - Backpropagation, Convolution, Pooling, Activation Functions, etc.
* Evaluation Metrics - Accuracy, Precision, Recall, IOU, DSC
* Image Segmentation Models - UNet, SegNet and Deeplabv3 (for ISIC 2016 Skin lesion segmentation)
* Class Activation Maps - GradCam and ScoreCam (using VGG16 on a Kaggle dataset)
* Selected some Medical image segmentation datasets - DRIVE, Foot Ulcer Segmentation, COVID19 - I, COVID19 - II, ISIC 2016 & Cardiac MR
* Computation of results using baseline segmentation models and their comparison
* Developing insights - Focused on improving accuracy by understanding input parameters and model architecture
* Paving way for future improvements on various datasets using the knowledge gained

# Results and Highlights
![image](https://user-images.githubusercontent.com/55876926/197972838-00038828-7cad-4796-8044-693d7d7fe20a.png)
![image](https://user-images.githubusercontent.com/55876926/197972897-a9babb09-dba2-411f-8aba-d674374a8b38.png)
![image](https://user-images.githubusercontent.com/55876926/197972943-dc811f17-f99b-47b2-acbe-f3b51c014a1f.png)
![image](https://user-images.githubusercontent.com/55876926/197972968-7010a831-d754-4b7c-a7d2-53f76189a394.png)
![image](https://user-images.githubusercontent.com/55876926/197973027-f39051b2-cda5-41dc-b99f-386b466b7911.png)
![image](https://user-images.githubusercontent.com/55876926/197973073-3a5a8d6e-33ff-4e6a-bb0a-7adccf791ffc.png)
![image](https://user-images.githubusercontent.com/55876926/197973129-96396f87-a997-451c-841c-2c7518658f1b.png)
![image](https://user-images.githubusercontent.com/55876926/197973161-11d8a593-2896-40ae-b0e4-e260869a9bae.png)
![image](https://user-images.githubusercontent.com/55876926/197973191-fa1c2d6b-41f0-4a16-9e73-469994aa6626.png)
![image](https://user-images.githubusercontent.com/55876926/197973224-aa477009-ab15-4004-b9ea-9bb06d1ab145.png)
![image](https://user-images.githubusercontent.com/55876926/197973245-7aed4240-f4ad-46ea-a1d7-ed31c5dab669.png)


# Future Work

* As we’ve understood layer-wise input parameters of the various segmentation models, we plan to perform model wise parameters’ comparison on more medical segmentation datasets in order to look into scope of improvement in any of the architecture
* Look into tools for improvement of segmentation results as Class Activation Maps (CAMs) does for the image classification problem since the explainability in segmentation problems is comparatively less explored.
* In future, we plan to dig deeper in comparing various baseline models results with type of medical dataset as to get an estimate of which model will perform better by doing some qualitative(image shape, type, etc.) analysis of the training and the test data’s images.
