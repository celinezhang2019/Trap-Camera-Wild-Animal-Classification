# Trap-Camera-Wild-Animal-Classification
Msc Project:https://github.com/celinezhang2019/Trap-Camera-Wild-Animal-Classification/wiki

### 1.Instruction

(1) The online prediction website:http://35.221.136.245:5000/static/predict.html

(2) This project studies 22 species of wild animals.









### 2. Data Sources
All the raw data are collected from http://lila.science/datasets

Four datasets are used for modeling.





### 3. Code

(1) Data_preparation.ipynb

Prepare the images to the desired sized pixels' ".npy" format dataset in Python. The purpose is to make the data loading issue easily and quickly. Every time, before modeling, we can load the .npy datasets and then train the model.

(2) AlexNet_S.ipynb

The proposed model code, which can generate model package including .h5 files and .ckpt file to save the model structure and weights.

(3) Traditional_model.ipynb

Including logistic regression(LR), KNN, SVM, Random Forest Modeling code



### 4. Test Image File

(1) correctly predicted test sample image: 
correct_elephant.jpeg; 
correct_lion.jpg 

(2) wrongly predicted test sample image:
wrong_elephant.jpeg; 
wrong_lion.jpg 

(3) images zipfile:
zipimg.zip  
(contains 4 images: 1 elephant, 1 zebra, 1 giraffe, 1 gazellethomsons)

















