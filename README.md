
=========================================
Virtusize Tech Solution – Data Science Task
=========================================

This repository contains a Jupyter notebook solution for Virtusize's Data Science technical task. The task involves analyzing a structured dataset and building a predictive model to estimate a target variable using machine learning.

--------------------
📂 Project Structure
--------------------
- Virtusize_Tech_Solution.ipynb : Jupyter notebook with complete EDA, feature engineering, model training, and evaluation.
- train.csv : Training dataset (referenced locally in the notebook).
- test.csv : Test dataset (referenced locally in the notebook).
- DS Question Answer.pdf : (The answer to the given question was contained in the PDF file)
- predicted.csv : (Estimated scores for hip, waist, and bust)

----------------
📌 Objective
----------------
To explore the dataset using statistical summaries and visualizations, perform necessary preprocessing, and build a Random Forest Regressor to make predictions on unseen data.

--------------------------
⚙️ Installation & Requirements
--------------------------
Ensure the following Python libraries are installed:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

You can install them using:

```
pip install pandas numpy seaborn matplotlib scikit-learn
```

-------------
🚀 How to Run
-------------
1. Clone this repository or download the notebook.
2. Ensure the train.csv and test.csv files are placed correctly as referenced in the notebook.
3. Open `Virtusize_Tech_Solution.ipynb` in Jupyter Notebook or any compatible environment.
4. Run all cells sequentially to reproduce the analysis and prediction process.
5. Please properly add the train and test paths at the beginning and end of the cell before using the "Run all cells" command.
6. Do not run "Outliers Cell" just to get the same accuracy as in Jupyter Notebook, because outliers are legitimate for this work. Keep only showing the EDA Approach.

----------------
🔍 Features Used
----------------
- Handling missing data
- Exploratory Data Analysis (EDA)
- Feature Scaling using `StandardScaler`
- Machine Learning using `RandomForestRegressor`
- Evaluation and prediction on the test set
- Additionally, other algorithms were explored, but only the approach with the highest accuracy was given.

------------
📊 Output
------------
Final predictions are generated for the test dataset using the trained Random Forest model. Model performance is assessed based on training data.

---------------
🧑‍💻 Author
---------------
Rofiqul Alam Shehab
