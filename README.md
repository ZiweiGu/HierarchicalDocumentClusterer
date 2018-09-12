# Hierarchical-Document-Clusterer
A demo of hierarchical document clustering techniques

This project is about clustering the top 100 places to travel in to world based on the short text description of each. First, NLTK, the Natural Language Tookit package, was used to tokenize and stem the words in the descriptions. After cleaning the data, K-means clustering was employed and the results were printed out. Finally, hierarchical clustering generated a graph that demonstrated the internal structure of the dataset and the relationship among the 100 places.

In fact, this technique could be applied to many other hierarchical clustering problems related to text data, like clustering law documents. The text data can be as small in size as movie blurbs, or as large in size as Wikipedia articles. However, it would be best if the text description for each item is of roughly the same size. 
