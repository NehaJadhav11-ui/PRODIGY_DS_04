Reddit Comment Sentiment Analysis - Intern Task 4

This project is part of the Prodigy Infotech Internship (Task 4). The goal is to analyze Reddit comment sentiment using the VADER sentiment analyzer and compare it with pre-labeled sentiment categories.

Dataset

Dataset used: Reddit_Data.csv  
Source: [Public Reddit Comment Dataset] (local CSV file)  
Contains:
- clean_comment: The text of the Reddit comment
- category: Sentiment label (1: Positive, 0: Neutral, -1: Negative)

Task Overview

- Loaded and explored the dataset
- Handled missing values and cleaned the text
- Used VADER SentimentIntensityAnalyzer to assign sentiment scores
- Mapped scores to sentiment labels: Positive, Neutral, Negative
- Compared VADER sentiment predictions with original labels
- Visualized sentiment distribution and confusion matrix

Technologies Used

- Python
- pandas, seaborn, matplotlib
- nltk (VADER)
- scikit-learn

How to Run

1. Clone the repository:
   git clone https://github.com/yourusername/intern-task-4.git
   cd intern-task-4

2. Place `Reddit_Data.csv` in the project directory  
   (Used file path in notebook: C:/Users/hp/Downloads/Reddit_Data.csv)

3. Open `Intern_task_4.ipynb` in Jupyter or Google Colab and run all cells

License

This project is licensed under the MIT License.

Contact

For questions or feedback, contact me via email or LinkedIn.
