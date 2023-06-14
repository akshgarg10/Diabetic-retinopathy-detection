# Diabetic-retinopathy-detection
This is a model that helps us in early detection of diabetic retinopathy<br><br>
Here is a general overview of this project : -
1) Data Collection
2) Pre-Preocessing
3) Network Architecutre
4) Training
5) Evaluation & Deployment
<br>

<h1>Working </h1>
This work employs the CNN methodology for detecting the diabetic retinopathy based on severity level. Many processes will be carried out before feeding the images to the network. 
We will train the two models in this work: our proposed model and the regression model and then we will make a comparison between the accuracies obtained by the two models.
So, we will be taking the data for Diabetic Retinopathy Detection and for APTOS blindness detection from Kaggle. Both the datasets contain thousands of retinal images under different conditions. As the images contains a lot of noise, like some images may be out of focus, some may have a lot of exposure, some may have extra lighting, presence of the black background, etc. so we need to do preprocessing in order to get them in the standard format. Now we will analyze the data, if the data is highly unbalanced among the diabetic retinopathy severity image classes, it will give rise to the propensity of data augmentation. Data augmentation is framed by aligning one class to the class with most samples, in order to balance the data among the diabetic retinopathy severity classes. The implementation will be executed using python language, where a wide variety of libraries were employed for processing of images and to get acquainted with the system for creating deep learning network. The type of library for image management and preprocessing will be OpenCV.
However, the mathematical functions required for the implementation is performed by NumPy. TensorFlow and Scikit-learn will also use for efficient management of CNN models and for defining the model. The implementation of the model will make use of GPU enabled devices for easier and faster processing.
<br><br>
This is a team project of 4 members, where I played a role in Data Augmentation (scaling, rotating and flipping) and Data Generation(same height and width of images)<br>

![unnamed](https://github.com/akshgarg10/Diabetic-retinopathy-detection/assets/104502015/6ec581e4-5a32-454e-bc32-38df99b2fac6)

<br><br>
A sample folder has been provided to run the model on these sample images, I wont be able to upload the test datasets here on GitHub due to the large size, but here is a link below which can guide you to the datasets from kaggle <br>
https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data


