This program focusses on the introduction of NLP and Text Mining. In this assignment, we first start with calculating the number of tokens and unique tokens, lemmatizing the words from our dataset, and finally, finding the percentage and frequency of certain words. 

The program can be run in Jupyter Notebook or Spyder, which every is used by the user. Just select the commands and run the program to see the result.

Some of the libraries that are used are:
NLTK
	corpus - words				###correct spell checking
	stem - WordNetLemmatizer		###Lemmatization
	probabilty - FreqDist			###To calculate Frequency of the words
	metrics.distance - edit_distance 	###spellchecker

Below are the correct ways to import the libraries:
import nltk
from nltk.corpus import words
from nltk.stem import WordNetLemmatizer
from nltk import word_tokenize, pos_tag
from nltk.probability import FreqDist
from nltk.metrics.distance import edit_distance
