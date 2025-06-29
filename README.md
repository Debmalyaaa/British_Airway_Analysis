# ✈️ British Airways Review Analysis Dashboard

This project provides an analytical dashboard built in **Tableau** that explores passenger reviews for **British Airways (BA)**. It combines textual and quantitative data from online customer feedback with global geographic data to generate insights into airline performance and customer sentiment.

---

## 📊 Project Overview

The Tableau dashboard helps stakeholders to:

- Analyze customer reviews across aircraft types, routes, and service levels.
- Track satisfaction metrics such as seat comfort, food & beverages, and entertainment.
- Filter and drill down by traveller type, country, and flight route.
- Identify patterns in customer dissatisfaction and potential improvement areas.

---

## 🗂️ Data Sources

### 1. `ba_reviews.csv`
Contains detailed customer reviews and ratings, with fields including:

- **author** – Reviewer name
- **date** – Review date
- **content** – Full text of the review
- **aircraft / route / seat type**
- **rating metrics** – e.g., `seat_comfort`, `cabin_staff_service`, `value_for_money`
- **trip verification** and recommendation flags

### 2. `Countries.csv`
Used to map the location of reviews to continents and regions. Key columns:

- `Country`, `Code`, `Continent`, `Region`

### 3. `British Airways.twbx`
A Tableau workbook that integrates the above datasets to generate visuals such as:

- Heatmaps of ratings by geography
- Time trends in satisfaction
- Text analysis of customer feedback
- Filters by traveller type, route, aircraft, and more

---

## 🛠️ How to Use

1. **Open the `.twbx` file** in Tableau Desktop.
2. Make sure the data sources (`ba_reviews.csv` and `Countries.csv`) are accessible from your local machine.
3. Explore the various dashboard pages:
   - Overall ratings summary
   - Geographic satisfaction analysis
   - Detailed passenger feedback
4. Use slicers and filters to refine your view (e.g., by seat class, aircraft, or month).

---

## 🔍 Key Metrics Tracked

- **Rating (Overall)**
- **Seat Comfort**
- **Cabin Staff Service**
- **Food & Beverages**
- **Entertainment**
- **Value for Money**
- **Recommendation %**
- **Verified Reviews**
- **Sentiment Highlights** (based on review content)

---
