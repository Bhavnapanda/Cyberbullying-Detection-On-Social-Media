Cyberbullying Detection on Social Media

📌 Project Overview

Cyberbullying has become a growing concern with the increasing use of social media platforms. This project aims to identify toxic, offensive and harmful text using Natural Language Processing (NLP) and Machine Learning techniques.

The system analyses text data, performs preprocessing and classifies content using machine learning algorithms to help identify potentially harmful online communication.

🎯 Objectives

- Detect toxic and non-toxic text.
- Identify potentially harmful online comments.
- Perform text preprocessing and cleaning.
- Extract meaningful textual features using TF-IDF.
- Train and evaluate machine learning classification models.

🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

📂 Dataset Sources

The project references the following publicly available datasets:

1. Jigsaw Toxic Comment Classification Dataset

Source: Kaggle

https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

This dataset contains Wikipedia comments labelled across multiple toxicity categories, including toxic, severe toxic, obscene, threat, insult and identity hate.

2. Twitter Hate Speech Dataset

Source: Kaggle

https://www.kaggle.com/datasets/hdsmrd/twitter-hate-speech-dataset

This dataset contains Twitter text samples used for hate speech detection and classification.

Note: Dataset files are not included in this repository. Please obtain them from their respective sources and follow the applicable terms and usage conditions.

⚙️ Methodology

The project follows these major steps:

1. Data Collection – Obtaining labelled text datasets.
2. Text Preprocessing – Cleaning and preparing textual data.
3. Tokenization – Splitting text into individual words or tokens.
4. Stop-word Removal – Removing commonly occurring words.
5. Feature Extraction – Converting text into numerical features using TF-IDF.
6. Model Training – Training machine learning classification algorithms.
7. Model Evaluation – Evaluating model performance using appropriate metrics.

🤖 Machine Learning Algorithms

The following algorithms were implemented and evaluated:

- Logistic Regression
- Multinomial Naive Bayes

📊 Project Implementation

The implementation is available in the Jupyter Notebook:

"Code.ipynb"

It contains the project code, text preprocessing steps, feature extraction and machine learning model implementation.

🚀 How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Download the required datasets from the sources mentioned above.
4. Place the dataset files in the appropriate project directory.
5. Open "Code.ipynb" using Jupyter Notebook or Google Colab.
6. Execute the notebook cells to run the implementation.

📁 Repository Structure

Cyberbullying-Detection-On-Social-Media/
│
├── Code.ipynb
├── README.md
└── .gitignore

🔮 Future Enhancements

- Integrating deep learning models for improved classification.
- Extending detection capabilities to multiple languages.
- Developing a real-time cyberbullying detection system.
- Integrating the model into a web-based application.

📌 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to analyse social media text and identify potentially harmful content. It explores text preprocessing, feature extraction and classification techniques to contribute towards safer online communication.
