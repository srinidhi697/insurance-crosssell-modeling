# 🚗📈 Cross-Selling Vehicle Insurance: Predictive Modeling Project

This project applies machine learning to **predict which health insurance customers are most likely to purchase vehicle insurance**, enabling smarter, more personalized marketing strategies.

## 🎯 Objective
Develop a predictive model using customer demographics, vehicle information, and insurance history to identify potential cross-sell opportunities for vehicle insurance.

## 📊 Dataset
- **Rows**: 381,109
- **Features**: Age, Gender, Driving License, Vehicle Age, Vehicle Damage, Previous Insurance, Region, etc.
- **Target**: Whether a customer bought vehicle insurance

## 🔍 Key Steps
1. **Exploratory Data Analysis (EDA)** – Distribution of age, gender, vehicle age, and claims behavior
2. **Preprocessing**
   - Label Encoding of categorical variables
   - Addressing class imbalance with **SMOTE**
   - Train-Test split & Feature Scaling
3. **Modeling**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Gradient Boosting
   - **XGBoost** (Best performance: ~85% accuracy)

## 🏆 Best Model: XGBoost
- **Training Accuracy**: 85.3%
- **Testing Accuracy**: 85.1%
- **Precision**: 82% (insured), 89% (not insured)
- **Recall**: 91% (insured), 80% (not insured)

## 📌 Insights
- Customers with **older vehicles** and **prior vehicle damage** show higher interest in vehicle insurance.
- **Previous insurance holders** are less likely to repurchase.
- Region and age (30+) are strong indicators for targeted campaigns.

## 💡 Recommendations
- **Targeted Marketing**: Focus on customers with damaged/older vehicles
- **Product Bundling**: Combine auto insurance with new car packages
- **Regional Customization**: Tailor offers to high-interest regions
- **Ongoing Model Updates**: Integrate real-time data for continual improvement

---

**🚀 Tools Used**: Python, Pandas, Scikit-learn, XGBoost, SMOTE, Matplotlib, Seaborn

> This project demonstrates the power of predictive analytics in driving personalized marketing strategies and improving conversion rates in the insurance industry.
