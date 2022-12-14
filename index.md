# Data Science Portfolio by Christian Klaus

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

## Standalone Projects.

### Dispatcher Project 
![Alt text](docs/assets/title.png?sanitize=true)

**Pick-up Prediction of Parcels**

For our final project in the Data Science Bootcamp my team predicted the pick-up time of parcels using real world data from a dispatcher company. A big part was handling large tables, combining them and engineering features. On top we built an ML and a DL model of which we used the DL model finally because it performed a lot better. We built a solid pipeline with data loading und preprocessing steps running in python scripts. The model was deployed in the cloud and we also built a small web interface to demo the model. We were able to improve the baseline accuracy score of 0.24 to a score of 0.54 with the ML model and even 0.86 with the DL model. The Timeframe of the project was 10 full days with 3 collaborators. For version control and collaboration we used Github and for the dashboard trello.

Feel free to check the repo readme for more info.

[github](https://github.com/christianklausML/dispatcher-project)

### Olist Data Analysis Project

Goal of this project is to analyze a dataset provided by e-commerce marketplace Olist.

Steps:

* Exploratory Data Analysis (EDA)
* load csv data in a Python class and pandas DataFrame
* define and analyze business key metrics:
  * Order numbers
  * Total payment values
  * Customer Satisfaction
  * Shipping delay
  * 

[github](https://github.com/christianklausML/olist_data_analysis)

## Deep Learning.

### Computer Vision: Semantic Segmentation of Satellite Imagery for Roofs

Notebook objectives

* Implement a model for semantic segmentation using UNet
* Perform binary segmentation of satellite imagery to detect roofs which could be used for photovoltaic.

[github gist](https://gist.github.com/christianklausML/a5dbd392f646562489bc36f618725bc2)

[google colab](https://colab.research.google.com/drive/1ceBAttqzrA2kVMCGetwyeQBMMPx0Pss7?usp=sharing)

### Computer Vision: CIFAR10 Classification

Notebook objectives

* Implement a CNN to solve a 10-class classification problem
* Enhance the CNN's performance with Data Augmentation Techniques
* Experiment the Acceleration of GPU for Image Processing with Google Colab

[github](https://github.com/christianklausML/Notebooks/blob/master/cifar_classification.ipynb)

[google colab](https://colab.research.google.com/drive/1yruCa5zSoQrjJseyBvP3YbvGnxCGozV2?usp=sharing)

### Computer Vision: Kaggle Competition RSNA 2022 Cervical Spine Fracture Detection

Using the first notebook of the fastAI course to make a simple prediction for this competition.

[kaggle](https://www.kaggle.com/code/christianklaus/fastai-approach-is-the-cervical-spine-fractured)

## Natural Language Processing (NLP).

### TF-IDF Clustering of Publication Titles

Notebook objectives

* Preprocess text: lower, remove stopwords, tokenize
* Vectorize text (skLearn)
* Find optimal number of clusters with elbow and silhouette methods
* Reduce number of components with PCA
* Clustering and visualizing clusters in plot
* Check top keywords
* Visualize clusters in wordclouds

[gist](https://gist.github.com/christianklausML/f9580a98d02f31f8714562a89b668f96)

[google colab](https://colab.research.google.com/gist/christianklausML/f9580a98d02f31f8714562a89b668f96/tf-idf_clustering_publication_titles.ipynb#scrollTo=heYK9broSk4K)

## Machine Learning.

### Simple ARIMA Model for Non-Seasonal Time-Series Forecast

The goal of this notebook is to apply the basic concepts of time series analysis to one-dimension data

Steps:

* load and visualize the data
* train our models and make predictions

[gist](https://gist.github.com/christianklausML/445cac15aacdc88cf82f4a1f037493da)

[google colab](https://colab.research.google.com/gist/christianklausML/445cac15aacdc88cf82f4a1f037493da/time_series_arima.ipynb)

## Data Sourcing.

### Books Scraper

In this notebook I am using:

- The [Goodreads books](https://www.kaggle.com/jealousleopard/goodreadsbooks) dataset from Kaggle.
- The [Open Library Books API](https://openlibrary.org/dev/docs/api/books)

The goal is to load the data from a CSV + loop over rows to enrich each row with information such as:

- List of subjects (Science, Humor, Travel, etc.)
- The cover URL of the book
- Other information you'd find useful in the JSON API

[github](https://github.com/christianklausML/Notebooks/blob/master/books_scraper.ipynb)
