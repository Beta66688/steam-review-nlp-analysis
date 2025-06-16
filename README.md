#  Steam Review Analysis with NLP & Machine Learning

> A data science project analyzing 20,000 Steam user reviews using NLP, topic modeling, and sentiment classification.  
>  Course: AIDM7400 Data Analysis and Visualization Studio  
>  Team: Zeng Yuting, Hu Zexin, Jiang Hanbing, Liu Kexin

---

##  Overview

This project leverages data analysis, natural language processing (NLP), and machine learning to extract insights from over **6.4 million Steam game reviews**. After preprocessing, **20,000 reviews** were sampled for in-depth analysis.

We explored **user sentiment**, identified **key discussion topics** using LDA, and trained a **Naive Bayes classifier** to predict review polarity, achieving **84.35% accuracy**.

---
##  Methods Used

- **Descriptive Analysis**: Word count, sentiment ratio, word clouds, game popularity
- **Topic Modeling**: LDA (Latent Dirichlet Allocation), TF-IDF preprocessing
- **Statistical Tests**: Point-Biserial Correlation, Chi-Square, Logistic Regression
- **Sentiment Classification**: CountVectorizer + Naive Bayes (MultinomialNB)
- **Tools**: Python, Pandas, Seaborn, Scikit-learn, Matplotlib

---

##  Key Findings

- Players are generally positive: **82.3%** of sampled reviews were favorable.
- **"Survival & Sociality"** was the most positively received topic (92.2% positive).
- **Negative reviews get more helpful votes**, indicating _silent player churn_ behavior.
- The topic **"Cost Performance & Storytelling"** had the strongest influence on sentiment.
- MultinomialNB achieved **84.35% accuracy**, outperforming GaussianNB and BernoulliNB.
