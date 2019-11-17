# Deep Learning with AWS SageMaker
## Project: Sentiment Analysis Web App

## Project Overview
 In this project you will construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the [IMDB data set](http://ai.stanford.edu/~amaas/data/sentiment/). You will create this model using Amazon's SageMaker service. In addition, you will deploy your model and construct a simple web app which will interact with the deployed model.
 
### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [nltk](https://www.nltk.org/)
- [bs4](https://pypi.org/project/beautifulsoup4/)
- [Pickle](https://docs.python.org/3/library/pickle.html)
- [Torch](https://pytorch.org/)
- [Sagemaker](https://sagemaker.readthedocs.io/en/stable/)
- [Boto3](https://boto3.readthedocs.io/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.


### Code

This project contains three files:

- `SageMaker_Project.ipynb`: This is the main file where you will be performing your work on the project.
- `model.py`: A Python file that is used to construct the model.
- `train.py`: A Python file to train the model.
- `predict.py`: A Python file that contains custom inference code. 
- `util.py`: A Python file containing helper code that includes `review_to_words` and `convert_and_pad` pre-processing functions.
- `requirements.txt`: A file which tells SageMaker what custom Python libraries are required.

### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook SageMaker_Project.ipynb
```  
or
```bash
jupyter notebook SageMaker_Project.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

[IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/) will be used for this project. 
