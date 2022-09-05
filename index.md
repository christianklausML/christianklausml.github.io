# Data Science Portfolio by Christian Klaus

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

## Standalone Projects.

### Pick-up Prediction of Parcels

For our final project in the Data Science Bootcamp my team predicted the pick-up time of parcels using real world data from a dispatcher company. A big part was handling large tables, combining them and engineering features. On top we built an ML and a DL model of which we used the DL model finally because it performed a lot better. We built a solid pipeline with data loading und preprocessing steps running in python scripts. The model was deployed in the cloud and we also built a small web interface to demo the model. We were able to improve the baseline accuracy score of 0.24 to a score of 0.54 with the ML model and even 0.86 with the DL model. The Timeframe of the project was 10 full days with 3 collaborators. For version control and collaboration we used Github and for the dashboard trello.

## Deep Learning.

### Computer Vision

[Google Colab](https://colab.research.google.com/drive/1yruCa5zSoQrjJseyBvP3YbvGnxCGozV2?usp=sharing)

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

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/christianklausML/christianklausml.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
