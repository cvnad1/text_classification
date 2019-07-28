# text_classification
a new ml approach to sentiment analysis
# importing libraries
import pandas as pd
import numpy as np
from nltk.corpus import stopwords
from nltk.Stem import PorterStemmer

# reading and preprocessing data
data = pd.read_csv("file_name.csv")
