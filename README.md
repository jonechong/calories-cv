# Calories CV v1.0 (Name TBD)
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

## Figma UI Wireframes (May not be actual design)
Figma Diagram (Work in Prog): https://www.figma.com/file/iJP6Gb055rOCt3edaB5Otz/cv-calories?type=design&node-id=0%3A1&mode=design&t=tOIJlxvQDAjwolk3-1



## Cloning:
If you wish to clone this repo, make sure to also clone the submodules. You can do this by: git clone --recursive <URL-of-main-repo>, where you add in the url accordingly.

  
