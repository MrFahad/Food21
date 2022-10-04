# Food21 Classifier Web App

This is a web application which allows a user to upload an image and the get the probabilities for top 3 classes from the neural network.

[The Live Web App can be found here](https://mrfahad.herokuapp.com//)

### Details about the Neural Network

#### Dataset
- [Food-101](https://www.kaggle.com/dLogical/Midterm-210044316)

#### Model
- Fine Tuned **ResNet50**

#### Training Environment
- [Python](https://www.python.org/): version 3.6
- [fastai](https://www.fast.ai/): version 1.0.61
- [PyTorch](https://pytorch.org/): version 1.12.1
- [CUDA](https://developer.nvidia.com/cuda-zone): version 10.2

#### Deployment Environment
- [Python](https://www.python.org/): version 3.10
- [fastai](https://www.fast.ai/): version 1.0.61
- [PyTorch](https://pytorch.org/): version 1.12.1 (cpu version)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/): version 2.2.2
- [Heroku](https://dashboard.heroku.com/)

### For deployment on your system??

1 - pip install -r requirements.txt`

#### Run using flask commands

To run the flask application

`flask run`

This runs your flask application on [http://127.0.0.1:5000](http://127.0.0.1:5000/)

To run the application on port 80

`flask run -p 80`

To run the application on your network IP address

`flask run -h 0.0.0.0`

#### Run using python

`python app.py`

This command will run the application on your network IP address on port 80.

**You can access the site using _127.0.0.1_ too even when running on network IP**