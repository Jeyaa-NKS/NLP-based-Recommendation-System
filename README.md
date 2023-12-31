# NLP-based-Recommendation-System

This project involves the development of a medicine recommendation system based on user-provided medical conditions or preferences. The recommendation system uses natural language processing (NLP) techniques to match user input with medicines from a dataset. The goal is to provide users with a list of relevant medicines.

## Dataset

The dataset used for this project contains information about various medicines. It includes the following columns:

- `Medicine Name`: The name of the medicine.
- `Composition`: The composition of the medicine.
- `Uses`: The medical conditions or purposes for which the medicine is prescribed.
- `Side_effects`: Possible side effects associated with the medicine.
- `Manufacturer`: The company that manufactures the medicine.
- `Excellent Review %`: The percentage of excellent reviews for the medicine.
- `Average Review %`: The percentage of average reviews for the medicine.
- `Poor Review %`: The percentage of poor reviews for the medicine.

### Exploratory Data Analysis

- Various charts and visualizations are created, including:
  - Distribution of Excellent Review %
  - Correlation matrix heatmap
  - Bar chart for the top 5 manufacturers
  - Bar charts for the top 5 medicines by manufacturer
  - Pie chart for the distribution of medicines among the top manufacturers


### Data Preprocessing
- Text data in the `Medicine Name`, `Uses`, and `Side_effects` columns is preprocessed using the following steps:
  - Lowercasing
  - Tokenization
  - Removing punctuation and non-alphanumeric characters
  - Removing stopwords
 
## Recommendation System

## Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is used to convert the text data into numerical feature vectors.

## User Profile
- Users can provide their medical conditions or preferences as input.

## Cosine Similarity
- Cosine similarity is used to calculate the similarity between the user's profile and the medicines in the dataset.
  
## Top-N Recommendations
- The system ranks medicines based on their similarity to the user's profile and provides the top N recommendations.

## Report Generated

- A report is generated with the top 5 medicines recommended for the user's profile.
- The report includes the following information for each recommended medicine:
  - Medicine Name
  - Composition
  - Excellent Review %
  - Average Review %
  - Poor Review %
  - Cosine Similarity

## Conclusion

This medicine recommendation system leverages NLP and data analysis techniques to provide users with relevant medicine recommendations based on their medical conditions or preferences. The system is designed to assist users in making informed decisions about medicine choices.









