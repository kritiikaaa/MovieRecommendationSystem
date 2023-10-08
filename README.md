
# Movie Recommendation System using machine learning

Welcome to the Movie Recommendation System, a sophisticated application designed to transform your movie-watching experience. This project harnesses the power of data analysis, vectorization, and cosine similarity to provide personalized movie recommendations tailored to your tastes.

### Project Flow:

*1. Data Analysis and Preprocessing:*
   - Our journey begins with an in-depth analysis of a vast movie dataset. We examine genres, directors, actors, and user ratings, extracting valuable insights to understand the nuances of each film.

*2. Data Transformation and Vectorization:*
   - To make sense of this vast movie landscape, we transform movies into numerical vectors using advanced embedding techniques. These vectors allow us to quantify movie features, making them ripe for comparison.

*3. Cosine Similarity Matching:*
   - Here's where the magic happens. We employ cosine similarity, a powerful mathematical tool, to measure the likeness between movies. This process enables us to pinpoint movies that share remarkable similarities with your favorites.

*4. User Interaction and Input:*
   - We believe in putting you at the heart of the recommendation process. You provide input by selecting your favorite movies, giving the system valuable insights into your cinematic preferences.

*5. Personalized Recommendations:*
   - Based on your input, our system goes to work, utilizing cosine similarity to generate tailored movie recommendations. The results? A list of films that align closely with your cinematic tastes.

*6. Evaluation and Continuous Improvement:*
   - To ensure the quality of our recommendations, we employ performance metrics, including precision and recall, to assess the system's accuracy. We're committed to delivering top-notch suggestions.


## Work Flow
  Data -> Data pre-processing -> Feature Extraction -> User input-> cosine similarity algorithm -> List of movies (recommendation)
## Algorithm
### Cosine Similarity
- Cosine Similarity is primarily used in natural language processing and information retrieval to assess the similarity between two documents or vectors in a high-dimensional space.
- It calculates the cosine of the angle between two vectors, treating them as multi-dimensional vectors in a vector space.
- The result is a value between -1 and 1, where 1 indicates perfect similarity, 0 means no similarity, and -1 implies complete dissimilarity.
- Cosine similarity is often used when the magnitude or length of vectors is not crucial, and only the direction matters.
- It's particularly useful for text analysis, document clustering, and recommendation systems, where you want to find similarities between documents or items based on their content.

In practice, Cosine Similarity is applied by taking the dot product of two vectors and dividing it by the product of their magnitudes. This formula is used to calculate the Cosine Similarity score:

Cosine Similarity(A, B) = (A • B) / (||A|| * ||B||)

Where:
- A and B are the vectors being compared.
- A • B is the dot product of A and B.
- ||A|| and ||B|| are the magnitudes (or lengths) of A and B, respectively.

Higher Cosine Similarity scores indicate greater similarity, making this algorithm a valuable tool for various machine learning tasks related to similarity and recommendation.
## Technique
### Feature extraction

Feature extraction is a crucial step in data preprocessing and feature engineering, particularly in the field of machine learning and pattern recognition. It involves selecting and transforming the relevant information or attributes from raw data into a format that is suitable for machine learning algorithms. Here's what feature extraction is all about:

1. *Raw Data to Features:* In many real-world applications, you start with raw and often high-dimensional data. Feature extraction is the process of converting this data into a reduced and meaningful set of features or attributes that can be used as input to machine learning algorithms. These features should capture the essential information in the data while removing noise and irrelevant details.

2. *Dimensionality Reduction:* Feature extraction often leads to dimensionality reduction, where the number of features or variables is reduced while retaining as much relevant information as possible. Reducing dimensionality can help in improving model performance, reducing computational complexity, and mitigating the risk of overfitting.

3. *Examples of Feature Extraction Techniques:* Feature extraction techniques can vary depending on the type of data and the problem at hand. Some common techniques include Principal Component Analysis (PCA) for numerical data, Bag of Words (BoW) or TF-IDF for text data, and image feature extraction methods like Histogram of Oriented Gradients (HOG) for image data.

4. *Domain-Specific Feature Engineering:* Feature extraction may also involve domain-specific knowledge. For example, in natural language processing, features could include word frequencies, n-grams, sentiment scores, or word embeddings. In computer vision, features might encompass color histograms, texture patterns, or edge information.

5. *Importance in Machine Learning:* The quality and relevance of features can significantly impact the performance of machine learning models. Well-chosen and informative features can lead to better model accuracy and generalization, while poorly chosen features can hinder model performance.

6. *Automated Feature Selection:* In some cases, feature extraction can be automated through techniques like genetic algorithms or recursive feature elimination, which iteratively select the most important features for the task.