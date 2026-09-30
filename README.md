# Major_Project_Aparna_Krishnan
# The Data-Driven Social Engagement Initiative 🚀

An end-to-end Data Science Major Project focused on analyzing social media content performance, audience relatability, virality, engagement patterns, and content optimization using data-driven methods.

## 📌 Project Overview

The **Data-Driven Social Engagement Initiative** aims to understand what makes social media content more engaging and relatable by combining:

- Data analysis
- Viral metric calculation
- Natural Language Processing (NLP)
- Statistical A/B testing
- Machine Learning
- Trend analysis
- Interactive data visualization

The project demonstrates a complete Data Science workflow, from dataset preparation and exploratory analysis to model development, recommendations, and dashboard visualization.

> **Note:** The project uses project-generated prototype data rather than live Instagram/YouTube user data.

## 🎯 Objectives

The main objectives of this project are to:

- Analyze content-level engagement and performance.
- Identify topics associated with higher engagement and growth.
- Calculate a weighted Viral Coefficient.
- Analyze audience comments using NLP.
- Test content formats, hooks, and posting times using statistical methods.
- Build a Machine Learning-based content optimization recommender.
- Develop a prototype trend forecasting system.
- Create an interactive Streamlit analytics dashboard.

## 🗂️ Dataset

The project contains:

- **240 content performance records**
- **480 project-generated audience comments**
- **8 content topics**

### Content Topics

- Social Anxiety
- Academic Pressure
- Friendship
- Dating
- Self Confidence
- Family Expectations
- Loneliness
- Work Stress

### Content Attributes

The content dataset includes:

- Topic
- Content type
- Format
- Hook type
- Posting time
- Caption style
- Video length
- Reach
- Views
- Likes
- Comments
- Shares
- Saves
- Retention rate
- Follower growth

## 🔬 Project Modules

### 1. Content Performance Analysis

Content-level performance was analyzed using:

- Reach
- Views
- Likes
- Comments
- Shares
- Saves
- Retention rate
- Follower growth
- Engagement rate

### 2. Virality Prediction Engine

A weighted **Viral Coefficient** was created to give greater importance to high-value engagement actions such as shares and saves.

Viral Coefficient:

((Shares × 3) + (Saves × 2) + (Comments × 1.5) + (Likes × 0.5)) / Reach

A Viral Score was then calculated as:

Viral Score = Viral Coefficient × Retention Rate

This was used to compare content performance across different topics.

### 3. Audience Relatability Analysis

An NLP pipeline was developed to classify audience comments into:

- **Relatable**
- **Neutral**

The model uses:

- TF-IDF Vectorization
- Logistic Regression

The comment dataset and labels are project-generated for prototype analysis.

### 4. A/B Testing

Statistical experiments were performed to examine:

- Short vs Long content
- Visual vs Text hooks
- Morning vs Afternoon vs Evening posting times

The analysis includes:

- Independent t-tests
- One-way ANOVA

Statistical significance was evaluated using a **0.05 significance level**.

### 5. Content Optimization Recommender

A Machine Learning model was developed to estimate the probability that a content configuration would achieve a high Viral Score.

The recommender considers:

- Topic
- Format
- Hook type
- Posting time
- Caption style
- Video length

The resulting combinations were ranked according to predicted success probability.

### 6. Interactive Analytics Dashboard

A Streamlit dashboard was developed to visualize:

- Engagement
- Virality
- Follower growth
- Save-to-share ratio
- Audience sentiment
- Trend forecasting
- Content recommendations

The dashboard supports interactive filtering by:

- Topic
- Format
- Posting time
- Hook type

### 7. Trend Forecasting Prototype

A prototype trend score was created using internal project metrics including:

- Average engagement rate
- Average viral coefficient
- Follower growth

> **Note:** Live external hashtag and keyword trend data was not available, so this module represents an internal prototype rather than live social-media trend forecasting.

## 📊 Key Project Results

Some key prototype findings include:

- **240** content records analyzed.
- **480** audience comments analyzed.
- Average engagement rate: approximately **14.50%**.
- Total prototype follower growth: approximately **42,418**.
- **Social Anxiety** showed the highest average engagement among the analyzed topics.
- **Social Anxiety** produced the highest prototype trend score.
- NLP analysis was used to distinguish Relatable and Neutral comments.
- Statistical testing was used to evaluate potential engagement drivers.

> These findings should be treated as prototype insights because the underlying data is project-generated.

## 🛠️ Technologies Used

### Programming & Data Analysis

- Python
- Pandas
- NumPy

### Machine Learning

- Scikit-learn
- Logistic Regression
- TF-IDF
- One-Hot Encoding

### NLP

- TF-IDF Vectorization
- Text preprocessing
- Logistic Regression Classification

### Visualization

- Matplotlib
- Seaborn
- Streamlit

### Development Environment

- Google Colab
- Python

## 📁 Project Outputs

The project generates several important files, including:

- `structured_content_performance_dataset.csv`
- `cleaned_content_performance_dataset.csv`
- `cleaned_content_performance_with_virality.csv`
- `structured_user_comments_dataset.csv`
- `relatability_nlp_model.pkl`
- `tfidf_vectorizer.pkl`
- `ab_testing_results.csv`
- `content_optimization_recommendations.csv`
- `top_10_content_recommendations.csv`
- `dashboard_topic_summary.csv`
- `dashboard_sentiment_summary.csv`
- `final_content_analytics_dataset.csv`
- `trend_forecasting_results.csv`
- `final_analytics_summary.csv`
- `social_engagement_dashboard.py`

## ▶️ Running the Dashboard

Install the required libraries:

`pip install pandas numpy matplotlib seaborn scikit-learn streamlit`

Run the Streamlit dashboard:

`streamlit run social_engagement_dashboard.py`

The dashboard will open in the browser.

## ⚠️ Limitations

This project is a prototype and has several limitations:

- The performance dataset is project-generated rather than collected from live social-media APIs.
- The audience comment dataset and labels are project-generated.
- The viral coefficient weights are project-defined.
- Trend forecasting does not currently use live external hashtag or keyword data.
- Model recommendations require validation using larger real-world datasets.

## 🚀 Future Improvements

Future versions could include:

- Instagram Graph API integration
- YouTube Data API integration
- Automated scheduled data collection
- Database integration
- Larger real-world datasets
- Multilingual NLP
- More detailed emotion classification
- Live hashtag and keyword trend analysis
- Time-series forecasting
- Cloud deployment of the Streamlit dashboard

## 🔺 Acknowledgement

This project was completed as part of the **UNLOX Data Science Internship journey**.
