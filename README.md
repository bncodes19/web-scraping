# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

## Dependencies
This project requires a few libraries that must be downloaded. These are: **beautifulsoup4, html5lib, matplotlib spacy, spacytextblob, and requests**

Store these libraries in the requirements.txt file in the project repository:
```
beautifulsoup4
html5lib
requests
spacy
spacytextblob
matplotlib
```

Next, install the packages in the terminal with:
```
python3 -m pip install -r requirements.text
```
Then freeze the requirements.txt file:
```
python3 -m pip freeze > requirements.txt
```
An additional step is required after installing these libraries to download a model from spacy. This command can be run in the terminal:
```
python3 -m spacy download en_core_web_sm
```