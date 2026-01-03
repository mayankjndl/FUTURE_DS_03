# 📊 College Event Feedback Analysis (NLP + Data Science)

This project analyses student feedback collected after college events such as workshops, seminars, cultural fests, and hackathons.  
It combines **numerical ratings** with **Natural Language Processing (NLP)**–based sentiment analysis to extract actionable insights that can help improve future campus events.

The goal of this project is to demonstrate how structured survey data and unstructured text feedback can be analysed together to support data-driven decision-making.

---

## 🎯 Project Objectives

- Analyse overall student satisfaction using ratings (1–5 scale)
- Identify patterns across event types and departments
- Perform sentiment analysis on textual feedback using NLP
- Detect common complaints and dissatisfaction themes
- Provide data-driven recommendations for event organisers

---

## 📂 Dataset Overview

- **Total Responses:** 1,000 student feedback entries  
- **Data Type:** Simulated Google Form–style dataset  
- **Each row represents:** One student’s feedback after attending an event  

### Dataset Columns
- `Event_Name`
- `Event_Type` (Workshop, Seminar, Cultural, Tech Fest)
- `Department`
- `Rating` (1–5)
- `Feedback_Comment` (text)
- `Would_Recommend` (Yes / No)

The dataset was designed to reflect realistic student feedback patterns, including positive, neutral, and negative responses.

---

## 🛠 Tech Stack

- **Python**
- **pandas, NumPy** – data handling
- **Matplotlib, Seaborn** – data visualisation
- **TextBlob** – sentiment analysis (NLP)
- **WordCloud** – text visualisation
- **Google Colab** – execution environment

---

## 🧹 Data Cleaning & Preparation

Before analysis, the dataset was inspected and cleaned to ensure reliability.

Key steps included:
- Verifying dataset structure and dimensions
- Checking for missing and duplicate values
- Cleaning textual feedback by:
  - Converting text to lowercase
  - Removing special characters and noise

**Data Cleaning & Preprocessing**

<img width="867" height="585" alt="Screenshot 2026-01-03 181120" src="https://github.com/user-attachments/assets/a95e8bfa-60c1-4eac-b266-4aade1d32fa2" />
<img width="857" height="378" alt="Screenshot 2026-01-03 181327" src="https://github.com/user-attachments/assets/1d0ccb0a-aa77-49a2-8b86-36fac7e7b850" />

---

## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand overall student satisfaction trends.

### Key Findings
- Rating **4** is the most frequent score, indicating general satisfaction
- Extreme negative ratings are relatively low
- Satisfaction varies across event types
- **Cultural events** consistently achieve higher average ratings

**Rating Distribution**

<img width="581" height="463" alt="image" src="https://github.com/user-attachments/assets/c3b87fb8-04ff-4177-b20d-ed56940441c6" />

**Average Rating by Event Type**

<img width="577" height="524" alt="image" src="https://github.com/user-attachments/assets/0b90cbdd-f6e5-49ea-926d-471e366a3d30" />

---

## 🧠 Sentiment Analysis (NLP)

Textual feedback was analysed using **TextBlob** to calculate sentiment polarity scores.

Each feedback comment was classified into:
- **Positive** – expresses satisfaction or appreciation
- **Neutral** – generic or emotionally weak feedback
- **Negative** – expresses dissatisfaction or complaints

Sentiment analysis provides deeper insights that numerical ratings alone cannot capture.

**Sentiment Distribution**

<img width="581" height="463" alt="image" src="https://github.com/user-attachments/assets/5ddfc401-786d-4031-baa3-c7168010acae" />

---

## 🔗 Relationship Between Ratings and Sentiment

A comparison between numerical ratings and sentiment scores was performed to validate student behaviour.

### Observations
- Higher ratings generally align with positive sentiment
- Some high ratings still show neutral sentiment due to brief or generic comments
- Sentiment adds important context behind numeric satisfaction scores

**Rating vs Sentiment**

<img width="589" height="458" alt="image" src="https://github.com/user-attachments/assets/58d26513-a8cf-4ff7-bfb2-434982971948" />

---

## ⚠️ Common Complaints in Negative Feedback

A word cloud was generated from negative feedback comments to identify recurring issues.

### Frequent Complaint Themes
- Boring or unengaging content
- Poor organisation
- Long or tiring sessions
- Overall average experience

These insights indicate that dissatisfaction is driven more by **content quality and engagement** than logistical factors.

**Common Complaints Word Cloud**

<img width="515" height="290" alt="image" src="https://github.com/user-attachments/assets/60d24268-7100-4506-a98e-287420c8c9a3" />

---

## 🧠 Key Insights

- Overall student sentiment is positive
- Cultural events receive the highest satisfaction and sentiment scores
- Engagement quality is the primary driver of negative feedback
- Ratings alone are insufficient without sentiment analysis

---

## ✅ Recommendations

- Introduce more interactive elements in workshops and seminars
- Reduce session length and improve event structure
- Use sentiment analysis regularly alongside ratings to monitor feedback trends

---

## 📄 Project Files

- `College_Event_Feedback_Analysis.ipynb` – complete analysis notebook  
- `college_event_feedback_1000_rows.csv` – dataset  
- `College Event Feedback Analysis - Report.pdf` – final report  

---

## 👤 Author

**Mayank Jindal**  
Independent Data Science Project
