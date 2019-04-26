# CSI WIP3 DATAMAPPERS
CSI (Computer Society of India) WIP-3.0. Team-DataMappers (Aditya Raj, Aaryaman Sharma, Arpit Jain).
This repository is for the project submission of CSI Winter Internship Program 3.0.

**Recommender System** is a system that seeks to predict or filter preferences according to the user’s choices. Recommender systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products, in general. A more formal definition of recommendation systems would be, it is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item.

### Workflow:-

Step 1. Collecting data.

Step 2. Storing of data.

Step 3. Filtering the data into train and test set.

Step 4. Fiting SVD (Singular Value Decomposition) Algorithm on Train Set.

Step 5. Now test the algo with test set.

Step 6. Compare TopN recommendation of KNN+SVD algo and a Random algo.

Step 7. Analyse RSME and Novelty to know accuracy of TopN recommendation .

### Main Driver Function:-
- MainTopN.py        ( Executing this files produces TopN recommendation using SVD+KNN algo among with a Random algo for comparision. )
- AccuracyClass.py   ( Executing this files produces RSME and MAE to get accuracy. ) 

### Software required to execute files:-
- Python 3 
- Spyder ( Anaconda )

### Library needed to be installed:-
- Surprise ( scikit-learn )
- Numpy
- Pandas

We have uploaded the detailed explanation of the RRS in the PDF file.

We have uploaded all the components required to execute this project including the MovieLens.csv file as the dataset.

_______________________

### Successfully completed - 26/04/2019 :) 
