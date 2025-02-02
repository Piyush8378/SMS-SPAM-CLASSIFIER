# SMS-SPAM-CLASSIFIER


### Overview

A simple Machine learning and `NLP` based Web Application which classify the given messages as Spam or Ham(Not Spam) built using `Flask` and deployed on `Heroku`.

 ### Technical Aspect
 
 This Project is mainly divided into two parts:
 
 1. Exploring the dataset, Preprocessing texts and traning the model using `Sklearn`.
 2. Building and hosting a `flask` web app on .


**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 


### Installation

The Code is written in Python 3.8.

```
pip install -r requirements.txt 
```

*To clone the repository*

```


### Run 

*To Run the Application*

```
python app.py
```






