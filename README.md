# SMS Bombing Spam Classifier for SMS Bombing Protection 

### Overview

A simple Machine learning and `NLP` based Web Application which classify the given messages as Spam or Ham(Not Spam) built using `Flask`

### Technical Aspect
 
 This Project is mainly divided into two parts:
 
 1. Exploring the dataset, Preprocessing texts and traning the model using `Sklearn`.
 2. Building a `flask` web app.

**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 


### Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```
pip install -r requirements.txt 
```


### Run 

*To Run the Application*

```
python app.py
```
