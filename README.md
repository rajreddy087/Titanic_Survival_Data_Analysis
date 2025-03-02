# Titanic Survival Analysis using Python  
*Titanic dataset analysis to uncover survival patterns based on class, gender, age, and other factors.*  

---

## *Overview*  
This project explores the Titanic dataset to identify key factors influencing passenger survival. By analyzing demographic and ticket-related attributes, this study helps understand survival trends, which can be useful for predictive modeling and decision-making in similar emergency scenarios.  

---

## *Key Features*  

- **Data Exploration**: Analyzing passenger demographics, ticket classes, and survival rates.  
- **Survival Trends**: Examining survival rates based on class, gender, age, and fare.  
- **Data Visualization**: Using charts and graphs to reveal survival patterns.  
- **Statistical Insights**: Evaluating correlations between survival and multiple factors.  

---

## *Libraries Used*  

- **pandas**: Data manipulation and analysis.  
- **matplotlib, seaborn**: Data visualization.  
- **numpy**: Numerical computations.  
- **scikit-learn**: Machine learning for predictive modeling.  

---

## *Dataset*  
The dataset contains passenger details from the Titanic disaster, including survival status, age, gender, ticket class, fare, embarkation port, and family size. The objective is to determine which factors had the most significant impact on survival.  

---

## *Steps Involved*  

### *1. Data Loading*  
- Importing the dataset using `pandas.read_csv()`.  
- Inspecting missing values and handling them appropriately.  

### *2. Data Preprocessing*  
- Filling missing values in **Age** and **Embarked** columns using median and mode, respectively.  
- Encoding categorical variables like **Sex** and **Embarked** for analysis.  
- Creating a new **family size** feature to analyze survival trends.  

### *3. Exploratory Data Analysis (EDA)*  
- Visualizing survival rates by **gender, class, and fare**.  
- Analyzing the correlation between **age, fare, and survival**.  
- Examining the impact of **embarkation port and family size** on survival.  

### *4. Survival Trend Analysis*  
- **Gender Influence**: Women had higher survival rates than men.  
- **Class Impact**: First-class passengers had the best survival rates, while third-class had the worst.  
- **Age Factor**: Children under 10 had a higher likelihood of survival.  
- **Fare Influence**: Higher ticket fares correlated with better survival chances.  

### *5. Predictive Modeling (Optional Extension)*  
- Applying **Logistic Regression** or **Random Forest** to predict survival outcomes.  
- Evaluating model performance using **accuracy, precision, recall, and F1-score**.  

---

## *Insights from Titanic Dataset Analysis*  

- **Higher-Class Passengers Had Higher Survival Rates**  
  - Passengers in **1st class had the highest survival rate**, followed by 2nd class, with 3rd class having the lowest.  
  - This suggests that **wealthier passengers had better access to lifeboats** and possibly received priority in rescue efforts.  

- **Women Had Higher Survival Rates Than Men**  
  - Across all classes, **female passengers had a significantly higher survival rate** than males.  
  - This supports the **"women and children first"** policy followed during the evacuation.  

- **Children Had a Better Chance of Survival**  
  - The age distribution plot shows that **children, especially those under 10, had higher survival rates**.  
  - This indicates that **younger passengers were prioritized** during rescue operations.  

- **Passengers with Higher Fares Were More Likely to Survive**  
  - The fare distribution plot reveals that **passengers who paid higher fares had higher survival rates**.  
  - This aligns with the earlier finding that **first-class passengers had better survival chances**.  

- **Most Passengers Embarked from Southampton**  
  - The majority of passengers **boarded at Southampton**, followed by Cherbourg and Queenstown.  
  - This reflects Titanic’s route but also suggests that **survival trends might be linked to embarkation points**.  

- **Older Passengers Were More Likely to Be in 1st Class**  
  - The boxplot of ages by class shows that **first-class passengers were generally older** than those in third class.  
  - This suggests that **wealthier, more established individuals were more likely to afford first-class accommodations**.  

- **Passengers in Higher Deck Levels Had Better Survival Rates**  
  - The deck-level survival plot suggests that **passengers in higher decks had better access to lifeboats**, leading to **higher survival rates**.  
  - **Lower decks (often assigned to third-class passengers) had fewer survivors**, possibly due to longer evacuation times.  

- **Passengers Traveling in Small to Medium Family Groups Had Better Survival Rates**  
  - The family size survival analysis shows that **passengers with 2 to 4 family members had the best survival rates**.  
  - **Those traveling alone had lower survival rates**, possibly due to lack of support in emergency situations.  
  - **Very large families (8+) had the lowest survival rates**, likely due to challenges in staying together during evacuation.  

- **Younger Passengers in Higher Classes Had the Best Survival Rates**  
  - The violin plot of age and survival by class highlights that **young passengers in first class had the highest survival probability**.  
  - This could be due to **better access to resources and priority in rescue efforts**.  

- **Network Analysis of Cabin Sharing Shows Clusters of Passengers in the Same Cabin**  
  - Many passengers **shared cabins**, and those in shared cabins may have been part of **families or groups**, impacting their chances of survival.  
  - **Cabins with multiple passengers had varied survival outcomes**, suggesting some groups might have influenced each other's survival chances.  

- **Survival Rates Decline with Age in Lower Classes**  
  - The line plot of age and survival rate shows that **as passengers get older, survival rates drop, especially in 2nd and 3rd class**.  
  - This suggests **older passengers may have faced mobility challenges** or were not prioritized in lifeboat allocation.  

- **Passengers Who Boarded at Cherbourg Had Higher Survival Rates**  
  - The scatter plot of embarkation, fare, and survival indicates that **many high-fare passengers boarded at Cherbourg, leading to higher survival rates**.  
  - **Southampton had the most passengers but a lower overall survival rate**.  

These insights help us understand how **socioeconomic status, age, gender, and boarding locations** played a role in survival outcomes during the Titanic disaster.  
