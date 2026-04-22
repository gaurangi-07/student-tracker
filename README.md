# 📊 Student Engagement Analysis System

## 📌 Overview

This project is an **AI-assisted student engagement analysis system** designed to evaluate and improve student participation in online classes. It combines **Google Forms, Google Sheets, and ChatGPT** to collect, process, and analyze engagement data using a **rule-based approach**.

The system does **not use real-time tracking or predictive machine learning models**. Instead, it demonstrates how **AI + no-code tools** can be integrated to generate meaningful insights for educators.

---

## 🎯 Key Features

* 📥 Structured engagement data collection
* 📈 Rule-based engagement scoring system
* 🧠 AI-powered sentiment analysis using ChatGPT
* ⚠️ At-risk student identification
* 📊 Trend dashboard visualization
* 📝 Weekly engagement reporting (Canva)
* 💡 AI-generated teaching suggestions

---

## 🧩 System Components

### 1. 📥 Engagement Data Collection

Post-class data is collected using **Google Forms**, including:

* Participation rating (self/instructor reported)
* Quiz score percentage
* Chat activity summary (manual input)
* Written student feedback

---

### 2. 📊 Engagement Scoring System

A **rule-based scoring system** implemented in Google Sheets.

**Weight Distribution:**

* Participation Rating → 40%
* Quiz Performance → 40%
* Feedback Sentiment → 20%

**Final Score Formula:**

```
Engagement Score = (Participation × 0.4) + (Quiz × 0.4) + (Sentiment × 0.2)
```

---

### 3. 🧑‍🎓 Student Categorization

Students are grouped based on engagement score:

* 🟢 High Engagement: ≥ 75%
* 🟡 Medium Engagement: 50% – 74%
* 🔴 Low Engagement: < 50%

---

### 4. 💬 Feedback Sentiment Analysis

* Student feedback is analyzed using **ChatGPT**
* Classified into:

  * Positive
  * Neutral
  * Negative
* Weekly sentiment trends are tracked in Google Sheets

---

### 5. ⚠️ At-Risk Student Identification

Students are flagged as **“At Risk”** if:

* Engagement score < 45%
* OR score declines for **two consecutive weeks**

> ⚠️ Note: This is **rule-based detection**, not predictive modeling.

---

### 6. 📈 Trend Dashboard (Google Sheets)

Dashboard includes:

* Class average engagement trends
* Individual student performance tracking
* Sentiment distribution charts
* Week-by-week comparison

---

### 7. 🤖 AI-Generated Educator Suggestions

ChatGPT generates teaching improvement suggestions based on:

* Declining engagement trends
* Increase in negative sentiment
* Low quiz performance

These suggestions are generated using **structured prompts + summarized data**.

---

### 8. 📝 Weekly Engagement Report

A visually structured report created using **Canva**, including:

* Class engagement average
* Student distribution by category
* At-risk students
* AI-generated suggestions

---

## 🧪 Project Demonstration Includes

* ✅ Test dataset (multiple students across multiple weeks)
* ✅ Engagement score variation analysis
* ✅ At-risk student identification
* ✅ AI-generated educator suggestions
* ✅ Canva-designed weekly reports
* ✅ Documented system limitations

---

## ⚙️ Tools & Technologies

* Google Forms (Data Collection)
* Google Sheets (Processing & Dashboard)
* ChatGPT (AI Analysis & Suggestions)
* Canva (Report Design)

---

## 🚧 Limitations

* No real-time tracking of student activity
* No predictive machine learning models
* Sentiment analysis depends on prompt quality
* Manual input required for some fields (e.g., chat activity)

---

## 🚀 Future Improvements

* Integration with LMS platforms
* Automated data collection
* Advanced predictive analytics
* Real-time engagement monitoring
* Improved NLP-based sentiment scoring

---

## 📌 Conclusion

This project demonstrates how **AI + rule-based logic + no-code tools** can be combined to create a practical and scalable **student engagement monitoring system**. It provides actionable insights for educators without requiring complex infrastructure.

---

## 👩‍💻 Author

*(Add your name here)*

---
