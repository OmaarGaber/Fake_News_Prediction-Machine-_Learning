# Fake_News_Prediction-Machine_Learning
My Latest Project Using Supervised ML " Logistic Regression "

The goal of this project is to detect which of the new is fake and which one is real

- importing libraries 
	- panads
	- numpy
	- matplotlib
	- re
	- from nltk.corpus import stopwords => this import becaous we are working in articles or big amount of words and " stopwords " meas 						the inneeded words that article or news could be understand without
	
	- from nltk.stem.porter import PorterStemmer  => An algorithm for suffix-prefix stripping.
	- from sklearn.feature_extraction.text import TfidfVectorizer => using it to convert the text into meaningful num to get the model
	- import train_test_split => making a train & test from data 
	- from sklearn.linear_model import LogisticRegression => to import the Logistic Regression model
	- from sklearn.metrics  import accuracy_score => to detect the accuracy of our model

- some Data exploration 
	- shape ,nulls ... etc
	- head , tail , info
	- unique, data types
	- describe

- Data processing 
	- missing Data and fill Nulls
	- drop duplicates & replace NaN
	- make some sum operations on the main features 

- Data Pre-processing 
	- Concatunate the 'title' & 'author' columns to make it one feature 
	- selecting tha main feature which is 'label' feature 
	- make a Stemming function to separate , detect and convert unsuitable words  
	- detect the values of x,y
	- vectorizing data & converting to numirized data 

- splitting data set to train and test
	- separating it into train and test for each one of y & x

- Training the model : Logistic Regression
	-fit the Logistic Regression model to x&y
	- deticting the accuracy " training Data " 
	- deticting the accuracy " testing Data " 

- Finally making a predictive system 

 
