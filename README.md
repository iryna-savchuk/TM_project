## Text Mining: Predicting Airbnb Unlisting
**University:** NOVA Information Management School<br>
**Program:** Master’s Degree Program in Data Science and Advanced Analytics<br>
**Academic Year:** 2022/2023<br>

**Students of Group 17:** 
- Iryna Savchuk (20211310)
- Cátia Parrinha (20201320)
- Pedro Anastácio (20180040)

## Project Details
### Task Description 
Based on the real Airbnb textual data (such as property descriptions, host descriptions, and comments from previous guests), build a classification model to predict whether a property listed on Airbnb will be unlisted in the next quarter. The model's output for each property should be either (1) if the property was unlisted or (0) if it is still listed.

### Tools 
The project is to be developed using Python and libraries such as NLTK, Scikit Learn, Keras or PyTorch. 

### Corpora
The data is divided in following sets:
- **Train** (train.xlsx) (12,496 lines): Contains the Airbnb and host descriptions (“description” and “host_about” columns), as well as the information regarding the property listing status (“unlisted” column). A property is considered unlisted (1) if it got removed from the quarterly Airbnb list and it is considered listed (0) if it remains on that same list.
- **Train Reviews** (train_reviews.xlsx) (72,1402): This file has all the guests’ comments made to each Airbnb property. There can be more than one comment per property, not all properties have comments, and comments can appear in many languages.
- **Test** (test.xlsx) (1,389 lines): The structure of this dataset is the same as the train set, except that it does not contain the “unlisted” column. The teaching team is keeping this information secret. Students are expected to provide the predicted status (0 or 1) for each Airbnb in this set. Once the projects are delivered, the predictions will be compared with the actual (true) labels.
- **Test Reviews** (test_reviews.xlsx) (80,877): The structure of this dataset is the same as the train reviews set, but the comments correspond to the properties present on the test set.

### Data Source
Original data retrieved from: http://insideairbnb.com/

### Project Objective
With the NLP techniques acquired throughout the Text Mining course, implement an accurate and robust NLP classification model able to predict Airbnb unlisting.
