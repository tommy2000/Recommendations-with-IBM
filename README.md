# Recommendations-with-IBM

## Project Overview
I aim in my capstone to answer the following 2 questions:
  1- What are the top most read articles
  2- 


## Problem Statement


## Data Exploration
The following is the schema for the table:

#### user-item-interactions.csv
  - article_id - the ID number of articles - float64
  - title - the titles of articles - object
  - email - email addresses of users who read the articles - object

```python
df.head()
```
/***
|	  |article_id	|title	|email|
|0	|1430.0	|using pixiedust for fast, flexible, and easier...	|ef5f11f77ba020cd36e1105a00ab868bbdbf7fe7|
|1	|1314.0	|healthcare python streaming application demo	|083cbdfa93c8444beaa4c5f5e0f5f9198e4f9e0b|
|2	|1429.0	|use deep learning for image classification	|b96a4f2e92d8572034b1e9b28f9ac673765cd074|
|3	|1338.0	|ml optimization using cognitive assistant	|06485706b34a5c9bf2a0ecdac41daf7e7654ceb7|
|4	|1276.0	|deploy your python model as a restful api	|f01220c46fc92c6e6b161b1849de11faacd7ccb2|
***/

#### articles_community.csv
  - doc_body - content of articles - object
  - doc_description - description of articles - object
  - doc_full_name - articles full name - object
  - doc_status - articles status - object
  - article_id - the ID number of articles - float64
  

```python
df_content.head()
```
