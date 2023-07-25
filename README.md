## Mars_data_scraping
Mars_Data_Scraping - Module 12, July 2023

##About
This project uses BeautifulSoup and Splinter to practice web scraping techniques. Specifically, scraping data from a website about Mars containing data and images as well as a table of data. Within this module, we must collect data, organize it, store it and analyze it while finishing the project with supportive visuals. 

##Table of Contents
Starter_Code
    - mars_data.csv = the final data scraped from the table on the Mars website
    - part_1_mars_news.ipynb = a jupyter notebook to scrape general data from the Mars website
    - part_2_mars_weather.ipynb = a jupyter notebook to scrape data specifically from the website's table

##Getting Started / Installation
This project is created and run via Jupyter Notebook.

The following imports are necessary to complete the project:
Part 1:
from splinter import Browser
from bs4 import BeautifulSoup as soup

Part 2:
from splinter import Browser
from bs4 import BeautifulSoup as soup
import matplotlib.pyplot as plt
import pandas as pd
import datetime as dt
from datetime import datetime
import numpy as np

##Acknowledgements
EdEx tutor, Jesse Wright, contributed to the code for building the dataframe in the part_2_mars_weather file. Specifically, how to call a list inside of a for loop to finish the dataframe.

