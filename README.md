# Project-4

## Overview
#### The goal of this project is to understand how individual lifestyle factors contribute to carbon emissions. By analyzing a diverse dataset containing information about people's habits and behaviors, we aim to build a predictive model that estimates carbon emissions based on various lifestyle choices.

### Model Training
#### We employ a Random Forest Regressor model to predict carbon emissions. This model is well-suited for handling complex datasets and capturing non-linear relationships between lifestyle factors and emissions.

### Feature Importance Analysis
#### After training the model, we conducted a feature importance analysis to understand which factors have the most significant impact on carbon emissions. The top 10 most important features are listed below:

- #### 1. Vehicle Monthly Distance Km
- #### 2. Frequency of Traveling by Air (very frequently)
- #### 3. Vehicle Type (electric)
- #### 4. How Many New Clothes Monthly
- #### 5. Frequency of Traveling by Air (frequently)
- #### 6. Waste Bag Weekly Count
- #### 7. Vehicle Type (hybrid)
- #### 8. Body Type (obese)
- #### 9. Vehicle Type (petrol)
- #### 10. Heating Energy Source (electricity)

### Vizualizations
#### Using matplotlib, we provide various charts and graphs on key components such as:
 - #### 1. The biggest influencers on individual carbon emissions
 - #### 2. How the diet of an individual can affect carbon emissions
 - #### 3. Difference in carbon emissions across male and female genders

### Personal Data Prediction
#### We've provided a script to predict carbon emissions based on personal lifestyle data. Please prepare your personal data in an Excel sheet named personal_data.xlsx with similar columns to the dataset. Then run the provided script (Final_project_personal_data.ipynb) to generate predictions.

### Summary 
#### When analyzing this dataset it is apparent that some factors heavily influence carbon emission numbers and some factors have little to no effect. Using the Random Forest Regressor model, we were able to achieve an accuracy score of .92 quite easily. This allowed us to perform our feature importance analysis which then allowed us to produce several strong vizualizations to help showcase our dataset. Finally, we added in a way for you to input your own carbon emission data. Using an excel sheet that would then inform you if you were above or below the average carbon emission numbers in our dataset.

### Contributors
- #### Marissa Saucedo
- #### Josiah Johnson
- #### Kidus Gorfe
- #### Cameron Carson
- #### Johnathan Rascon
