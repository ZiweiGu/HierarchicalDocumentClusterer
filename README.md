# Hierarchical-Document-Clusterer
A demo of hierarchical document clustering techniques

This project is a clustering of the top 100 places to travel in the world, based on the short text description of each. First, NLTK, the Natural Language Tookit package, was used to tokenize and stem the words in the descriptions. After cleaning the data, K-means clustering was employed and the results were printed out. Finally, hierarchical clustering generated a graph that demonstrated the internal structure of the dataset and the relationship among the 100 places.

In order for the program to run successfully, the items to be clustered need to be contained in a .txt file, with each item on a line. Similarly, the descriptions corresponding to the items should also be contained in a .txt file, with a line break (\n) for each new description. It is crucial that the two files match. For example. the first paragraph in the descriptions file should describe the first item, and the second paragraph should describe the second item, etc. 

As it turns out, this technique could be applied to many other hierarchical clustering problems related to text data as well, like clustering law documents. The text data can be as small in size as movie blurbs, or as large in size as Wikipedia articles. However, it would be best if the text descriptions for all items are of roughly the same size.
