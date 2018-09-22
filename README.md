# Species Predictor
python flask webapp which deals with iris dataset and classify them as some species based on user's input

**Libraries used:**  
a. EDA: Numpy, Pandas  
b. ML: sklearn (LogisticRegression, DecisionTreeClassifier, KNeighborsClassifier)  
c. persistance: Pickle  
d. Plotting in jupyter notebook: matplot, seaborn


**Code structuring:**  
This project follows cookie-cutter template.  

a. data: holds all data. 2 subfolders (raw and processed). raw folder contains the raw youtube comments csv, whereas processed folder contains the merged csv post processing.  
b. model: contains different models (logistic regression, kNN, SVM)  
c. notebook: contains the jupyter notebook having entire logic of how data is processed and model is generated/persisted.  
d. static: contains static content like images 
e. templates: contains the html pages used in application.  
f. app.py (starting point)  


# Application Screenshots  

**Main Application**  
![Alt text](./screenshots/main_app.png?raw=true "Home Page")  


**Preview Page**  
![Alt text](./screenshots/preview_page.png?raw=true "Home Page") 
