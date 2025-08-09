🚗 ML-Based Used Car Price Prediction Dashboard – Australian Market
📌 Overview

A Streamlit-based web application that predicts the fair market price of used cars in Australia based on brand, model, year, mileage, fuel type, and transmission.<br>

Designed for:

a.Car buyers → Negotiate better deals.

b.Dealerships → Set competitive yet profitable prices.

Live Demo: Streamlit App
Dataset: Kaggle – Australian Vehicle Prices

🎯 Business Problem
The Australian used car market is valued at $60B+ annually. There are many players in the used car market like carsales.com.au, ars24.com.au.<br>
Pricing the car right is crucial to ensure sales conversion. Used car prices are influenced by a bunch parameters that are internal and external<br>
-Internal (Car parameters) like the make (brand), model, fuel type, efficiency, transmission type etc., <br>
-External parameters like regional demand vs supply, fuel subsidies and seasonal trends.<br>
Without accurate pricing tools dealers could face longer inventory cycles if overpriced or loss margins if underpriced.<br>

Solution: A data-driven model providing a platform or player agnostic brand & model-specific price estimates for AU market players.

🛠 Technical Approach
1. Data Collection & Cleaning<br>
-Used open-source datasets from Carsales, Gumtree and Kaggle.<br>
-Cleaned & merged multiple sources for richer feature coverage.<br>

2. Feature Engineering<br>
-Numerical: mileage, year<br>
-Categorical: brand, model, fuel type, transmission<br>
-Derived: car age, price per kilometre<br>

3. Modelling<br>
-Baseline: Linear Regression<br>
-Improved: Lasso Regression + Random Forest Regressor (GridSearchCV optimized)<br>

4. Deployment<br>
-Interactive Streamlit UI with dropdowns & sliders<br>
-Real-time prediction output<br>

📊 Key Results
Metric	Value
-R² Score	0.82
-MAE	$1,850
-Dataset Size	45,000+ rows

Sample Prediction:
Toyota Corolla, 2018, 45,000 km, Petrol, Automatic, Sydney → $18,500

💡 Business Impact
-Dealers: Price competitively, improve turnover.
-Buyers: Negotiate with confidence.
-Analysts: Track brand & regional trends.

🖼 Sample Screenshot
<img width="522" height="715" alt="image" src="https://github.com/user-attachments/assets/d80de2ab-d77d-44f5-ad71-2fd5d9474767" />

🚀 Future Enhancements
-Compare multiple models in-app ✅
-Confidence intervals in predictions ✅
-Real-time listings scraping
-Seasonal trend adjustments
-Expansion to New Zealand market
-Batch file upload for bulk predictions

👨‍💻 Author
Gokul GS
LinkedIn | GitHub
