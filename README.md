# Smoking Detection using CNN

## 1. Project Goal/Motivation
The "No Smoking" signs at gas stations are essential for safety due to the highly flammable gasoline vapors present. Traditional methods for detecting smoking can be expensive. This project aims to provide a cost-effective solution by utilizing artificial intelligence. By training a convolutional neural network (CNN) to recognize smoking behavior from images, we can develop an alert system using existing surveillance cameras, enhancing safety at gas stations.

## 2. Data Collection
I used a dataset from Kaggle (https://www.kaggle.com/datasets/sujaykapadnis/smoking), which contains 1,120 images equally divided into smokers and non-smokers. These images were collected from various search engines with diverse keywords to ensure a rich and varied dataset. All images were preprocessed to a resolution of 250×250 pixels. The dataset was split into 80% for training and validation, and 20% for testing.

## 3. How to Use the Project
1. Clone the repository and navigate to the project directory.
4. It's recommended to create a virtual environment within your project directory to manage dependencies. Utilize the provided requirements.txt file to install all necessary dependencies. You can achieve this by running the following command in your terminal or command prompt: pip install -r requirements.txt.
2. Set up the data as described in the setup section.
3. If you want to train the model, run the training part of the jupyter notebook.
4. To use the pretrained model, download the folder "models" including the pretrained model "smokingdetector_v1.keras" from https://drive.google.com/drive/folders/1OwVv_H8tsGRpusHSZ-441n8BlMhyUZDt?usp=sharing. Insert the folder into your project directory and run the evaluation or prediction scripts (starting from chapter 4 of the jupyter notebook). Be aware that some functions of chapter 1 to 3 are necessary to run the rest of the jupyter notebook. Therefore, it is recommended to go through all chapters in order to understand the whole project (just leave out the training & saving of the model).

## 4. Setup
1. Data Acquisition: Download the training, validation, and testing images from Kaggle (https://www.kaggle.com/datasets/sujaykapadnis/smoking).
2. Folder Structure: Organize your project directory by creating three main folders: "training_images", "validation_images", and "testing_images". Within each of these folders, create two subfolders labelled "smoking" and "notsmoking", and place the corresponding images into these subfolders.
3. Pretrained Model Option: Alternatively, you can utilize the pretrained model "smokingdetector_v1.keras" located in the "models" folder if you prefer not to train your own model. To apply the trained model to your own images, simply use the code in part 5 of the smokingdetection.ipynb file. Replace "path_to_your_image.jpg" with the path to your image and execute the code. The model will predict whether the image contains smoking behavior or not, providing valuable insights for further analysis or application.

By following these steps, you'll have your project environment ready for training your model or utilizing the pretrained one, ensuring smooth development and experimentation.

## 5. Credits
Author: Florian Rieser

Dataset: Khan, Ali (2022), “Smoker Detection Dataset”, Mendeley Data, V1, doi: 10.17632/j45dj8bgfc.1

## 6. License
This project is licensed under the CC BY 4.0 License. See the https://creativecommons.org/licenses/by/4.0/deed.en for details.



