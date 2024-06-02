



## Project: Analysis of Ramayana Kandas

### Overview

This project involves a comprehensive analysis of five datasets representing different sections (Kandas) of the ancient Indian epic, the Ramayana. Each dataset contains content in Sanskrit and its corresponding explanation in English. The analyses performed include word frequency analysis, sentiment analysis, translation quality analysis, keyword extraction, and topic modeling. Additionally, a classification task is carried out to distinguish between short and long English explanations.

### Dataset Description

Each dataset consists of two main columns:

- **Content**: Contains the text in Sanskrit.
- **Explanation**: Contains the English translation or explanation of the corresponding Sanskrit text.

The datasets used in this project are:

- aranyakanda.csv
- ayodhyakand.csv
- balakanda.csv
- kishkindakanda.csv
- sundarakanda.csv

### Analyses Performed

#### Word Frequency Analysis

The word frequency analysis identifies the 20 most common words in both Sanskrit and English texts, providing insights into the recurring themes and terminologies.

#### Sentiment Analysis

Sentiment analysis is conducted on the English explanations to determine the polarity (positive/negative sentiment) and subjectivity (objective/subjective nature) of the texts. This helps in understanding the emotional tone conveyed in the explanations.

#### Translation Quality Analysis

Translation quality analysis compares the length of Sanskrit sentences with their English translations to evaluate consistency. Scatter plots visualize the relationship between the lengths of the original and translated texts.

#### Keyword Extraction and Topic Modeling

Keyword extraction uses TF-IDF vectorization to identify the top 20 keywords in the English explanations. Topic modeling, using Latent Dirichlet Allocation (LDA), discovers underlying topics in the text data.

### Classification Task

The classification task aims to distinguish between short and long English explanations. Various machine learning models were used, including:

- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

#### Results of the Classification Task

The classification task yielded the following results:

- **Logistic Regression**: Best hyperparameters were C: 10 and solver: lbfgs, achieving an accuracy of 0.92.
- **Naive Bayes**: Best hyperparameter was alpha: 0.1, achieving an accuracy of 0.88.
- **Support Vector Machine (SVM)**: Best hyperparameters were C: 1 and kernel: linear, achieving an accuracy of 0.89.
- **Random Forest**: Best hyperparameters were n_estimators: 100, max_depth: None, and min_samples_split: 2, achieving an accuracy of 0.91.
- **Gradient Boosting**: Best hyperparameters were n_estimators: 100, learning_rate: 0.1, and max_depth: 3, achieving an accuracy of 0.90.

### How to Run the Project

1. **Clone the Repository**: Clone the project repository to your local machine.
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install Dependencies**: Install the required Python packages.
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn textblob
    ```



### Conclusion

This project integrates classical literature with modern data analysis techniques, offering insights into the linguistic characteristics, emotional tones, translation quality, and underlying topics in the Ramayana Kandas. The classification task demonstrates the applicability of machine learning models in distinguishing between short and long English explanations.

