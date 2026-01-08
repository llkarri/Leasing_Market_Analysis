# 🏢 Student Housing Market Analysis: Strategic Insights for UIUC

## 📌 Executive Summary
**Objective:** Determine the key success factors for a new property management company entering the University of Illinois (UIUC) market.
**Scope:** Analyzed **10,000+ Google Reviews** across three major university towns (UIUC, Penn State, BYU) using NLP and Sentiment Analysis.
**Tools:** Python, Pandas, Plotly, Natural Language Processing (Spacy/DistilBERT data).

## 📊 Key Findings
1.  **Operations > Amenities:** Maintenance reliability is discussed **6x more often** than pools or clubhouses. It is the "Core Product" of student housing.
2.  **The "Speed Premium":** Owners who respond to reviews within **24 hours** see a **0.5-star premium** in ratings compared to slower peers. Currently, **41%** of reviews are ignored.
3.  **The "Toxic" Baseline:** "Water Leaks" and "Unreturned Deposits" are universal dealbreakers (90% Negative Sentiment) across all markets.
4.  **Market Comparison:** UIUC is a high-performing market (**3.74 Stars**) compared to distressed markets like BYU (**3.15 Stars**).

## 🔍 Analysis Highlights

### 1. What Drives Tenant Sentiment?
Analyzed sentiment polarity for 15 key topics. 
*   **Result:** Lifestyle amenities like "Gyms" and "Tours" drive positive sentiment, while financial friction points like "Deposits" and "Rent" drive negative sentiment.

### 2. The Impact of Speed
Measured the correlation between response time and star rating. 
*   **Result:** Fast responses (<24 hours) correlate with a 3.8-star average. Responses taking longer than a month drop the average to 3.2 stars.

### 3. Strategic Priority Matrix
Identified "Fix vs. Market" priorities for the UIUC market.
*   **Top Priority (Fix):** Security Deposits and Cleaning (Lowest Rated).
*   **Top Priority (Market):** Gyms and Leasing Tours (Highest Rated).

## 🛠️ Methodology
1.  **Data Extraction:** Processed raw CSV data containing business info, reviews, and pre-computed token/sentiment data.
2.  **Data Cleaning:** Merged datasets, handled missing values, and parsed datetime objects for time-series analysis.
3.  **Feature Engineering:**
    *   Calculated `Response Time Delta` (Review Date vs. Owner Reply Date).
    *   Derived `Review Length` to analyze the psychology of dissatisfaction.
4.  **Visualization:** Built interactive dashboards using **Plotly Express** to uncover trends.

## 🚀 Strategic Recommendation
To succeed at UIUC, a new entrant must:
*   **Automate Deposits:** Eliminate the #1 source of friction (1.67 Stars).
*   **Response SLA:** Enforce a strict 24-hour response policy to capture the speed premium.
*   **Marketing:** Leverage UIUC's strong reputation for Tours (4.1 Stars) to build trust.

---
*Author: Lalitha Lahari Karri*
*Connect with me on (https://www.linkedin.com/in/lalithalaharikarri/)*
