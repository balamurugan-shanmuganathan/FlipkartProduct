# Review Scrapper - Flipkart.com

## Table of content
  * Demo
  * Overview
  * Technical Aspect
  * Installation
  * Run
  * Deployement on Heroku
  
### Demo
Link: https://flipkart-product-heroku.herokuapp.com/

### Overview
Webscrap is the process of extracting or scraping data from website.The data on the websites are unstructured. Web scraping helps collect these unstructured data and store it in a structured form. 

In this project, we try to scrap the reviews from **Flipkart.com** about the product that we are planning to buy. Our end goal is to build a web scraper that collects the reviews of a product from the internet.

Beautiful Soup is a Python library for pulling data out of HTML. 

### Technical Aspect
This project is dividing into two part
  1. parsing data with help of Beautifulsoup
  2. Building and hosting a Flask web app on Heroku.
  
### Installation
As always ensure you create a virtual environment for this application and install the necessary libraries from the requirements.txt file.

    $ virtualenv venv
 
    $ source venv/bin/activate
 
    $ pip install -r requirements.txt

### Run

    $ python run.py

### Deployement on Heroku

Follow the instruction given on Heroku Documentation to deploy a web app.

To run app in heroku below mentioned line should be in Procfile

    web: gunicorn app:app
