# Hi, I'm Humphrey :)  
_Master's in Business Analytics @ UT Austin • Philosophy and Public Affairs @ Claremont McKenna_

---

<!-- UT Austin Section -->
<p align="left">
  <img src="images/McCombs_Logo.png" width="240" height="240" alt="UT Austin / McCombs Logo" />
</p>
<p align="left">
  <strong>Master's in Business Analytics</strong>
</p>

### Data Projects

<table>
<thead>
<tr>
<th width="30%"><strong>Project</strong></th>
<th width="70%"><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/UTMcCombsMSBA/tree/main/Data/AustinHousePricesPrediction">Austin House Price Prediction</a></strong></td>
<td>
- Predicted Austin housing prices by <strong>engineering 14 features</strong> (age, sqft_ratio, bath_bed_weighted, lot_category, interaction terms) with <strong>log transformations</strong> on price and square footage to reduce skewness, treating zipcode and amenities as categorical factors, and handling unseen holdout zipcodes by replacing with the most common training zipcode.
<br><br>
- Compared <strong>five models</strong> using <strong>5-fold cross-validation</strong> on log-transformed prices: Bagging, Random Forest, XGBoost, BART, and Pruned Regression Tree. Selected <strong>Bagging as final model</strong> for its <strong>lowest RMSE</strong> and resistance to overfitting through ensemble averaging while maintaining low bias.
<br><br>
- <strong>Tech Stack:</strong> R (tidyverse, rpart, randomForest, BART, xgboost, tidymodels, Metrics)
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/UTMcCombsMSBA/tree/main/Data/CreditCardFraudPrediction">Credit Card Fraud Prediction</a></strong></td>
<td>
- Built fraud detection models on <strong>imbalanced Kaggle dataset (555K transactions, 99.6% non-fraud)</strong> by <strong>resampling to 78.6% non-fraud</strong> for training, engineering features including time-of-day indicators, distance calculations, target-encoded merchants/categories, and removing highly correlated predictors (lat/long) identified through correlation heatmap analysis.
<br><br>
- Compared <strong>four classification models</strong> on 80/20 train-test split: <strong>Classification Tree achieved best performance (93% recall, 90% precision, 96% accuracy)</strong> using entropy criterion and max depth of 10, with <strong>transaction amount dominating feature importance (72%)</strong> followed by gas (6%) and groceries (2%) categories, outperforming Logistic Regression, Naïve Bayes, and KNN.
<br><br>
- <strong>Tech Stack:</strong> pandas, matplotlib, scikit-learn
</td>
</tr>
</tbody>
</table>

### Finance Projects

