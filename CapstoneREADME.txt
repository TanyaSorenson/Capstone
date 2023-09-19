Exploring Gender Representation in Novels README file
Tanya Sorenson


Datasets:

My original found datasets are listed below. The ones that actually got used in the project were Books_and_genres.csv and books dataset (Amazon).csv.

Later, my combined dataset with full text and title information is named final_books.csv. This was subsequently cleaned and became final_final.csv.

After Natural Language Processing took place and the elements of interest were pulled out, the expanded dataframe with the desired elements was named final_with_character_counts.csv. This final dataset did not have full text included.

Books_and_genres.csv :   first dataset I looked at which contains full text data for Project Gutenberg books.
    It does not contain author or publication date
    origin: Kaggle https://www.kaggle.com/datasets/michaelrussell4/10000-books-and-their-genres-standardized

goodbooks 10k.csv :   another dataset which does contain author and publication date, but no full text
    origin: Kaggle https://www.kaggle.com/datasets/zygmunt/goodbooks-10k?select=books.csv 

books dataset (Amazon).csv : another dataset which contains author and publication date, but no full text
    origin: Kaggle https://www.kaggle.com/datasets/saurabhbagchi/books-dataset 


Jupyter Notebooks:
The first notebook that was used to explore the initiall datasets and do some early cleaning was Books and genres explore.ipynb.

The next notebook, where I did some test NLP processing on a single books at a time is named Capstone test Processing.ipynb. Another notebook with more test processing is named Processing.ipynb.

The notebook where I explored spaCy on a book I was already familiar with is named Pride&PrejSpacyTest.ipynb.

The final notebook which contains the actual NLP processing that I did on all of the books is named Hopefully final NLP on all docs.ipynb.