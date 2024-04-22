# Hotel Price Analysis:
This project aims to perform hotel price analysis by crawling data from three popular websites - Airbnb, Expedia, Hotels.com and Booking.com. The project utilizes various techniques including web crawling, data validation using regular expressions, HTML parsing, inverted indexing, frequency count, page ranking, spell checking, word completion, search frequency, and finding patterns using regular expressions.

## Features
### Web Crawler
The project includes a web crawler module that retrieves hotel price data from Airbnb, Expedia, and Booking.com websites.

### Data Validation using Regular Expressions
Regular expressions are used to validate and extract relevant information from the crawled data.

### HTML Parser
An HTML parser is employed to parse the HTML content retrieved from the websites.

### Inverted Indexing
Inverted indexing is utilized to enable quick searches without the need to go through all the files. It stores a mapping from content (words or numbers) to their locations in a set of documents.

### Frequency Count
The project provides functionality to count the frequency of words in a specific URL, allowing users to see the number of occurrences of a word.

### Page Ranking
Page ranking is implemented to measure the importance of search results based on the number of occurrences. Web pages with repeated search keywords are ranked higher. Various data structures such as sorting and heaps are used for ranking web pages.

### Spell Checking
The project includes a spell checking feature that constructs a vocabulary based on all existing words in text files. It suggests alternative word suggestions if no results are found, using the edit distance algorithm to compare the user's input with existing words from source files.

### Word Completion
Word completion functionality suggests completed words based on user input.

### Search Frequency
The project tracks and displays the word that has been searched before, along with the number of times the word has been searched.

### Finding Patterns using Regular Expressions
Regular expressions are employed to find specific patterns within the crawled data.

## Usage
Compile and Run: Compile the Java files and run the main program to initiate the hotel price analysis.

Provide Input: Input the desired search parameters such as location, dates, and other relevant criteria.

View Results: Access the analyzed hotel price data along with additional features such as frequency count, page ranking, and spell checking.
