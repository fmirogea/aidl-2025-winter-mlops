# Session 5
Implement a Deep Learning App. Train a model to classify text reviews between positive and negative and deploy a web app to predict on user reviews. 
Then, deploy the model using Google Cloud App Engine.

## Installation
### With Conda
Create a conda environment by running
```
conda create --name aidl-session5 python=3.10
```
Then, activate the environment
```
conda activate aidl-session5
```
and install the dependencies
```
pip install -r requirements.txt
```

## Running the project
To train the model run:
```
python session-5/train.py
```

To run the app run:
```
python session-5/app/main.py
```
then, you can test you app by going to http://localhost:8080
