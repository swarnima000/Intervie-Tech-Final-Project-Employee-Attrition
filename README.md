1. **Setup**: 
   - Ensure Python is installed on your machine.
   - Install the required libraries (`numpy`, `pandas`, `seaborn`, `matplotlib`) using pip.

2. **Usage**:
   - Clone the repository to your local machine.
   - Navigate to the project folder in the terminal.
   - Run the Python script (`FINAL_TASK.py`) to execute the code.

3. **Data Analysis**:
   - The code performs Exploratory Data Analysis (EDA) on the employee attrition dataset.
   - It includes analysis of categorical columns with respect to the target column (Attrition).
   - It also analyzes continuous and discrete data with respect to the target column.

4. **Model Building**:
   - Two machine learning models are built for predicting employee attrition: Decision Tree Classifier and Random Forest Classifier.
   - The SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the target column (Attrition) to handle class imbalance.
   - The models are trained on the balanced dataset and evaluated using classification reports and F1 scores.
   - Random Forest demonstrated superior performance with an accuracy rate of 94%.

