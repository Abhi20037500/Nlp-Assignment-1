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

# lab 4

Q1: PoS Tagging Implementation
• Write a Python program to perform PoS tagging on a given sentence.

• Use nltk or spacy library for implementation.

• The program should take a sentence as input and output each word along with its
corresponding PoS tag.

• Input: "John saw the saw and decided to take it to the table."

Q2: Ambiguity Handling in PoS Tagging

• Analyze the ambiguity in PoS tagging using NLTK and SPACY

o Sentence 1: "I like candy."

o Sentence 2: "Time flies like an arrow."

Q3: p Rule-Based vs Machine Learning-Based PoS Tagging

• Compare rule-based and machine learning-based PoS tagging approaches.

• Use a dataset to test both methods.

• Rule-Based Approach: Implement a rule-based PoS tagger using transformation-based
learning (TBL).

• Machine Learning Approach: Implement an HMM (Hidden Markov Model) or CRF
(Conditional Random Field)-based PoS tagger.

• Compare accuracy and efficiency of both aproaches.

Neural Network WalkThroughand Word2Vec

Q1: Implement a Multi-Layer Perceptron (MLP) for Classification

• Create a Multi-Layer Perceptron (MLP) for binary classification.

• Use one hidden layer with ReLU activation.

• Use Softmax activation in the output layer.

• Train the model on a custom dataset (like make_moons from sklearn).

• Print the accuracy of the model

Q2: Implement Backpropagation from Scratch (Without TensorFlow/PyTorch)

• Implement a 2-layer neural network using only NumPy.

• Include forward pass and manual backpropagation.

• Update weights using gradient descent and print loss values.

Q3: Implement Word2Vec using Gensim (CBOW & Skip-gram)

• Train a Word2Vec model on a sample text dataset.

• Implement both CBOW and Skip-gram models.

• Find the most similar words to a given word.
