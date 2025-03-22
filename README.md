# Extracting_and_Visualizing_Stock_Data
Extracting and Visualizing Stock Data using yfinance and Webscraping

Requirements:
  1. Install the required libraries:
     !pip install yfinance
     !pip install bs4
     !pip install nbformat
     !pip install --upgrade plotly
  2. Import the required libraries:
     import yfinance as yf
     import pandas as pd
     import requests
     from bs4 import BeautifulSoup
     import plotly.graph_objects as go
     from plotly.subplots import make_subplots
      
     import plotly.io as pio
     pio.renderers.default = "iframe"
      
     import warnings
     # Ignore all warnings
     warnings.filterwarnings("ignore", category=FutureWarning)

Define a Function that Makes a Graph
  Question 1: Use yfinance to Extract Stock Data
  Question 2: Use Webscraping to Extract Tesla Revenue Data
  Question 3: Use yfinance to Extract Stock Data
  Question 4: Use Webscraping to Extract GME Revenue Data
  Question 5: Plot Tesla Stock Graph
  Question 6: Plot GameStop Stock Graph


