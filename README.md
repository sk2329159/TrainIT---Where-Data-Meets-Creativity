# TrainIT---Where-Data-Meets-Creativity
# ImpactX - Poverty & Economic Inequality

## GitHub Repository
https://github.com/sk2329159/TrainIT---Where-Data-Meets-Creativity

## Project Overview
Poverty and economic inequality remain significant global challenges that hinder social and economic progress. This project aims to leverage data science techniques to analyze poverty indicators, understand income disparities, and recommend policy interventions that can help bridge economic gaps. By analyzing state-wise per capita income and other socio-economic factors, we derive insights that can be used by policymakers, NGOs, and researchers to implement impactful strategies for poverty alleviation.

## Datasets Used
- **Poverty & Economic Inequality** dataset
- **State-wise Per Capita Income in India** – Reserve Bank of India (RBI)  
  [Dataset Link](https://www.kaggle.com/datasets/varunnagpalspyz/india-statewise-gdp-per-capita-geometry)
- **Dataset Features:**
  - Per capita income data across different Indian states
  - Economic indicators like employment rate, literacy rate, and inflation
  - Socio-demographic factors influencing economic disparity
  - Access to basic resources such as education, healthcare, and employment
- **Data Preprocessing:**
  - Removed missing values and handled inconsistencies
  - Normalized data for uniform comparisons
  - Feature engineering to extract key economic indicators

## Tools & Technologies Implemented
- **Programming Language:** Python
- **Libraries Used:**
  - Pandas, NumPy - Data preprocessing and manipulation
  - Matplotlib, Seaborn - Data visualization and analysis
  - Scikit-Learn - Machine learning models for predictive insights
- **Machine Learning Models Implemented:**
  - **Linear Regression:** To predict future income trends based on historical data
  - **Polynomial Regression:** For more complex trend prediction
  - **K-Means Clustering:** To categorize states based on economic similarities and disparities
- **Visualization Tools:** Matplotlib, Seaborn for creating graphical representations of income distributions and poverty trends

## Project Setup & Execution Instructions
1. **Clone the Repository:**
   ```bash
   git clone [Insert GitHub Repository Link]
   cd impactx-project
   ```

2. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Data Preprocessing & Analysis:**
   ```bash
   python data_analysis.py
   ```
   - This script cleans and processes the dataset, performing exploratory data analysis (EDA) to identify trends and patterns in economic inequality.

4. **Train & Evaluate Models:**
   ```bash
   python model_training.py
   ```
   - This step trains machine learning models to predict future poverty trends and segment regions based on economic indicators.

5. **Generate Visualizations & Insights:**
   ```bash
   python generate_reports.py
   ```
   - This generates plots and reports showcasing findings on income disparity, poverty trends, and key economic insights.

## Key Insights & Findings
- **Income Disparities:** Significant variations in per capita income exist across states, highlighting economic inequality.
- **Education vs. Poverty:** Higher literacy rates correlate with lower poverty levels, reinforcing the importance of education.
- **Employment Trends:** Regions with higher unemployment rates show greater economic instability.
- **Geographical Influence:** Certain states with lower infrastructure development have consistently lower per capita income.
- **Policy Implications:** Data-driven recommendations for improving education, employment, and economic policies to reduce poverty.

## Contribution
- **Team Name:** Foxtrot Data Hunters
- **Team Members:**
  - Swarnim Kumar (Team Leader)
  - Anuja Chakraborty
  - Shreya Bhattacharjee

## Future Scope
- **Global Dataset Integration:** Expand the project to analyze poverty on a global scale.
- **Real-time Data Monitoring:** Incorporate real-time economic indicators to provide dynamic insights.
- **Interactive Dashboard:** Develop a web-based dashboard for policymakers to visualize trends and insights.
- **Advanced ML Models:** Implement deep learning models for more accurate poverty trend predictions.

## License
This project is open-source under the MIT License.

---
For any queries, please reach out via GitHub Issues.

