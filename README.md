# Classifying_Chicago_Crime
The project's aim is to develop a classification model that could help make accurate predictions about the crimes
- This could be a framework which can identify criminality in various categories. I want a program to be developed which could distribute a defined crime automatically to the division that can help law enforcement agencies appoint police officers or assign crime officers on the basis of a rating. We will use various feature extraction techniques together with various supervised machine-learning algorithms in Pyspark to solve this problem.
### The dataset is available on the following link
https://www.kaggle.com/chicago/chicago-crime
The dataset includes the following contents:

| Column name | datatype | Description |
| --- | -- | -- |
| ID | Numeric | Identifier for a particular case of crime |
| Case Number | String | Case number with the police | 
| Date | Date | Date and time at which the crime occured | 
| Block | String | Block where the crime occured | 
| IUCR | Numeric | Illinois Uniform Crime Reporting |
| Primary Type | String | Type of crime |
| Description | String | Description of the crime |
| Location Description | String | Location of the crime |
| Arrest | Boolean | Whether an arrest was made | 
| Domestic | Boolean | Whether it is a domestic violence case | 
| Beat | Numeric | -- | 
| District | Numeric | Disrict where the crime occured | 
| Ward | Numeric | Ward where the crime occured | 
| Community Area | Numeric | Community area where the crime occured |
| FBI Code | Numeric | FBI code for the crime |
| X Coordinate | Numeric | Loaction co-ordinates of the crime |
| Y Coordinate | Numeric | Loaction co-ordinates of the crime |
| Year | Numeric | Year when the crime occured | 
| Updated On | Date | Time and date when the investigation for the crime was updated | 
| Latitude | Numeric | Loaction co-ordinates of the crime | 
| Longitude | Numeric | Loaction co-ordinates of the crime |
| Location | String | Location of the crime |

### Project Objective
The goal of this analysis is to explore the Chicago Crimes Dataset from 2016-2017, classify the features that determine the arrest result, and construct a predictive model.

### Running the file?
. The entire notebook was executed on a single machine using the pyspark
### PROCEDURE 
- Step 1 : Data Cleaning using Python
- Step 2: Data Loading and extraction in pyspark into data frames
- Step 3: Creating a pipeline and chaning the extracted features into vectors using various multi-classification techniques
- Step 4: Randomly splitting the data into Train 70% and Test 30% data.
- Step 5: Training the model using Logistic Regression and Naive Bayes classifier algorithms
- Step 6: Making predictions and evaluating the model to check the accuracy of the data using 

