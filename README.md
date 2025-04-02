# 🏡 Predictive Analytics for Airbnb: Analyzing Pricing, Reviews & Star Ratings

This project analyzes Airbnb listings data to uncover insights on pricing trends, review patterns, and predict star ratings using machine learning models. The goal is to help hosts and platforms optimize listing performance and enhance guest satisfaction through data-driven decisions.

---

## 📌 Project Objectives

- Analyze how average listing prices vary by room type, property type, and market.
- Evaluate user engagement through average number of reviews per listing in different markets.
- Predict the star rating of a listing based on attributes such as room type, property type, price, and market using regression models.
- Recommend actionable strategies for Airbnb hosts based on insights derived.

---

## 📊 Dataset Description

The dataset includes details for each Airbnb listing:

- `room_type`
- `property_type`
- `price`
- `market`
- `number_of_reviews`
- `star_rating`

Data preprocessing involved:

- Handling missing values
- Label encoding categorical variables
- Feature selection and train-test split for modeling

---

## 🛠️ Tools & Technologies

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Techniques:** Data Cleaning, Label Encoding, EDA, Regression Modeling (Random Forest, Gradient Boosting, Linear Regression), Evaluation (MSE, R² Score)

---

## 📈 Methodology

1. **Exploratory Data Analysis (EDA)**  
   - SQL used to compute average prices and review counts by segment.
   - Visualizations for distribution of room types, property types, and pricing.

2. **Data Preparation**  
   - Encoded categorical variables using `LabelEncoder`
   - Selected relevant features for star rating prediction
   - Train-test split (80-20)

3. **Modeling**  
   - Built and evaluated three regression models:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor
   - Evaluated using Mean Squared Error (MSE) and R² Score

---

## 🔍 Results

| Model                  | R² Score | MSE     |
|------------------------|----------|---------|
| Random Forest          | 0.3415   | 0.0306  |
| Gradient Boosting      | 0.1172   | 0.0410  |
| Linear Regression      | 0.0144   | 0.0458  |

- **Random Forest** performed best, capturing ~34% variance in star ratings.

---

## 💡 Key Insights

- Listings in **Amsterdam** had higher average prices.
- **Birmingham** listings showed the highest average review engagement.
- Most common listing types were `Entire home/apt` and `Apartments`.
- Room/property type, price, and market modestly predicted star ratings.

---

## ✅ Recommendations

- **Dynamic Pricing:** Hosts can adjust prices based on market and property trends.
- **Improve Engagement:** Focus on guest satisfaction to increase reviews and ratings.
- **Optimize Listings:** Highlight high-performing features specific to markets.
- **Use ML Tools:** Predict reviews and pricing patterns using historical data.

---
