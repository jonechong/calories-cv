# Calories CV v1.0
## Overview
This is a cross-platform application designed to make tracking your daily caloric intake as simple as taking a picture. Users can snap photos of their meals or upload images to get estimated calorie counts.

## Features
* Take pictures of your food to estimate calorie count

* Upload existing images for calorie estimation

* Track your daily calorie intake

* View history of calorie intake

## Technology Stack
* **Frontend**: React Native (Expo CLI)
* **Backend**: FastAPI
* **Database**: (Frontend) SQlite
* **Machine Learning**: (Framework) Pytorch, (Model Architecture) MobileNetV2

## Functional Requirements:
### Frontend
* **Camera Integration**: Access device's camera to take pictures (where applicable)
* **Image Upload**: Upload image files
* **User Interface**: User-friendly interface to execute use cases

### Backend
* **Image Processing**: Receive image data, process image and return predictions
* **Model Inference**: Host machine learning model for image classification
* **Database Operations**: Store and retrieve food item data

### Database
* **Food Data**: Store food data for each food item
* **Image Metadata**: Store metadata for images uploaded

### Machine Learning
* **Type of Model**: Choose a machine learning model suited for image classification
* **Training Data**: Procure a large dataset of food images tagged with accurate calorie information for training the model.
* **Validation Data**: Separate dataset to validate the model's performance.
* **Test Data**: Dataset to evaluate performance of the model

## Use Case Diagram
![Use Case Diagram](./diagrams/v1.0/Use%20Case%20Diagram.png)

## Architecture
### Frontend
![Component_Hierarchy_Diagram](./diagrams/v1.0/Component%20Hierarchy%20Diagram.png)
### Database
![Database Schema](./diagrams/v1.0/Database%20Schema.png)
### Machine Learning
![ML Pipeline](./diagrams/v1.0/ML%20Pipeline.png)

For more info on the ML aspect of this project, do visit the ML repo: https://github.com/jonechong/calories-cv-model/tree/main

## Video

https://drive.google.com/file/d/1QsXh_TSl-RuemDHeobQjXPuJZ3tXiO3T/view?usp=sharing

## Notes
 
Currently, the app is severely limited due to the amount of quality dataset and nutritional database that we have.
  
Logo Designer & Credits:
[@raykowithfries](https://www.instagram.com/raykowithfries/)
