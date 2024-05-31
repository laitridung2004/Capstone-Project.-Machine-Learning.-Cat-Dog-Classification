# UTILITIES
1. Referring to our git clone link: `git clone https://github.com/Dinhhoanghm/ml-project.git`
2. Referring to our libraries used: `pip install -q -r requirements.txt`
3. Referring to running our project: `classification_app.ipynb`

# OPERATING
This is our project structure:

![image](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/9d00b270-ffa9-4def-a556-6c6f3a4c4389)

The index standing before the folder name represents its order in our pipeline. The only folder that you need to examine our application is the GUI folder where we put our app interface inside called "classification_app.ipynb" that could show you the interface of our cat - dog classification project.

![image-1](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/8d1877c3-7ae1-4a30-ba74-3698323bfa03)

Before demoing our project, you would have to remember some of this requirements.

## 1. Changing path in the GUI Code
As we use Google Drive, specificially Google Collab as our mutual workspace, the path linked to folders and files in our project would be different from your folder downloaded, so make sure you changed all the path into the correct one for activating.

![image-4](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/4859d131-6fc5-4e74-8614-0f44b306f552)

*Note: If you have already installed scikit-learn library, make sure it is installed in 1.2.2 version which is Google Collab's version. 

We deeply recommend you using Google Collab to run our file by uploading all the file into a Drive folder so you do not have to change the path since that's how we cooperate in our project. The downloaded version in MS Teams is allocated into different folder for you to read. In case you want to upload all the file into Google Drive without any relocate file, please direct to the git clone that we put in the beginning, which is https://github.com/Dinhhoanghm/ml-project.git, you could directly download all the folder here (we allocate only the GUI file and the trained models only) then put them into your Drive to run.

*Note: As our full folder account for nearly 13GB due to the dataset, our file pushed in git only contain required file for you to run so that it would not take much space in your drive. In case you want to test it carefully or your drive is available, we recommend you push our whole project.

## 2. Operating our application
When you successfully open our application to classify cat and dog, the interface would present like this:

![image-2](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/72bd62d4-c307-41fd-b625-76e9d11e1434)

You could change the model you want to examine in the "Select Model" in the upside left, but everytime you change the model, you would have to upload your image again then classify them.

That's all of our guiding for you to operate our application. In case you want to deeply understand our project without spending hours reading the code, I will show you thoroughly what's inside our folder.

## 3. Our folder structure

![image](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/9d00b270-ffa9-4def-a556-6c6f3a4c4389)

### 3.1. Data

![image-5](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/39e77edb-b132-4b72-9caf-4c9662ece795)

There are two zip file in this folder, one named "data" and the other is "data_folder". The former, "data" is the original dataset in which we download from kaggle and the latter, "data_folder" is our dataset after augmented, which is used to train our models.

### 3.2. Data preprocessing

![image-7](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/70d68de8-75e8-47b1-86ce-4fde02ca72c8)

We have three ipynb files in this folder which are labelled as the work order. The "data_preprocessing" file is used to visualize the data and apply some techniques so that we could get to know our dataset better. The second file "error_analyse" is when we try putting our dataset into a pre-trained model to see how it work, and more importantly, see the error related to models and dataset. Error related to dataset such as the model could not recognize picture where the subject is too small will be solved in the third file "data_augmentation" by zoom our all the dataset in a specific scale. For the error related to model, we will categorize them and avoid them in models that we would build later.

### 3.3. Machine Learning models

![image-8](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/1d479c02-b53b-4042-b73b-5c895f798095)

There is only one ipynb file in which we would operate three models at the same time in this code. Our model will be saved in file formated "PKL". Our application would recognize this file in "model path" as our model to run.

### 3.4. Deep Learning models

![image-9](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/80dbc024-9683-4097-a1b0-366e6281e0e2)

In our process, we work with ANN model and CNN model separately so there structure is a little different. After training process, both ANN model and CNN model will return a file formated "h5" which you will use to operate our application.

![image-10](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/d72b9b2b-f558-4469-9911-1b8b4e65b3a3)

![image-11](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/694b75cd-d9ba-488b-b509-1df59b20915a)

### 3.5. Transfer Learning models

![image-12](https://github.com/thocon00015/Capstone-Project.-Machine-Learning.-Cat-Dog-Classification/assets/102193912/bb275d17-3895-4a18-a344-0dd0072723b2)

We put three pre-trained model VGG19, InceptionV3 and Xception together in a file named "transfer learning_models.ipynb" for faster and consistent coding. After our training process, they would return you with each model in two files formated "h5" and "pkl". The "h5" file will be the material you need operating our application.

# THANK YOU
That's all about our project description. Thank you so much for spending your time in our project. We are really appriciate your efforts and what you have done so far. Hope you all the best. Thank you!!!
