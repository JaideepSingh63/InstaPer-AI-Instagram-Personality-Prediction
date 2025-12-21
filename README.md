# InstaPer: Instagram Personality Prediction Using Hashtags

## 📌 Overview
InstaPer is a machine learning–based project that predicts an Instagram user’s personality by analyzing the hashtags used in their posts. The system is based on the Big Five (OCEAN) personality model—Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism—to infer personality traits from social media behavior using publicly available data.

---

## 🎯 Objectives
- Analyze Instagram hashtag usage patterns  
- Categorize hashtags into meaningful domains  
- Compute Big Five (OCEAN) personality trait scores  
- Train and evaluate multiple machine learning models  
- Predict a human-readable personality label  

---

## 🗂 Dataset Description
The dataset was collected using the Apify web scraping tool, focusing only on public Instagram content.

### Dataset Tables

### Table 1: Raw Instagram Data
- Post/Reel URL  
- Caption  
- Hashtags  
- Likes Count  
- Comments Count  
- Timestamp  

### Table 2: Hashtag Analysis Table
- Hashtag  
- Frequency  
- Category (e.g., Travel & Nature, Art & Creativity, Technology, Fitness, etc.)  
- Sentiment (Positive / Neutral / Negative using TextBlob)

### Table 3: Personality Feature Table
- Category-wise hashtag occurrence scores  
- Big Five (OCEAN) personality traits  
- Final personality label (e.g., Adventurous, Creative, Balanced)

---

## ⚙️ Feature Engineering
- Hashtags from each post are combined and cleaned  
- Category-wise counts are calculated  
- Category scores are mapped to OCEAN traits  
- OCEAN scores are normalized and used as features  

**Input Features (X):**
- Openness  
- Conscientiousness  
- Extraversion  
- Agreeableness  
- Neuroticism  

**Target Variable (y):**
- Personality Label  

---

## 🤖 Machine Learning Models
The following classifiers were trained and evaluated:

- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Extra Trees Classifier  
- Support Vector Machine (SVM)  

### Model Performance Comparison

| Model                  | Accuracy |
|------------------------|----------|
| Gradient Boosting      | 99.58%   |
| Extra Trees            | 98.06%   |
| Random Forest          | 97.09%   |
| Logistic Regression    | 96.54%   |
| SVM                    | 94.18%   |

The Gradient Boosting Classifier achieved the best performance due to its ability to capture non-linear patterns and iteratively correct prediction errors.

---

## 🛠 Tools & Technologies
- Jupyter Notebook – Development environment  
- Apify – Data scraping  
- Python Libraries:
  - pandas, numpy – Data processing
  - scikit-learn – Machine learning models
  - TextBlob – Sentiment analysis
- Canva – Presentation design  
- ChatGPT – Research and documentation support  

---

## 📈 Applications
- Personality-based digital marketing  
- Social media analytics  
- Content recommendation systems  
- Behavioral and psychological research  
- User profiling and personalization  

---

## 📚 Key Learnings
- Ethical social media data collection  
- NLP-based feature extraction from hashtags  
- Application of the Big Five personality model  
- Importance of feature engineering  
- Model comparison and evaluation  
- End-to-end machine learning pipeline development  

---

## ⚠️ Ethical Considerations
- Only publicly available data was used  
- No private or sensitive user information was collected  
- This project is intended for educational and research purposes only  

---

## 👨‍🎓 Author
Jaideep Singh  
B.Tech CSE (Data Science)

---

## 🔮 Future Scope
- Real-time personality prediction  
- Multi-modal analysis (text + images)  
- Deep learning–based personality models  
- Improved generalization and validation techniques  
