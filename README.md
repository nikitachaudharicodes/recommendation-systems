# recommendation-systems
a detailed study of recommendation systems and the different techniques involved


### Recommendation Systems
##Content Filtering
Uses item features and user preferences to suggest similar items.
Assumption: users will prefer items that are similar to those they have liked in the past.

#Item and User Profiles:
- Item profile: A vector representation of an item’s features (e.g., genre, author, keywords for books).
- User profile: A vector representation of user preferences based on previously interacted items. 

#Feature Engineering:
Extract and select important features from items. (eg. text descriptions, tags, categories, or metadata)
Use techniques like TF-IDF (Term Frequency - Inverse Document Frequency) for text-based items. 

#Similarity Metrics:
- Cosine Similarity: Measures the angle between two item vectors. Widely used for content-based recc.
- Euclidean Distance : Measures the distance between two vectors.
- Jaccard Similarity: Useful for categorical data (e.g., genres or tags)

#Modeling Techniques:
- Nearest Neighbor Models: Find items with the most similar feature vectors.
- Linear Classifiers (e.g., Logistic Regression): Classify items based on user preferences.
- Decision Trees and Random Forests: Capture non-linear relationships between item features and user preferences.

#Cold-Start Problem:
- For users : works well for new users once preferences are gathered.
- For items: Difficult to recommend items without enough metadata

