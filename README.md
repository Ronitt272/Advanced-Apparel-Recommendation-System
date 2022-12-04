# Advanced-Apparel-Recommendation-System
- Implemented TF-IDF, Google’s Page Ranking Algorithm, on a sample dataset
- Wrote the pseudocode for the implementation of TF-IDF to rank a set of documents in the increasing order of relevance for a query term. 
- Performed detailed Time Complexity Analysis of the pseudocode. 

The Apparel Recommendation System was implemented on Python. 

The Advanced Apparel Recommendation System consisted of: 

1. Text based Apparel Recommendation System
2. Image based Apparel Recommendation System
 
Text based Apparel Recommendation: 

- The system functions by ranking a set of clothing (Corpus), downloaded from the Amazon website, depending on the relevance with the input query (Apparel of user’s choice). 
- The system works by calculating a TF-IDF score for each clothing present in the corpus, and then displaying the clothes in the decreasing order of relevance (More the TF-IDF score, Greater the relevance). 

Image based Apparel Recommendation: 

- performed Feature Extraction by downloading images of clothing from the Amazon website. 
- Used Convolutional Neural Networks (VGG-16 Network) to squeeze the images into a 16 X 16 matrix, and then saved the bottleneck features on those matrices. 
- The query image (user’s choice of clothing) is then similarly converted into a matrix using CNN, and the euclidian distance between the query term and each of the bottleneck feature matrices is calculated. 
- The clothes are then sorted in decreasing order of Euclidian distance to get the closest recommendations. 
