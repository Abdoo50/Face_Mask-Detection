# Face_Mask-Detection

Hello Dears,
This is my second Project as a Machine Learning at @SYNC

- Project Name: Real-time face mask Detection

- <h2>Description<h2\>:
**First** I get API token from Kaggle as a json format file and uploaded it into a colab notebook

**second** Installed Kaggle and configur the path of Kaggle.json file and Imported a dataset to use in our training step to our CNN Model and extracted it from compressed dataset file

**third** Import Pakages to preprocess our model and devided our Data into two sections {With_mask_files, Without_mask_files} and Print the length of our two labels

**fourth** Devide our Data into two labels and convert images into metrices to preprocess them and Resize the images
with mask  -->  1

without mask  -->  0

and Display images

**Fifth** Scale our data after training test split step

**Sixth** Building a Convolutional Neural Networks (CNN)

**Sefenth** Model evaluation is the process of assessing the performance of a machine learning model using various metrics and techniques. The goal of model evaluation is to determine how well the model is able to generalize to new, unseen data and to identify any potential weaknesses or areas for improvement.
in our case we get:
Test Accuracy = 0.9338186383247375
Loss function = 0.1776

**Finally* I built a predictive System to deploy our model in any image with Path only and it will classify if you wear a maskor No

Finally I want to thank you for reading

