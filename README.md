# Book of Trump
The Book of Trump was a team project for BYU Economic's Applied Machine Learning Class (213R) where we used Trump tweets 
and verses from the Bible to create a bot which would combine the two and use deep learning methods such as LSTM and produce
its own (non-blasphemic) "verses". File expanations are below.

#### Webscraping_Bible_Functions.ipynb

A webscraper which takes the raw script from the Gutenburg project and transforms it to a usable form, taking out any verses  
with words or names that could be considered blasphemic if used in this context (e.g. "Lord" or "Christ")

#### Word_Cloud_Function-2.ipynb

Creates a word cloud in a given shape given a .txt file and .png file.

#### Book of Trump Predictions.ipynb	
Deep learning models which combine the new Trump tweets and Bible verses to create verses from the "Book of Trump" (you feed
it one word and it produces the verse). 

#### pres_v8.pptx

PowerPoint which was presented to the applied machine learning class as well as to the heads of various local data science corporations. 
