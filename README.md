# Collocationn or Co-occurance?

The goal here is to determine whether a bigram represents a collocation or is merely a chance term co-occurrence.

The null hypothesis used for this task is that there is no association between words (the words simply co-occur by chance).
- First, we extract all bigrams from a document corpus using either NLP libraries or custom functions. 
- Next, we implement a statistical test in a statistical programming language or library you are comfortable working in to calculate the probability
that the null hypothesis is true (i.e., the word is not a collocation) for each bigram in the list of bigrams. 
