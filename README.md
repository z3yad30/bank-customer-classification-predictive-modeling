
  # Bank Customer Classification: Predicting Campaign Success

  ## Project Goal
  The objective of this project is to develop a predictive model that classifies bank customers based on their financial behavior and demographic data. The model aims to predict whether a customer will subscribe to a term deposit, enabling the bank to optimize its marketing resources for higher conversion rates.

  ## Dataset Overview
  The analysis uses the **Bank Marketing Dataset**, which includes features such as:
  * **Demographics**: Age, Job, and Marital Status.
  * **Financial Information**: Average yearly balance.
  * **Campaign Engagement**: Duration of the last contact and the number of contacts performed during the campaign.

  ## Methodology
  ### 1. Data Cleaning & Feature Engineering
  * **Feature Selection**: Several non-essential columns were dropped to focus on high-impact variables, including `education`, `housing`, `loan`, and `contact`.
  * **Encoding**: Categorical variables like `job` and `marital` status were transformed using **Label Encoding** to prepare the data for machine learning models.

  ### 2. Model Development
  The project utilizes the **Random Forest Classifier** as the primary predictive engine. The workflow includes:
  * Splitting the dataset into training (80%) and testing (20%) sets to ensure model generalization.
  * Evaluating model performance using accuracy scores and confusion matrices.

  ## Technical Stack
  * **Languages**: Python
  * **Data Processing**: Pandas, NumPy
  * **Machine Learning**: Scikit-Learn (Random Forest, LabelEncoder, train_test_split)

  ## Installation and Usage
  1. Clone this repository to your local machine.
  2. Ensure the dataset is stored in `Data/bank-full.csv` relative to the notebook.
  3. Install the required Python libraries:
     ```bash
     pip install pandas numpy scikit-learn jupyter
     ```
  4. Open and run `07_task_03.ipynb` to train the model and view prediction results.
