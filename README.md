# About PathXplorer

A lot of high school students, especially those in their final years, feel confused about what career path to take. Even people who think they've figured it out sometimes realize later that they're on the wrong path and have to start over. That’s why we want to help solve this problem early on by helping people discover the right career path sooner. ourApp is a career guidance app that gives personalized career recommendations based on the RIASEC test, which helps identify your interests. Our main focus is on final-year high school and vocational school students, as well as educational institutions like schools and tutoring centers.


# Machine Learning Part

For the machine learning aspect of our app, we used a dataset of RIASEC test responses sourced from Kaggle. After cleaning and manually labeling the data, we split the dataset and applied downsampling to balance the distribution of labels. Our model uses multi-class classification to predict a user’s RIASEC type based on their test results. The model’s output is then used to recommend careers that align with the user’s RIASEC profile.

With our current architecture, we’ve achieved a very high accuracy and a low loss rate, demonstrating the model’s reliability. To further ensure consistent performance, we evaluated the model using a confusion matrix, which helped us fine-tune its precision and robustness.

# How to Use PathXplorer

1. Download and open the app
2. Register and/or login
3. Take the RIASEC test
4. Get your result
5. Explore your career

# RIASEC Test
![image](https://github.com/user-attachments/assets/62c97eaa-b2bd-4376-9213-82f888e7f1f2)

# Documentation
- [Dataset](https://github.com/PathXplorer-C242-PS289/MachineLearning/blob/main/data/riasec/labeled-data.csv)
- [Model](https://github.com/PathXplorer-C242-PS289/MachineLearning/blob/main/multi-class-model.ipynb)
- [Model TFLite](https://github.com/PathXplorer-C242-PS289/MachineLearning/blob/main/model.tflite)
