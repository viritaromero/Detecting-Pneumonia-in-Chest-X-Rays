# Creating a model that detects Pneumonia in Chest X-Rays
A Computer Vision model made in PyTorch that detects Pneumonia in Chest X-Rays
![alt text](https://cdn-images-1.medium.com/max/716/0*KCg1HEnTwnvSuVA9.jpg)

# AI in Healthcare

AI in healthcare will always be the reason I started to dig in this field of Artificial Intelligence. The scope is huge and the impact you make in the world, too. Making a prototype to solve medical problems will always be a reason to be proud of.

It’s unbelievable how AI is improving the healthcare field, specifically in medical diagnosis. AI will improve the way Doctors diagnose and treat diseases. It’s not a competition but an opportunity to join forces!

This time, detecting Pneumonia in Chest X-Ray images, is a great experience. I will show you two ways to detect Pneumonia in Chest X-Rays: Using a Convolutional Neural Network with PyTorch (It’s my favorite!).

# What is Pneumonia?

According to the American Lung Association, Pneumonia is an infection that inflames your lungs’ air sacs (alveoli). The air sacs may fill up with fluid or pus, causing symptoms such as a cough, fever, chills and trouble breathing.

# Pneumonia Symptoms

Most common Pneumonia symptoms are:

- Cough, which may produce greenish, yellow or even bloody mucus
- Fever, sweating and shaking chills
- Shortness of breath
- Rapid, shallow breathing
- Sharp or stabbing chest pain that gets worse when you breathe deeply or cough
- Loss of appetite, low energy, and fatigue
- Nausea and vomiting, especially in small children
- Confusion, especially in older people


# Chest X-Ray Images (Pneumonia)

I will use the Chest X-Ray Images (Pneumonia) Dataset. You can find this dataset at Kaggle. It’s organized into 3 folders (train, test and val sets) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

I will upload the images and tag them into 2 categories: Normal and Pneumonia.

You can get the dataset here: 

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/




# Instructions

The project is broken down into multiple steps:

    Load and preprocess the image dataset
    Train the image classifier on your dataset
    Use the trained classifier to predict image content

Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. The dataset was uploaded to Google Drive, so you can download it directly (the code to download it is in the notebook). For more details, the notebook includes the instructions to follow.

If you want to load the trained model, the code to download it, is in the notebook, in the "Load the checkpoint" section. The model was also uploaded to Google drive, so you can download it.

This project is updated to be compatible with PyTorch 0.4.0

Read more about this project here: https://medium.com/datadriveninvestor/detecting-pneumonia-in-chest-x-rays-with-custom-vision-and-pytorch-e270e071e982
