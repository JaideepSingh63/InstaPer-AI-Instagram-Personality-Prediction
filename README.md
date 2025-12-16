# InstaPer  
## Instagram Personality Prediction Using Hashtags

---

## 📌 Overview

**InstaPer** is a machine learning–based project that predicts a user’s **personality category** using only the **hashtags** they use on Instagram.  
Hashtags are treated as **behavioral signals** that reflect user interests, lifestyle, and online expression.  
This project demonstrates how social media metadata can be transformed into structured features for personality inference using explainable machine learning techniques.

---

## 🎯 Objective

- Analyze Instagram hashtags as indicators of personality traits  
- Convert unstructured hashtag data into meaningful numerical features  
- Build and evaluate machine learning models for personality prediction  
- Create a reusable and research-oriented ML pipeline  

---

## 🧠 Problem Statement

Traditional personality prediction systems rely on long text, surveys, or image analysis.  
However, hashtags are:
- Public and intentionally chosen by users  
- Short, expressive, and topic-focused  
- Easy to process and language-independent  

**InstaPer** investigates whether **hashtags alone** are sufficient for accurate personality prediction.

---

## 🏗️ Project Workflow

Instagram Hashtags
→
Text Cleaning & Normalization
→
Hashtag-to-Category Mapping
→
Feature Engineering (Category Scores)
→
Machine Learning Models
→
Personality Prediction
---

## 📊 Dataset Description

The dataset used in this project is **self-created** and specifically designed for hashtag-based personality analysis.

### Main Columns

- `hashtags` – Raw hashtags extracted from Instagram captions  
- `category_scores` – Dictionary of category-wise hashtag counts  
- `dominant_category` – Final personality label  

### Dataset Properties

- No personal or private user information  
- Fully anonymized and ethically collected  
- Suitable for open-source sharing and research use  

---

## 🧩 Personality Categories

The system currently supports the following personality categories:

- Travel & Nature  
- Fashion & Lifestyle  
- Fitness & Health  
- Food & Cooking  
- Technology & Programming  
- Education & Learning  
- Entertainment  
- Art & Creativity  
- Business & Finance  

Each hashtag contributes to one or more category scores, forming the final feature vector.

---

## ⚙️ Technologies Used

### Programming & Data Processing
- Python  
- Pandas  
- NumPy  

### Machine Learning
- Scikit-learn  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  

### Visualization & Evaluation
- Matplotlib  
- Seaborn  

---

## 📈 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | ~98%     |
| Random Forest       | ~96%     |
| Decision Tree       | ~94%     |

High accuracy is achieved due to **domain-driven feature engineering** and **well-defined category mapping**.

---

## 🧪 Key Insights

- Hashtags strongly reflect user interests and behavioral patterns  
- Simple ML models perform exceptionally well with good features  
- Category-based aggregation improves interpretability  
- The pipeline is scalable and easy to extend  

---

## 🔮 Future Scope

- Mapping predictions to Big Five personality traits  
- Multi-label personality classification  
- Temporal personality analysis  
- Real-time prediction using live hashtag streams  
- Extension to other social media platforms  

---

## ⚖️ Ethical Considerations

- No images, private data, or personal identifiers are used  
- The system provides probabilistic predictions, not psychological diagnoses  
- Designed strictly for educational and research purposes  

---

## 🏆 Project Highlights

- Self-curated dataset  
- End-to-end machine learning pipeline  
- Explainable and interpretable approach  
- Research- and resume-ready project  

---

## 👤 Author

**Jaideep Singh**  
B.Tech CSE (Data Science)  

- GitHub: https://github.com/JaideepSingh63  
- LinkedIn: https://www.linkedin.com/in/jaideep-singh-s7/  

---

## 📄 License

This project is released for **educational and research purposes**.  
Please provide proper attribution if reused.

---
