# Python-App-Engine
Example of a python website made with Flask and configured to be uploaded to Google App Engine

This site is developed in python version 2.7.

You need to create a project inside https://console.developers.google.com

It's necessary to run:
* `pip install -t lib -r requirements.txt`
so the "lib" directory is generated and bundled into Google App Engine Project

Install the Google SDK in order to use the command "gcloud" by console
Execute 
* `gcloud auth login` # to select your current Gmail account
* `gcloud config set project PROJECT_ID` # to select the current project in which the code will be uploaded
* `dev_appserver.py app.yaml` # test the project in localhost
* `gcloud app deploy` # to deploy the application to Google App Engine