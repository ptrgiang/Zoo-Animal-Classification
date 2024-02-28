# Zoo Animal Classification: Random Forest Classifier

## Project Overview:
This project involves the development of a Random Forest Classifier that classifies various animals into their respective classes based on their traits.

## Dataset:
The dataset includes the classification of 7 different types of animals along with their characteristics. Below is a brief explanation of each column in the dataset:

- Class_Number: Identifier for the animal's class.
- Number_Of_Animal_Species_In_Class: Number of species in each class.
- Class_Type: Type of animal class (Mammal, Bird, Reptile, Fish, Amphibian, Bug, Invertebrate).
- Animal_Names: List of Animal Species in each class.
- Hair: Whether the Animal has hair or not.
- Feathers: Whether the Animal has feathers or not.
- Eggs: Whether the Animal reproduces by laying eggs or not.
- Milk: Whether the Animal produces milk or not.
- Airborne: Whether the Animal is able to fly or not.
- Aquatic: Whether the Animal is aquatic or not.
- Predator: Whether the Animal is a predator or not.
- Toothed: Whether the Animal has teeth or not.
- Backbone: Whether the Animal has a backbone or not.
- Breathes: Whether the Animal breathes or not.
- Venomous: Whether the Animal is venomous or not.
- Fins: Whether the Animal has fins or not.
- Legs: Number of legs the Animal has (Numeric value).
- Tail: Whether the Animal has tail or not.
- Domestic: Whether the Animal is domestic or not.
- Catsize: Whether the Animal is of cat size or not.
- Class_type: Identifier for the animal's class (matching with Class_Number).

## Requirements:
1. Python: Python 3.7 or newer is required.
2. Libraries: pandas, numpy, sklearn
3. Data: The dataset in csv format is used for this project.

## Steps of Implementation:
1. Data Cleaning and Preprocessing: Find the missing values, outliers if any.
2. Model Building: Use Random Forest Classifier from sklearn library.
3. Model Training: Split the data into train and test set, train the model with the best parameters.
4. Model Evaluation: Check the performance of model using cross validation and confusion matrix.
6. Predictions: Predict the class of animals by utilizing the trained model.