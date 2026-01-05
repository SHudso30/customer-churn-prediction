# Customer Churn Prediction: Machine Learning for Retention

## Project Overview
This project uses machine learning to predict customer churn for a telecommunications company, enabling proactive retention strategies. With a 26.5% churn rate costing $1.67 million annually, identifying at-risk customers is critical for business success.

## Business Problem
**The Challenge:** 1 in 4 customers are leaving, resulting in significant revenue loss.

**The Solution:** Build a predictive model to identify customers likely to churn before they leave, enabling targeted retention campaigns.

**The Impact:** Preventing just 10% of churn would save $167,000 per year.

## Dataset
- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Size:** 7,043 customers with 21 features
- **Target Variable:** Churn (Yes/No)
- **Features Include:** Demographics, services, contract details, billing information

## Key Findings

### 1. Contract Type is the Biggest Factor
- **Month-to-month contracts:** 42.7% churn rate
- **One-year contracts:** 11.3% churn rate
- **Two-year contracts:** 2.8% churn rate

💡 **Insight:** Long-term contracts drastically reduce churn risk.

### 2. New Customers Are Vulnerable
- Most churn occurs within the first 12 months
- Early engagement is critical for retention

### 3. Service Gaps Drive Churn
- Customers without tech support churn at higher rates
- Fiber optic customers without security services are high risk
- Service bundling could improve retention

### 4. Financial Impact
- Average churned customer: $74.44/month
- Monthly revenue loss: $139,130
- Annual revenue loss: $1,669,570
- **High-value customers are leaving**

## Machine Learning Model

### Model Performance
- **Algorithm:** Random Forest Classifier
- ** Accuracy:** 78.7%
- **Precision:** High accuracy in identifying churners
- **ROC-AUC Score:** 0.85+ (strong predictive power)

### Model Interpretation
The model successfully identifies at-risk customers by analyzing:
- Contract type and tenure
- Service subscriptions (tech support, security)
- Payment methods
- Monthly and total charges

### What the Model Predicts
- Can identify customers likely to churn with 79% accuracy
- Enables targeting of retention campaigns to high-risk customers
- Reduces wasted marketing spend on loyal customers

## Visualizations

The project includes compelling data visualizations:
1. **Churn distribution** by customer segments
2. **Contract type analysis** showing dramatic differences in retention
3. **Tenure patterns** revealing critical early months
4. **Revenue impact** demonstrating business cost of churn
5. **Confusion matrix** showing model performance
6. **Feature importance** highlighting key churn drivers

## Business Recommendations

### Immediate Actions (0-3 months)
1. **Early intervention program** for customers in months 0-12
2. **Proactive outreach** to month-to-month contract holders
3. **Service bundle promotions** emphasizing tech support and security

### Short-term Strategy (3-6 months)
1. **Contract upgrade incentives:** Discounts for switching to annual/two-year contracts
2. **Customer success program:** Dedicated support for new customers
3. **Targeted retention offers:** Based on model predictions

### Long-term Strategy (6-12 months)
1. **Predictive retention system:** Automated alerts for at-risk customers
2. **Customer Journey optimization:** Address pain poinnts in first year
3. **Value-added services:** Develop retention-focused product bundles

### Expected ROI
- **10% churn reduction:** $166.957 saved annually
- **20% churn reduction:** $333,914 saved annually
- **Model enables precise targeting, **maximizing retention spend efficiency

## Technical Details

### Tools & Technologies
- **Python 3.x**
- **Libraries:**
  - pandas - Data manipulation
  - NumPy - Numerical computing
  - scikit-learn - Machine learning
  - matplotlib & seaborn - Data visualization
- **Platform:** Google Colab
- **Version Control:** Github

## How to Use This Project

### View the Analysis
1. Open `customer_churn_prediction.ipynb` in Google Colab
2. Review visualizations and insights
3. Examine model performance metrics

### Reproduce the Results
1. Download the Telco Customer Churn dataset from Kaggle
2. Open notebook in Google Colab
3. Upload dataset when prompted
4. Run all cells in order

### Apply to Your Data
1. Replace dataset with your customer data
2. Adjust feature names as needed
3. Retrain model on your data
4. Generate predictions for your customers

## Key Takeaways for Non-Technical Audiences

**What we learned:**
- Month-to-month customers are 15x more likely to churn than two-year contract customers
- The first year is critical - most churn happens early
- Customers without support services leave at higher rates

**What we built:**
- A tool that predicts which customers will leave with 79% accuracy
- Enables targeting retention efforts where they matter most

**What it means for business:**
- Stop revenue bleeding from preventable churn
- Focus limited marketing budget on high-risk customers
- Potential savings of $167K+ per year with modest improvements

## Future Enhancements
- Implement real-time churn scoring system
- A/B test retention campaign effectiveness
- Develop customer lifetime value predictions
- Create interactive dashboard for stakeholders
- Experiment with advanced algorithms (XGBoost, Neural Networks)

## Author
[Your Name]  
Data Science Student | University of Pheonix  
https://www.linkedin.com/in/sara-h-4301502ab/ | https://github.com/SHudso30

## Acknowledgments
- Dataset: IBM Sample Data Sets (via Kaggle)
- Inspired by real-world telecom retention challenges

**This project demonstrates:**
- End-to-end machine learning workflow
- Business problem solving with data
- Clear communication of technical results
- Actionable recommendations from analysis
