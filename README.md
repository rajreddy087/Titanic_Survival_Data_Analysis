**Titanic Survival Analysis using Python**

Titanic dataset analysis to uncover survival patterns based on class, gender, age, and other factors.

**Overview**

This project explores the Titanic dataset to identify key factors influencing passenger survival. By analyzing demographic and ticket-related attributes, this study helps understand survival trends, which can be useful for predictive modeling and decision-making in similar emergency scenarios.

**Key Features**

**Data Exploration:** Analyzing passenger demographics, ticket classes, and survival rates.

**Survival Trends:** Examining survival rates based on class, gender, age, and fare.

**Data Visualization:** Using charts and graphs to reveal survival patterns.

**Statistical Insights:** Evaluating correlations between survival and multiple factors.

**Libraries Used**

**pandas:** Data manipulation and analysis.

**matplotlib, seaborn:** Data visualization.

**numpy:** Numerical computations.

**scikit-learn:** Machine learning for predictive modeling.

**Dataset**
The dataset contains passenger details from the Titanic disaster, including survival status, age, gender, ticket class, fare, embarkation port, and family size. The objective is to determine which factors had the most significant impact on survival.

**Steps Involved**

**1. Data Loading**
Importing the dataset using pandas.read_csv().
Inspecting missing values and handling them appropriately.

**2. Data Preprocessing**

Filling missing values in Age and Embarked columns using median and mode, respectively.
Encoding categorical variables like Sex and Embarked for analysis.
Creating a new family size feature to analyze survival trends.

**3. Exploratory Data Analysis (EDA)**
Visualizing survival rates by gender, class, and fare.
Analyzing the correlation between age, fare, and survival.
Examining the impact of embarkation port and family size on survival.

**4. Survival Trend Analysis**

**Gender Influence:** Women had higher survival rates than men.

**Class Impact:** First-class passengers had the best survival rates, while third-class had the worst.

**Age Factor:** Children under 10 had a higher likelihood of survival.
Fare Influence: Higher ticket fares correlated with better survival chances.

**5. Predictive Modeling (Optional Extension)**
Applying Logistic Regression or Random Forest to predict survival outcomes.
Evaluating model performance using accuracy, precision, recall, and F1-score.
