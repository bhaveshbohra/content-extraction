# content-extraction
Extracting HTML web content using paragraph tags and Natural language Processing:

## Wikipedia :-  Natural Language Processing
This Python script uses several popular libraries to extract and analyze the text content of a Wikipedia page on natural language processing. The script downloads the HTML content of the page, extracts the text content of each paragraph using BeautifulSoup, and then uses spaCy to identify named entities of organization type.
## Requirements
To run the script, you will need to have the following libraries installed:
 requests, beautifulsoup4, nltk, spacy 
 
You will also need to download the following NLTK resources using the nltk.download() method:
stopwords, punkt ,averaged_perceptron_tagger
## Usage
To use the script, simply run the following command in your terminal:

python wikipedia_nlp.py
