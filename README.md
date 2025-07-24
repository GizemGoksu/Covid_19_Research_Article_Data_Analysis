# Covid_19_Research_Article_Data_Analysis

This project explores the CORD-19 (COVID-19 Open Research Dataset), provided by the Allen Institute for AI via Kaggle. The dataset includes thousands of scholarly articles related to COVID-19 and other coronaviruses, aiming to support the global research community in combating the pandemic.

📁 Dataset Source
Kaggle Dataset: https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge

The dataset includes metadata and full texts of articles from sources like PubMed, WHO, and preprint servers (e.g., bioRxiv, medRxiv).

🎯 Project Goals
The main objectives of this project are:

- To explore and clean the large-scale textual data.

- To extract valuable insights using Natural Language Processing (NLP) techniques.

- To answer a specific research question by finding the most relevant scientific articles from the dataset.

🔍 Research Question
I simulated a real-world research scenario by formulating a specific question related to COVID-19 and using TF-IDF and cosine similarity to retrieve the most relevant articles from the dataset based on their titles and abstracts.

📌 Example question: "Which drugs are most effective for treating COVID-19 symptoms?"
➤ We searched through the articles and ranked them based on similarity to this question.

🧰 Tools & Libraries Used


- pandas, numpy – data manipulation

- matplotlib, seaborn – visualizations

- nltk, re, string – text preprocessing

- TfidfVectorizer, cosine_similarity – document similarity

- wordcloud – keyword visualization

📊 Key Steps
1. Data Cleaning & Preprocessing:

- Removed nulls, duplicates, and irrelevant rows

- Cleaned punctuation, stopwords, and special characters

2. TF-IDF Vectorization:

- Vectorized the titles and abstracts

3. Cosine Similarity:

- Measured similarity between research question and each article

- Returned top matching articles

4. Word Cloud Generation:

- Created visual summaries of most frequent terms

5. Exploratory Analysis:

- Checked word distributions and article metadata patterns

📌 Notes:


- Dataset is large and may require time and memory to process.

- Google drive is used for storing the dataset.
