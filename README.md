# Emerging-Technologies-PROJECT

### Project for Emerging Technologies by Kevin Flanagan G00228079

(1) Jupyter notebook with a trains model that shows its accuracy.

(2) Python script that runs a web service on the model.

(3) Dockerfile to build and run web service container.

(4) Set-up git repo and ReadMe. 

Requirements of the project: 

Create a model that accurately predicts wind turbine power output from wind speed values, as in the data set.

 * Jupyter notebook that trains a model using a data set.
 
Develop a web service that will display the pridicted power value based 0on speed values sent using a HTTP request

  * Web service based on train model using python.
  * Use a container to build and run the web service. (Dockerfile)
 
## Running the Project 

### Requirements 
  * Python 
  * Jupyter Notebook 
  * PIP within Anaconda
  
### Install with conda

conda install -c conda-forge notebook

### Install with pip

pip install notebook

### Run the Jupyter Notebook:

Open to the correct repository directory.

jupyter notebook

### How to run flask app on local machine

 * set FLASK_APP=webservice.py

 * python -m flask run

### Commands to Build, Run, Kill & Remove a Docker Image

 * To build a a Docker image use the command: docker build -t web-service .

 * To run the Docker image use the command: docker run -d -p 5000:5000 web-service

 * To check if the Docker image is running use the command: docker container ls

 * To kill the program that is running use the command: docker kill CONTAINER_ID

 * To remove a Docker image use the command: docker rm CONTAINER_ID 

