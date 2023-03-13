# topic_modelling_on-_BBC_articles
Data is sourced from - D. Greene and P. Cunningham. "Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering", Proc. ICML 2006.

The courpus contains 2,225 documents from BBC's news website corresponding to stories in five topical areas (business, entertainment, politics, sport, tech) from 2004-2005.

**Topic modeling** has been done using **LSA and LDA algorithms**, after vectorizing the text in three different ways:

(1) after normal cleaning of the text corpus (punctuation removal, stopword removal, etc.),

(2) with term frequency filter,

(3) count-vectorizer.


**Observation**

After vectorizing the text using TF-IDF vector in three different ways normal cleaning,using term frequncy,part of speech as noun and using LSI/LSA and LDA algorithms for topic modeling. Top 5 words discussed in each of topic are discussed.

From the results - LDA model using normal cleaning has better keywords and relevant to each article.
