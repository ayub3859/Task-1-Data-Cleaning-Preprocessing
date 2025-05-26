# Titanic Dataset - Data Cleaning & Preprocessing

## Objective
This project performs data cleaning and preprocessing on the Titanic dataset using Python and libraries like Pandas, NumPy, and Scikit-learn.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn

## Steps Followed
1. **Data Import & Exploration**
2. **Handling Missing Values**
   - Age: Filled using median
   - Embarked: Filled using mode
   - Cabin: Dropped (too many missing values)
3. **Encoding Categorical Variables**
   - Label Encoding: Sex, Embarked
   - Dropped: Name and Ticket
4. **Feature Scaling**
   - StandardScaler used for Age, Fare, SibSp, and Parch
5. **Outlier Detection**
   - Boxplots for visualization
   - Z-score for outlier removal
6. **Saved Cleaned Dataset** was `Titanic-Cleaned.csv`

## Files Included
- `Titanic-Dataset.csv` - Original dataset
- `titanic_preprocessing.py` - Python script
- `Titanic-Cleaned.csv` - Cleaned output

Output:
Final CSV has no nulls, all features encoded, scaled, and cleaned of outliers.