<table>
<thead>
<tr>
<th width="30%"><strong>Project</strong></th>
<th width="70%"><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/UTMcCombsMSBA/tree/main/Finance/ConstructingCustomEquityIndexes">Constructing Custom Equity Indexes</a></strong></td>
<td>
- Built <strong>three custom stock indexes</strong> (equal-weighted, value-weighted, price-weighted) from <strong>top 100 stocks</strong> by market cap using <strong>CRSP data (2015-2024)</strong>, incorporating <strong>delisting returns</strong> to avoid survivorship bias and implementing <strong>monthly reconstitution</strong> with strict t-1 information to prevent look-ahead bias.
<br><br>
- Compared custom indexes against <strong>SPY, IWM, and QQQ</strong> using <strong>correlation analysis</strong> and log returns, computed <strong>HHI scores</strong> for sector diversification analysis, and tested robustness across different market conditions by resetting indexes during 2020, 2022, and 2023 periods.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, wrds, scipy, seaborn
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/UTMcCombsMSBA/tree/main/Finance/MinimumVariancePortfolioOptimization">Minimum Variance Portfolio Optimization</a></strong></td>
<td>
- Optimized <strong>Global Minimum Variance portfolios</strong> comparing <strong>sample covariance vs. Ledoit-Wolf shrinkage</strong> methods across <strong>rolling backtesting periods (4-60 months)</strong>, with interactive stock selection and user-defined weight constraints validated through coverage checks for data quality.
<br><br>
- Implemented <strong>quadratic optimization</strong> using <strong>CVXPY (OSQP solver)</strong> with enforced covariance matrix symmetry, demonstrating <strong>Ledoit-Wolf's superior out-of-sample performance</strong> through analysis of cumulative returns, portfolio variance, weight stability, and monthly turnover metrics.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, wrds, scipy, seaborn, scikit-learn, cvxpy
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/UTMcCombsMSBA/tree/main/Finance/TestingAssetPricingModels">Testing Asset Pricing Models</a></strong></td>
<td>
- Tested <strong>CAPM and Fama-French 3-Factor models</strong> on <strong>25 size/book-to-market portfolios (1990-2024)</strong> using <strong>time-series regressions</strong> to estimate alphas and betas, <strong>GRS F-tests</strong> to jointly test alpha significance, and <strong>Fama-MacBeth cross-sectional regressions</strong> with Shanken corrections to measure factor risk premia.
<br><br>
- Found <strong>FF3F explained 94% of portfolio variance</strong> (vs. 70% for CAPM) with lower average alpha, though only market risk factor achieved statistical significance; <strong>high book-to-market portfolios showed 42% higher mean returns</strong>, with small-cap portfolios exhibiting greater variance and lower model fit.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, statsmodels, scipy
</td>
</tr>
</tbody>
</table>

---

<!-- MIT Section -->
<p align="left">
  <img src="images/MIT_Logo.png" width="150" height="150" alt="MIT Logo" />
</p>
<p align="left">
  <strong>Applied Data Science Program</strong>
</p>

<table>
<thead>
<tr>
<th width="30%"><strong>Project</strong></th>
<th width="70%"><strong>Description</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/MIT-Applied-Data-Science-Program/tree/main/Capstone">Capstone Project</a></strong></td>
<td>
- Applied various data segmentation techniques to classify customers and evaluated performance of techniques using <strong>silhouette scores</strong> and detailed cluster profiles.
<br><br>
- Designed and presented a professional presentation summarizing analytical processes, key findings, and practical business recommendations for stakeholders.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, seaborn, scikit-learn
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/MIT-Applied-Data-Science-Program/tree/main/BankCustomerSegmentation">Bank Customer Segmentation</a></strong></td>
<td>
- Utilized <strong>clustering algorithms</strong> such as <strong>K-Means, K-Medoids, and Gaussian Mixture Models</strong> on scaled datasets to segment customer populations.
<br><br>
- Evaluated clustering results by plotting <strong>SSE against cluster count</strong> to create and analyze <strong>elbow plots</strong> for determining optimal clustering solutions.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, seaborn, scikit-learn
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/MIT-Applied-Data-Science-Program/tree/main/CarDealership">Car Dealership Dimension Reduction</a></strong></td>
<td>
- Preprocessed raw data and applied <strong>dimensionality reduction techniques</strong>, including <strong>t-SNE and PCA</strong>, to effectively segment dealership customers.
<br><br>
- Conducted comprehensive variable analysis for each segment to uncover key behavioral and demographic characteristics.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, seaborn, scikit-learn
</td>
</tr>
<tr>
<td><strong><a href="https://github.com/humphreyhhui/MIT-Applied-Data-Science-Program/tree/main/Foodhub">Foodhub EDA</a></strong></td>
<td>
- Created <strong>univariate and bivariate visualizations</strong> using Matplotlib and Seaborn to identify trends and patterns in customer behavior.
<br><br>
- Conducted in-depth analysis of data insights and presented <strong>actionable recommendations</strong> to optimize business operations and customer satisfaction.
<br><br>
- <strong>Tech Stack:</strong> pandas, numpy, matplotlib, seaborn
</td>
</tr>
</tbody>
</table>
