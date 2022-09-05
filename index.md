# Data Science Portfolio by Christian Klaus

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

## Standalone Projects.

### Pick-up Prediction of Parcels

For our final project in the Data Science Bootcamp my team predicted the pick-up time of parcels using real world data from a dispatcher company. A big part was handling large tables, combining them and engineering features. On top we built an ML and a DL model of which we used the DL model finally because it performed a lot better. We built a solid pipeline with data loading und preprocessing steps running in python scripts. The model was deployed in the cloud and we also built a small web interface to demo the model. We were able to improve the baseline accuracy score of 0.24 to a score of 0.54 with the ML model and even 0.86 with the DL model. The Timeframe of the project was 10 full days with 3 collaborators. For version control and collaboration we used Github and for the dashboard trello.

## Deep Learning.

### Computer Vision

Notebook objectives

* Implement a CNN to solve a 10-class classification problem
* Enhance the CNN's performance with Data Augmentation Techniques
* Experiment the Acceleration of GPU for Image Processing with Google Colab

[github](https://github.com/christianklausML/Notebooks/blob/master/cifar_classification.ipynb)

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
