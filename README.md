# Nlp-Assignment
nlp 
# lab 1
 Install the following Python libraries using pip:
nltk
spaCy
textblob

• Load the above libraries in a Python script or Jupyter notebook.

• Write a Python script to tokenize a simple sentence using NLTK.

• Load the English language model in spaCy and Perform POS tagging on the following
sentence.

sentence = "The quick brown fox jumps over the lazy dog."

• Write a Python function to clean text by converting it to lowercase and removing punctuation.

This week’s lab assignment is all about implementing your first language model.
You are supposed to download a huge body of text at least (10,000 words). You can download the
text from Wikipedia.

• You now must create a model that computes the probabilities of the next word based on
unigrams and bigrams.

• Assignment: Given a starting word, you now must predict the whole sentence of length 15
using the ideas of both unigrams and bigrams.

# lab 2

QI. (Within Lab). The following exercises aim to deepen your understanding of tokenization
issues in text processing tasks. Recall our class discussion on the complexities of tokenization,
including handling URLs, email IDs, hashtags, mentions, numbers, and other textual elements.
You will now explore these challenges in detail through practical examples.

1. Extracting URLs from Text
2. Identifying Email IDs
3. Detecting Hashtags
4. Finding Mentions in Text
5. Extracting Numbers
6. Identifying Punctuations
7. Validating PAN Numbers
8. Removing Repetitive Characters
9. Finding Indian Mobile Numbers
10. Extracting Words Starting with Capital Letters

Q.II (Within Lab). Write a program to calculate the edit distance between two input strings and
demonstrate the number of operations (insertions, deletions, or substitutions) required to
transform one string into another.

# lab 3

Q1: Implement Stemming Using Porter Stemmer [Lab]

• Write a Python script to apply Porter Stemmer and Lancaster Stemmer on
a given list of words.

• Compare their outputs.

Example words to test:
["running", "flies", "better", "studies", "fishing", "happiness"]

Q2: Implement Lemmatization Using WordNet and spaCy [Lab]
• Write a Python program to perform lemmatization using:

o WordNet Lemmatizer

o spaCy Lemmatizer

• Compare their outputs.

Example words to test:
["leaves", "mice", "ran", "jumping", "children", "faster"]

Q3: Apply Stemming and Lemmatization on a Large Text Dataset [Lab]

• Load a large text dataset (e.g., from nltk.corpus.gutenberg).

• Apply both stemming and lemmatization.

• Compare the word count before and after processing.

• Create a graph or visualization showing the difference in word reduction
using stemming vs. lemmatization.
