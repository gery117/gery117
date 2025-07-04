# Welcome to My Data Analytics Portfolio 👋  

## About Me  

With six years of experience as a dedicated Project Manager, I have successfully led linguistic projects for international clients—coordinating between translators and internal teams to ensure smooth and timely execution. Currently pursuing a doctorate in International Economics, I apply advanced data analysis techniques in both my coursework and thesis research.  

To support my transition into a data analysis role, I have completed the **Google Advanced Data Analytics Certificate** and **IBM’s Databases and SQL for Data Science** course. My combined academic and professional experience has equipped me with a solid foundation in tools such as **Python, Stata, R, SQL, and Excel**, along with knowledge in **statistical modeling, regression analysis, and the fundamentals of machine learning**.  

I bring a unique blend of **analytical acumen, project management expertise, and a passion for uncovering insights through data** to any data-driven environment.  

📄 **[My CV (PDF)](link to CV)** 

---

## 📌 Repository Overview  
This repository showcases my skills, shares projects, and tracks my progress in **Data Analytics & Data Science**.  

### 📋 Table of Contents  
- [About](#about-me)  
- [Portfolio Projects](#portfolio-projects)  
  - [Python](#python)
  - [Stata](#stata)
  - [R](#r)   
  - [Tableau](#tableau)
- [Education](#education)  
- [Certificates](#certificates)  
- [Contact](#contact)  

---

## 📂 Portfolio Projects  

In this section, I list data analytics projects, briefly describing the **technology stack** and **methodologies** used.  

### **Python**  
#### 🐍 Determine the impact of marketing promotions (TV, social media, radio, and influencer) on a small business's historical sales.  
**Code:** [`Build a multiple regression marketing sales promotion.ipynb`](mutiple_reg_marketing_sales.ipynb)  
**Goal:** Determine what type of promotion contributes most to a business's historical sale.  
**Description:**  
- Analyzed a dataset representing the amount of money spent on TV, radio, and social media promotions.  
- Performed **data exploration, data cleaning, multiple linear regression model building, and model assumptions checking.  
- Visualized trends to identify key success drivers.  
**Skills:** Data cleaning, statistical analysis, data visualization.  
**Tech:** Python (Pandas, Seaborn, Matplotlib, statsmodels).  
**Results:**  
✅ High TV promotional budgets have a substantial positive influence on sales and investments in radio promotions also increases sales.

#### 🐍 Building a binary classifier (claim vs. opinion) predicitve logistic regression model for video content analysis.
**Code:** [`Build a binary classifier model and regression model to categorize claim types in video content.ipynb`](https://github.com/gery117/gery117/blob/main/binary_classifier%20_regression_model.ipynb)  
**Goal:** Build a predictive model that can determine whether a video contains a claim or offers an opinion.  
**Description:**  
- Build a predicitve logistic regression model that analyzes a dataset consisting of claims classification data and then categorizes claim types in the video content.  
- Performed **data exploration, data cleaning, logistic regression model building, and model assumptions checking.  
- Visualized trends to identify key success drivers.  
**Skills:** Data cleaning, statistical analysis, data visualization, correlation matrices, histogram plotting, confusion matrices.  
**Tech:** Python (Pandas, Seaborn, Matplotlib, sklearn).  
**Results:**  
✅ Based on the estimated model coefficients from the logistic regression, longer videos tend to be associated with higher odds of the user being verified.

#### 🐍 Developing a binary logistic regression model to predict employee attrition and inform retention strategies.
**Code:** [`Build a binary predictive logistics model to predict employee attrition.ipynb`](https://github.com/gery117/gery117/blob/main/_Salifort%20Motors%20capstone%20project%20logistic%20regression.ipynb)  
**Goal:** To develop a logisitic regression data driven tool that predicts whether an employee is at risk of leaving the company, with the goal of enabling proactive retention strategies.  
**Description:**  
- Build a predictive logistic regression model that analyzes a dataset and that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points. 
- Performed **data exploration, data cleaning, logistic regression model building, and model assumptions checking.  
- Visualized trends with box plots and scatterplots to identify key success drivers, create correlation heatmaps, create confusion matix and a classification report to show the precision, recall, accuracy and f1 score of the model.
**Skills:** Data cleaning, statistical analysis, data visualization, correlation matrices, histogram plotting, confusion matrices.  
**Tech:** Python (Pandas, Seaborn, Matplotlib, sklearn).  
**Results:**  
✅ The models and the feature importances extracted from the models confirm that employees at the company are overworked and the number of the projects that employees work on should be capped as well as increaded rewards and promotions for employees that have worked longer hours.

#### 🐍 Developing a machine learning model (Decision tree and Random forest) to predict employee attrition and inform retention strategies.
**Code:** [`Build a machine learning model to predict employee attrition.ipynb`](https://github.com/gery117/gery117/blob/main/Salifort%20Motors%20capstone%20project%20machine%20learning.ipynb)  
**Goal:** To develop a machine learning data driven tool that predicts whether an employee is at risk of leaving the company, with the goal of enabling proactive retention strategies.  
**Description:**  
- Build a Decision tree model as well as a Random forest model that analyzes a dataset and that predicts whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points.  
- Performed **data exploration, data cleaning, logistic regression model building, and model assumptions checking.  
- Visualized trends with box plots and scatterplots to identify key success drivers, create correlation heatmaps, confusion matix and decision tree splits.
- Construct a Decison tree model and a Random forest model and set up cross validated grid-search for both models, perform feature engineering to droping and creating new variables to improve on the models. 
**Skills:** Data cleaning, statistical analysis, data visualization, correlation matrices, histogram plotting, confusion matrices.  
**Tech:** Python (Numpy, Pandas, Seaborn, Matplotlib, sklearn).  
**Results:**  
✅ The models and the feature importances extracted from the models confirm that employees at the company are overworked and the number of the projects that employees work on should be capped as well as increaded rewards and promotions for employees that have worked longer hours inform employees not familiar with the overtime policies inform them about this and address the company work culture better.

#### 🐍 Doing EDA and general data cleaning and exploration for thesis research. 
**Code:** [`Data_cleaning_thesis_final.ipynb`](https://github.com/gery117/gery117/blob/main/Data_cleaning_thesis_final.ipynb)  
**Goal:** Clean, Explore and Prepare data using python as preparation for regression analysis.
**Description:**  
- Perform extensive EDA on panel data from Latin America and the Caribbean from 1990 to 2023 in 22 different nations. The study incorporates Unemployemnt, FDI, Trade, Interest rate, Wages, Education, Inflation, and Population and GDP as variables.  
- Performed data exploration and data cleaning.
- Convert columns to numeric, rename columns, find and adress missing values with interpolation forward fill and back fill, find and adress outliers using winsorization.  
- Visualized trends with box plots and scatterplots, histograms and line plots, create correlation heatmaps, adressing stationarity.  
**Skills:** Data cleaning, data visualization, correlation matrices, histogram plotting.  
**Tech:** Python (Numpy, Pandas, Seaborn, Matplotlib, sklearn, scipy, statsmodels).  
**Results:**  
✅ The data was explored, cleaned as preparation for regression analysis where different models will be used like OLS, Fixed effects and Random effects model in Stata.


### **Stata**  
#### 🎮 Analysis of the relationship between Unemployment and FDI in Latin America and the Caribbean using the OLS model
**Code:** [`Analyze the relationship between Unemployment and FDI.ipynb`](https://github.com/gery117/gery117/blob/main/How%20Unemployment%20influenced%20FDI%20portfolio%20OLS%20study.pdf)  
**Goal:** Examines how foreign direct investment (FDI) inflows relate to unemployment trends in Latin America and the Caribbean by studying labor market changes. The study examines panel data from 22 countries between 1990 and 2023 using Pooled OLS, Fixed Effects, Random Effects, and fixed effects with robust standard errors to uncover both structural patterns and individual country dynamics**  
- The study incorporates Unemployemnt, FDI, Trade, Interest rate, Wages, Education, Inflation, and Population and GDP as variables.  
- Get Descriptive statistics for all variables and plot the correlation matrix to reveal how the variables in the dataset interact with one another.
- Run regression models like the Pooled OLS model, fixed effects model and random effects model.  
- Conduct the Augmented Dickey-Fuller unit root tests to see if the variables are stationary.
- Do diagnostics tests like the F-test, Endogeneity test, The Breusch and Pagan LM test, Hausman Specification Test, VIF Multicollinearity test and Autocorrelation test.     
**Skills:** Explaining descriptive statistics, Running regression models, running diagnostics test to further explain the reasoning for running these models.  
**Tech:** Stata 18.  
**Results:**  
✅ This study’s findings reveal a slight negative impact of unemployment on FDI but demonstrate that trade openness along with wage differentials and population size produces significant positive effects.


#### 🎮 Analysis of the relationship between Trade and Economic Growth in Latin America and the Caribbean using the ARDL model  
**Code:** [`relationship between Trade and Economic Growth.pdf`](https://github.com/gery117/gery117/blob/main/Relationship%20between%20Trade%20and%20Economic%20Growth%20ARDL%20model%20portfolio%20study.pdf)  
**Goal:** Examines the possible relationship between trade and economic growth using the Autoregressive Distributed Lag (ARDL) model, utilizing three estimation techniques: Pooled Mean Group (PMG), Mean Group (MG), and Dynamic Fixed Effects (DFE)**  
- The study incorporates Trade, GDP, Interest rate, Wages, Education, FDI, Inflation, Population, unemployment as variables.  
- Get Descriptive statistics for all variables and plot the correlation matrix to reveal how the variables in the dataset interact with one another.
- Run regression models like the Pooled OLS model, mean group estimation, Pooled mean group estimation, Dynamic Fixed Effetcs.  
- Conduct the Augmented Dickey-Fuller unit root tests to see if the variables are stationary.
- Do diagnostics tests like the Panel cointegration test, Hausman Specification Test, Granger causality test.     
**Skills:** Explaining descriptive statistics, Running regression models, running diagnostics test to further explain the reasoning for running these models.  
**Tech:** Stata 18.  
**Results:**  
✅ The results suggest that trade liberalization, employment growth, and inflation control are critical for economic stability and growth in Latin America and the Caribbean. In the long run, FDI and education investments should be optimized to ensure their positive contributions to economic development.


### **R**  
#### 🎮 Analysis of the relationship between Trade and Economic Growth in Latin America and the Caribbean using the ARDL model 
**Code:** [`relationship between Trade and Economic Growth.pdf`](https://github.com/gery117/gery117/blob/main/Relationship%20between%20Trade%20and%20Economic%20Growth%20ARDL%20model%20portfolio%20study.pdf)  
**Goal:** Examines the possible relationship between trade and economic growth using the Autoregressive Distributed Lag (ARDL) model, utilizing three estimation techniques: Pooled Mean Group (PMG), Mean Group (MG), and Dynamic Fixed Effects (DFE)**  
- The study incorporates Trade, GDP, Interest rate, Wages, Education, FDI, Inflation, Population, unemployment as variables.  
- Get Descriptive statistics for all variables and plot the correlation matrix to reveal how the variables in the dataset interact with one another.
- Run regression models like the Pooled OLS model, mean group estimation, Pooled mean group estimation, Dynamic Fixed Effetcs.  
- Conduct the Augmented Dickey-Fuller unit root tests to see if the variables are stationary.
- Do diagnostics tests like the Panel cointegration test, Hausman Specification Test, Granger causality test.     
**Skills:** Explaining descriptive statistics, Running regression models, running diagnostics test to further explain the reasoning for running these models.  
**Tech:** R.  
**Results:**  
✅ The results suggest that trade liberalization, employment growth, and inflation control are critical for economic stability and growth in Latin America and the Caribbean. In the long run, FDI and education investments should be optimized to ensure their positive contributions to economic development.


### **Tableau**  
📊 [Link to Tableau Public Profile](https://public.tableau.com/app/profile/gery.krantje/vizzes)  

---

## 🎓 Education  
- **PhD in International Economics** (Currently enrolled) – [University of International Business and Economics], Sep 2019 - July 2025  
- **Master's in Business Administration** – [University of International Business and Economics], Sep 2017 - July 2018
- **Master's in International Business** – [University of International Business and Economics], Sep 2015 - July 2017

## 📜 Certificates  
- [Google Advanced Data Analytics Certificate](https://coursera.org/share/c54e6131a66a48f7f851929fbb7c5b19)
- [IBM Databases and SQL for Data Science with Python](https://coursera.org/share/7e5da9496cb659582c0640f00f5f26e1)
- [Python Data Structures](https://coursera.org/share/dbb0959355f34eba2d7f5614620cf240)
- [Using Databases with Python](https://coursera.org/share/009790c7772ef05590654b1dc9790819)
- [Using Python to Access Web Data](https://coursera.org/share/f24f02c17d8cd7f922af4e3e57064ce8)
- [Python for Everybody](https://coursera.org/share/a2d458f40bfb8acb2bc22d6f0017a75b)
- [IBM Excel Basics for Data Analysis](https://coursera.org/share/533d2d05dcd4df3661529620d416eb7e)
- [The Nuts and Bolts of Machine Learning](https://coursera.org/share/44d4d873e00ff49e56a694a2a5343ece)
- [Foundations of Data Science](https://coursera.org/share/90adcfdfbdb3111b5b6e59454bacd488)
- [Regression Analysis: Simplify Complex Data Relationships](https://coursera.org/share/85d8ea253479ec615ce6a50761ec46e4)
- [Introduction to Data Analytics](https://coursera.org/share/6e88610d5d9b4ba45ea9148ea570db3f)
- [Go Beyond the Numbers: Translate Data into Insights](https://coursera.org/share/c0916d8b7465d1768f2a84a501a22b4f)
- [The Power of Statistics](https://coursera.org/share/77f6216501cfe42e23ec9c3220ff5198)
- [Get Started with Python](https://coursera.org/share/e6dd394bfb3cb2cdc78ad85c0c81d544)
- [JavaScript Basics](https://coursera.org/share/2f592832df6b43f44d678135b23f7ba9)
- [Capstone: Retrieving, Processing, and Visualizing Data with Python](https://coursera.org/share/7929c8d5984cb1cf5761c3563002395f)
- [Programming for Everybody (Getting Started with Python)](https://coursera.org/share/a73625de41b187c023b3e63b117b3e80)
- [Google Advanced Data Analytics Capstone](https://coursera.org/share/fc34ce8d9b6b8fc860e8968bf6ca5efe)

---

## 📩 Contact  
- LinkedIn: [linkedin.com/in/geraldo-kranenburg](https://www.linkedin.com/in/geraldo-kranenburg/)  
- Email: [geraldo.kranenburg@gmail.com](mailto:geraldo.kranenburg@gmail.com)
- Wechat: Gerykranenburg 

🌟 **Let’s connect and collaborate on data-driven solutions!**  
