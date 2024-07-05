# Credit Card Fraud Detection
Credit Card Fraud Detection models using Machine Learning and Deep Learning on a PCA-transformed dataset. Addressing class imbalance, the models include ensemble methods and a Deep Neural Network (DNN), evaluated with standard metrics. Ensuring robust fraud detection through comprehensive preprocessing and balanced sampling.


------------------------------------------------------------------------------------------------------------------------------------------------------


The notebooks focus on the development of Credit Card Fraud Detection models using both classical Machine Learning (ML) and Deep Learning (DL) approaches. The dataset utilized in the analysis consists of transactions over two days, with features derived via Principal Component Analysis (PCA), except for 'Time' and 'Amount'. The target variable, 'Class', indicates whether a transaction is fraudulent (1) or not (0).

### Data Exploration and Preprocessing:
1. **Data Exploration:** Initial analysis highlights the imbalance in the dataset, with a significantly smaller fraction of fraudulent transactions.
2. **Data Visualization:** Visual comparisons of transaction amounts between valid and fraudulent cases are conducted.
3. **Data Sampling:** To handle the imbalance, a sample dataset is created by combining all fraudulent transactions with a random sample of non-fraudulent transactions.

### Feature and Response Separation:
- The dataset is split into features (X) and the target variable (y).
- The data is further divided into training and test sets using an 80-20 split.

### Machine Learning Models:
1. **Library Imports:** Essential libraries for data manipulation, visualization, and machine learning are imported, including `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, and `imblearn`.
2. **Model Training:** Various ensemble methods like Random Forest are utilized to train the models.
3. **Evaluation Metrics:** Standard metrics are employed to evaluate model performance, ensuring robust fraud detection capabilities.

### Deep Learning Approach:
- **Model Architecture:** A Deep Neural Network (DNN) is designed and trained on the dataset.
- **Training and Validation:** The DNN is trained with specific epochs and batch sizes, using appropriate loss functions and optimizers.
- **Performance Assessment:** The performance of the DNN is assessed through relevant metrics to gauge its effectiveness in detecting fraudulent transactions.
