# Project: University Student Admission Prediciton Project 
> The goal of this project is to predict the admission of a student in an University taking into account the following points:

> Dataset: https://www.kaggle.com/adityadeshpande23/admissionpredictioncsv

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
The goal of this project is to predict the admission of a student in an University taking into account the following points:
- General test score (GRE).
- Test of English as a Foreign Languge score (TOEFL).
- University rating.
- Statement of Purpose (SOP).
- Letter of Recommendation (LOR). 
- Cumulative Grade Point Average (CGPA).

Purpose: Practice the implementation of the Linear Regression Machine Learning Model till deployment (Google Cloud).

## Technologies Used
- Python 3.7.7
- Flask 1.1.2
- Werkzeug 1.0.1
- Google Cloud SDK 347.0.0


## Setup
requirements.txt:
   certifi==2020.6.20
   click==7.1.2
   Flask==1.1.2
   Flask-Cors==3.0.8
   itsdangerous==1.1.0
   Jinja2==2.11.2
   MarkupSafe==1.1.1
   six==1.15.0

To install the requiriments.txt file in your environment:
1. cd to the directory where requirements.txt is located.
2. activate your virtualenv.
3. run the command "pip install -r requirements.txt".

To deploy the files into Google Cloud:
1. Create an account on  https://cloud.google.com/.
2. Create a new project on the console (IAM & admin).
3. Once the project gets created, select App Engine and select Dashboard.
3. Install Google Cloud SDK on your system: https://cloud.google.com/sdk/docs/install
4. Run "gcloud init" in the directory where the files has been created.
5. Introduce the Project ID.
6. Run "gcloud auth login".
7. Run "gcloud app deploy app.yaml".
8. Introduce your billing data. You have 3 months of free trial (https://cloud.google.com/terms/free-trial/?_ga=2.134446513.-1935026008.1613996760)


## Project Status
Project is: _complete_ 


## Room for Improvement
The Linear Regression is used for learning purposes but for sure the model can be tested and improved with other Machine Learning Algorithms.

To do:
- Test other ML algorithms


## Contact
Created by [Xavier Nuel Gavaldà](xaviernuelgav@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
