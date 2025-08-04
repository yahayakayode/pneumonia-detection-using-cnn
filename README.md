## Pneumonia Detection Using Convolutional Neural Networkcnn (CNN)

### Project Overview 
Pneumonia is a life-threatening lung infection resulting from several different viral infections. Early detection of pneumonia is crucial for determining the appropriate treatment of the disease and preventing and possible preventive measures. Chest radiographs are the most widely used tool for diagnosing pneumonia; however, they are subject to inter-class variability, and similarity to other pulmonary diseases, and the diagnosis largely depends on the clinicians’ expertise in detecting early pneumonia traces. 

To assist medical practitioners, a Convolutional Neural Networks `CNN`-based deep learning model was developed to detect and classify `Chest X-ray` images into two classes “Pneumonia” and “Normal. Class Activation Mapping (CAM) was also applied to the detected images to intensify the potential regions of pneumonia in CXR images.



### Dataset
 The dataset used contains `5,856` Chest X-Ray images (in JPEG format), 3 folders named train, test and val, and 2 categories `Pneumonia` and `Normal`. The dataset can be found [here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download).<br> Below are the details of the 3 folders in the dataset.

 #### Samples Pneumonia X-Ray images

 ![image](https://github.com/yahayakayode/pneumonia-detection-using-cnn/assets/40303292/3028f9d5-de39-4968-b9b3-2bed87c49e04)


  #### Samples Normal X-Ray images

  ![image](https://github.com/yahayakayode/pneumonia-detection-using-cnn/assets/40303292/96ebab5b-4f23-4c1b-a0f6-600291b3d056)



 ### Conclusion
After analyzing a dataset of over 5,000 images, a model was developed using Convolutional Neural Networks (CNN). The model achieved an accuracy of 83.81%. This system can be applied in medical imaging settings to assist in diagnosing patients who may have pneumonia, enabling earlier detection and improved treatment outcomes.
