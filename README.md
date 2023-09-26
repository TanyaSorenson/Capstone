# Exploring Gender Representation in Novels

## Description
This was my final project for my BrainStation Data Science bootcamp. I used natural language processing on over a thousand public domain books to examine the gender of characters and the verbs associated with the main characters by gender. I also identified the genders of the authors.

## Python Packages
python=3.10.11

A number of packages were added to this environment. A full list can be found in the Environment.yml file; however, most of the packages were not used in the final code. Here is a list of the packages necessary to run the code:

pandas=1.5.3  
matplotlib=3.7.1  
plotly=5.9.0  
spacy=3.5.3  
gender-guesser=0.4.0

## Original Data Sources
Books_and_genres.csv :   first dataset I looked at which contains full text data for Project Gutenberg books.
    It does not contain author or publication date  
    origin: Kaggle https://www.kaggle.com/datasets/michaelrussell4/10000-books-and-their-genres-standardized

books dataset (Amazon).csv : another dataset which contains author and publication date, but no full text  
    origin: Kaggle https://www.kaggle.com/datasets/saurabhbagchi/books-dataset 

## Code Structure
Jupyter Notebooks:
The first notebook that was used to explore the initiall datasets and do some early cleaning was "Books and genres explore.ipynb".

The next notebook, where I did some test NLP processing on a single books at a time is named "Capstone test Processing.ipynb". Another notebook with more test processing is named "Processing.ipynb".

The notebook where I explored spaCy on a book I was already familiar with is named "Pride&PrejSpacyTest.ipynb".

The notebook which contains the actual NLP processing that I did on all of the books is named "Hopefully final NLP on all docs.ipynb".

The notebook where I examined the verbs associated with characters is named "Verbs Processing.ipynb".

## Results
I found that most authors were male, and that most characters were male. This character gender ratio surprisingly held true regardless of the authors’ gender. I also found that whether looking at total characters or main characters, defined as characters who were mentioned at least five times, there were roughly twice as many male characters as female characters in each book. In regards to verbs, I discovered there was not much difference between the male and female characters' verbs. 

## Future Work
In the future, I may explore the male and female characters' verbs more deeply. Perhaps examining the percentage of verbs or running a logistic regression to see which verbs are most predictive of characters' gender. I could also run a logistic regression to see if any verbs are predictive of authors' gender.

## License
MIT License
