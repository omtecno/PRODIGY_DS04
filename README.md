# PRODIGY_DS_04: Social Media Sentiment Analysis – Twitter Brand Tweets

## 🎯 Project Overview
A comprehensive **Sentiment Analysis project** performed on **74,000+ social media tweets** to uncover public opinion patterns, validate pre-labeled sentiments, and visualize sentiment distributions across brands and topics using Python.

This project focuses on:
- Data Cleaning & Preprocessing
- Sentiment Distribution Analysis
- Brand-Specific Insights (Microsoft Example)
- Visualization of Social Media Trends

---

## 📊 Dataset Information
**Source:** Social Media Twitter Training Dataset  
**Total Records:** 74,682 tweets  
**Cleaned Records:** 71,656 tweets  
**Features:**
- `ID` – Unique tweet identifier
- `Entity` – Brand / Topic
- `Sentiments` – Positive / Negative / Neutral / Irrelevant
- `Contest` – Tweet content

**Engineered Steps:**
- Null removal  
- Duplicate removal  
- Brand filtering  
- Sentiment counting  

---

## 🛠️ Tools & Technologies
**Python 3.x** | **Pandas** | **TextBlob** | **Matplotlib** | **Jupyter Notebook** | **NumPy (Optional)**

---

## 📋 Methodology

### 1. Data Loading & Structure Identification
- Loaded dataset using **Pandas**
- Identified 4 main columns
- Verified dataset size and structure
- Initial Tweets: **74,682**

---

### 2. Data Cleaning Pipeline
**Process Flow:**  
Raw Data → Remove Nulls → Remove Duplicates → Structured Dataset

- Removed 686 null tweet rows
- Removed 2,340 duplicate rows
- Final dataset: **71,656 meaningful tweets**

---

### 3. Sentiment Distribution Analysis
- Counted sentiment labels
- Compared Positive vs Negative vs Neutral vs Irrelevant
- Observed higher negative sentiment overall

| Sentiment | Count |
|---------|-------|
| Negative | 21,698 |
| Positive | 19,713 |
| Neutral | 17,708 |
| Irrelevant | 12,537 |

---

### 4. Brand-Specific Sentiment (Microsoft Example)
Filtered tweets containing **“Microsoft”** keyword to analyze targeted brand perception.

| Sentiment | Count |
|---------|-------|
| Neutral | 816 |
| Negative | 748 |
| Positive | 573 |
| Irrelevant | 167 |

---

## 📈 Visualization Suite

### Charts Generated
| File / Chart | Type | Insight |
|------------|------|---------|
| sentiment_bar.png | Bar Chart | Overall sentiment distribution |
| brand_pie.png | Pie Chart | Microsoft sentiment share |
| dataset_shape.png | Info Chart | Dataset cleaning impact |

---

## 🔍 Key Findings
- **Negative sentiment** slightly exceeds positive overall.
- **Neutral tweets** represent a significant portion.
- **Microsoft brand sentiment** is mostly neutral.
- Dataset cleaning improved accuracy and reduced noise.
- Social media opinions are mixed but balanced.

---

## 💡 Actionable Insights
- **Brand Monitoring:** Track negative sentiment spikes.
- **Marketing Strategy:** Convert neutral audience to positive.
- **Product Feedback:** Identify recurring complaints.
- **Scalability:** Handles 70k+ tweets efficiently.
- **Data Quality:** Cleaning significantly impacts insights.

---

## 🚀 How to Replicate

### Prerequisites (Bash)
```bash
pip install pandas textblob matplotlib jupyter
python -m textblob.download_corpora
GITHUB - https://github.com/omtecno/PRODIGY_DS04
