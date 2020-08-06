[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

Humans are excellent at vision, our brain is very powerful in visual recognition. Given a dog, one can easily detect it’s breed the only condition is you be aware of
all the dog breeds on this planet! Now this becomes a quite challenging task for a
normal human. Consider you love a specific dog breed(say, labrador) and want to
adopt a dog of the same breed, you go to shop and bring home your lovely new
friend. How do you know if that’s the correct dog breed you have got?? Many
times it becomes hard for humans to identify the dog’s breed. This is a multi-class classification problem where we can use supervised machine learning to solve this problem.


![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification and localization, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

## Project Problem Statement :

The goal of the project is to build a machine learning model that can be used within web app to process real-world, user-supplied images. The algorithm has to perform two tasks: 
- Dog face detector: Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. 
- Human face detector: If supplied an image of a human, the code will identify the resembling dog breed.

## Project Datasets :
-	Dog images dataset: The dog image dataset has 8351 total images which are sorted into directories. 
-	Human images dataset: The human dataset contains 13233 total human images which are sorted into directories. 


### Instructions
```
1.	Import Datasets
2.	Detect Humans
3.	Detect Dogs
4.	Create a CNN to Classify Dog Breeds (from Scratch)
5.	Create a CNN to Classify Dog Breeds (using Transfer Learning)
6.	Write  Algorithm
7.	Test  Algorithm
```
## Evaluation

Your project will be reviewed by a Udacity reviewer against the CNN project rubric.  Review this rubric thoroughly and self-evaluate your project before submission.  All criteria found in the rubric must meet specifications for you to pass.


## Project Submission

Your submission should consist of the github link to your repository.  Your repository should contain:
- The `dog_app.ipynb` file with fully functional code, all code cells executed and displaying output, and all questions answered.
- An HTML or PDF export of the project notebook with the name `Dog Identification App Reports.pdf`.

