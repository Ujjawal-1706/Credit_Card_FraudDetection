🔍 Credit Card Fraud Detection – Project Workflow
📥 Data Loading: Loaded the creditcard.csv dataset containing anonymized transaction data, including amount, time, and a "Class" label indicating fraud (1) or not (0).

📊 Exploratory Data Analysis (EDA):

Viewed the first and last few records.

Checked the dataset shape and data types.

Verified the distribution of class labels to confirm class imbalance (fraud cases are significantly fewer).

⚖️ Handling Class Imbalance:

Applied resampling techniques (e.g., undersampling or oversampling) to balance the dataset for better model performance.

🔧 Feature Engineering:

Explored additional meaningful features like:

Transaction frequency

Time-based patterns

Amount-based insights

🧠 Model Building:

Used Logistic Regression as the initial classification model.

Split the dataset into training and test sets using train_test_split.

📈 Model Evaluation:

Evaluated model performance using accuracy score.

📁 Tools and Libraries:

Python (NumPy, Pandas, scikit-learn)

Jupyter Notebook

✅ Outcome:

Successfully built a fraud detection model with improved balance and performance.

Ensured low false positives and high fraud detection accuracy.
