# Travel Insurance Prediction

This repository contains code and data related to predicting travel insurance purchases based on various features. The goal is to understand the factors influencing travel insurance decisions and build a predictive model.

## Dataset

The dataset used for this project is `TravelInsurancePrediction.csv`. It includes the following columns:

- `Age`: Age of the individual
- `Employment Type`: The Sector In Which Customer Is Employed
- `GraduateOrNot`: Whether The Customer Is College Graduate Or Not
- `AnnualIncome`: Annual income
- `FamilyMembers`: Number of family members
- `ChronicDiseases`: Whether the individual has chronic diseases
- `FrequentFlyer`: Derived Data Based On Customer's History Of Booking Air Tickets On Atleast 4 Different Instances[2017-2019]
- `EverTravelledAbroad`: Whether the individual has traveled abroad
- `TravelInsurance`: Target variable 

## Exploratory Data Analysis (EDA)

- Summary statistics
- Distribution plots for numeric features
- Imbalance percentages of categorical features
- Correlation matrix

## Hypothesis Testing

1. **Age Hypothesis**:
   - Null hypothesis (H0): There is no significant difference in travel insurance purchases across different age groups.
   - Alternative hypothesis (Ha): Travel insurance purchase behavior varies significantly among different age groups.

2. **Income Hypothesis**:
   - Null hypothesis (H0): There is no association between annual income and travel insurance purchases.
   - Alternative hypothesis (Ha): Individuals with higher annual incomes are more likely to purchase travel insurance.

3. **Family Size Hypothesis**:
   - Null hypothesis (H0): Family size does not impact travel insurance decisions.
   - Alternative hypothesis (Ha): Travel insurance purchases differ based on family size (e.g., smaller families vs. larger families).

## Model Selection and Performance

- Three models were evaluated: Logistic Regression, Random Forest, and SVM.
- Balancing techniques (SMOTE and undersampling) were applied.
- Hyperparameter tuning was performed using GridSearchCV.
- Random Forest achieved the best performance based on F1-score and overall accuracy.

## Conclusion

- Age and income significantly influence travel insurance decisions.
- Family size does not significantly impact travel insurance choices.
- The Random Forest model is recommended for predicting travel insurance purchases.

## Author

Petar Krešimir Borić
