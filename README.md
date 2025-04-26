# E-Commerce Sentiment Analysis
## Overview:
This Jupyter Notebook project performs sentiment analysis on women's clothing e-commerce reviews. It uses a pre-trained DistilBERT model to classify review texts as positive or negative, visualizes sentiment distributions, and provides an interactive interface to filter reviews by product ID and sentiment. The project leverages the Censius-AI/ECommerce-Women-Clothing-Reviews dataset from Hugging Face.
Requirements

## To run this project, you'll need the following:

Python 3.*
Jupyter Notebook 
 * Required Python libraries:

datasets
transformers
ipywidgets
matplotlib
seaborn
pandas



## Install the dependencies using:
pip install -r requirements.txt

## Dataset
The project uses the Censius-AI/ECommerce-Women-Clothing-Reviews dataset, which is automatically downloaded from Hugging Face using the datasets library. It contains reviews with columns such as Clothing ID, Title, and Review Text. The notebook processes the Review Text for sentiment analysis.
Setup

* Clone this repository:git clone https://github.com/ocabezas95/ECommerce_Sentiment_Analysis.git


* Install the required dependencies:pip install -r requirements.txt


* Launch Jupyter Notebook:jupyter notebook


* Open the main.ipynb file in your browser.

## Usage

Open main.ipynb in Jupyter Notebook or JupyterLab.
Run the cells sequentially to:
Load and preprocess the dataset.
Perform sentiment analysis using the DistilBERT model.
Save the classified reviews to classified_reviews.csv.
Generate a confidence distribution plot (saved as confidence_distribution_by_Sentiment.png).
Use interactive dropdown widgets to filter reviews by product ID and sentiment, with a pie chart visualization of sentiment distribution.


Modify parameters (e.g., product ID or sentiment filters) in the interactive widget section to explore specific subsets of reviews.


## Notes

The notebook uses the distilbert-base-uncased-finetuned-sst-2-english model for sentiment analysis, which is automatically downloaded via the transformers library.
The interactive widgets require ipywidgets and work best in a Jupyter environment.
Ensure an internet connection to download the dataset and model during the first run.
The notebook includes basic text cleaning (e.g., removing whitespace) but can be extended for more advanced preprocessing if needed.


## Contact
For questions or contributions, contact GitHub: ocabezas95.
