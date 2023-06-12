Project Title: As an AI engineer working in a biomedical company are tasked to
create a model for semantic segmentation for images containing cell neuclei.

Project Description:
1. Link to the source of data:
https://www.kaggle.com/competitions/data-science-bowl-2018/overview
2. Link to the dataset (Use this as the data):
data-science-bowl-2018.zip
3. Carry out the whole machine learning workflow for this project (Problem
Formulation →Data Preparation→Model Development→Model
Deployment)
4. For criteria, try to achieve training and validation accuracy of more than 80%
5. Make sure your model is not overfitting.
6. Build a U-Net for this project (for downsampling path, you can apply transfer
learning, then build your own upsampling path similarly as what we did in the
exercise).
8. For model deployment, try to use the model to make some predictions with
test data.

What your project does?
- import packages
- Data loading
- Convert the list of np array into a full np array
- Data preprocessing
- Convert the numpy array into tensorflow tensors
- Combine features and labels together to form a zip dataset
- Model development
- Compile the model
- Create functions to show predictions
- Create a custom callback function to display results during model training
- Create a TensorBoard callback object for the usage of TB
- Model training
- Model deployment
- Save the model

Any challenges you face and how you solve them? 
- Yes, the challenges that i face is a bit confius to understand the question. But after read carefully, i can do it better. Other than that, hard to create plot model.

