# Crumble Pakistan App Review Analysis

## Project Overview

This project analyzes customer reviews from the Crumble Pakistan mobile application on the Google Play Store to understand customer sentiment, identify recurring issues, and uncover actionable business insights.

The objective was to answer a simple question:

**What are customers actually saying about their experience with the Crumble app, and what can the business learn from it?**

This is an independent data analytics project completed using customer reviews data scraped from Google Play Store.
<img width="1471" height="1291" alt="image" src="https://github.com/user-attachments/assets/a3807ccf-1a36-470a-a487-4a60a1869ad6" />

---

## Business Problem

Customer reviews are one of the richest sources of customer feedback, but reading hundreds of reviews manually is difficult and time-consuming.

This project focuses on:

- Understanding customer sentiment
- Identifying common customer complaints
- Discovering what customers value most
- Finding opportunities to improve customer experience

---

## Dataset

| Metric | Value |
|----------|----------|
| Source | Google Play Store |
| Reviews Analyzed | 277 |
| Coverage Period | June 2023 – June 2026 |
| Analysis Date | June 19, 2026 |
| Average Rating | 3.53 / 5 |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Play Scraper

---

## Project Workflow

### 1. Data Collection
- Extracted customer reviews from the Google Play Store using Python.

### 2. Data Cleaning
- Removed unnecessary columns
- Standardized review text
- Prepared data for analysis

### 3. Sentiment Analysis
Reviews were classified into:
- Positive
- Neutral
- Negative

### 4. Topic Analysis
Negative and neutral reviews were manually reviewed and categorized into common complaint themes.

### 5. Business Recommendations
Insights were translated into practical recommendations for improving customer experience.

---

## Key Findings
<img width="1990" height="790" alt="image" src="https://github.com/user-attachments/assets/95c9faa6-8b29-462c-8bb1-93317b6dd101" />

### Customer Sentiment

| Category | Percentage |
|----------|----------|
| Positive Reviews | 58.7% |
| Neutral Reviews | 9.1% |
| Negative Reviews | 32.2% |

### Most Common Customer Complaints

| Complaint Category | Share |
|-------------------|--------|
| Delivery & Logistics | 27% |
| App Bugs & Performance | 21% |
| General Complaints | 17% |
| Payment Failures | 12% |
| Promo & Voucher Issues | 7% |
| Product Quality & Pricing | 5% |
| Cities Not Yet Covered | 4% |
| Loyalty Program Issues | 4% |
| Staff & In-Store Service | 3% |

### What Customers Love

Customers most frequently praised:

- Product taste
- Product quality
- Freshness
- Fast service
- Overall experience

### Key Insight

Customers generally love Crumble's products, particularly their taste and quality. Most dissatisfaction comes from the experience of obtaining the product rather than the product itself.

The largest opportunities for improvement lie in:

- Delivery operations
- App stability
- Payment reliability
<img width="1990" height="813" alt="image" src="https://github.com/user-attachments/assets/2027918c-190b-4b6f-a786-d340dc5ddd25" />

---

## Recommendations

### Priority 1: Improve Delivery Operations
- Reduce delivery delays
- Improve address matching
- Reduce incorrect orders
- Improve order accuracy checks

### Priority 2: Improve App Stability
- Fix OTP issues
- Reduce crashes and freezing
- Improve performance across devices

### Priority 3: Improve Payment Reliability
- Investigate failed transactions
- Improve payment gateway performance
- Simplify the payment process

### Priority 4: Engage With Customers
- Respond to customer reviews
- Address complaints publicly
- Build customer trust through active communication

### Priority 5: Protect Existing Strengths
- Maintain product quality
- Continue focusing on taste and freshness
- Leverage positive customer feedback in marketing

---

## Repository Structure

```text
├── data
│   └── Crumble_reviews_dataset.csv
│
├── notebooks
│   ├── 1_Crumble_reviews_extraction_code.ipynb
│   └── 2_Crumble_reviews_analysis_codefile.ipynb
│
├── reports
│   └── 3_Crumble_app_review_analysis_report.docx
│
└── README.md
```

---

## Report

The complete business report can be found in:

```text
reports/Crumble_app_review_analysis_report.pdf
```

---

## Author

**Noor Ul Ain Zahid**  
Business Data Analyst

- LinkedIn: www.linkedin.com/in/noor-ul-ain-zahid-588895341
- GitHub: https://github.com/NoorDataAnalyst

---

## Disclaimer

This project was conducted independently for educational and portfolio purposes using publicly available customer reviews. It is not affiliated with or commissioned by Crumble Pakistan.
