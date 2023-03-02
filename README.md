# Sports-Personality-Classifer


## About
This is a machine learning project that aims to classify different sports personalities based on their facial features such as 2 eyes. The classifier is built using machine learning techniques and is capable of predicting the sports player with high accuracy.

The project has 5 target classes :
- Virat Kohli 
- Lionel Messi
- Maria Sharapova
- Roger Federer
- Serena Williams


## Folder Structure 

The folder structure and it's description is as follows:
- UI - Contains the front end files of HTML , CSS and JavaScript
- Server - Contains the flask server along with util.py file and b64 encoding specifics
- Model - Contains the ML model in a Jupyter notebook and the final model pickle file
- Images - Contains the primary dataset segregated into the 5 target classes

## Tech Stack and Tools Used
- Python
- Numpy and OpenCV for data cleaning
- Matplotlib & Seaborn for data visualization
- Sklearn for model building
- Jupyter notebook and visual studio code 
- Python flask for http server
- HTML/CSS/Javascript for UI



## Installation and running on localhost 

To install the necessary dependencies, use the following command:
```
pip install -r requirements.txt
```

To run the project on your local host , use the following command in the server directory:
```
python server.py
```

