The objective of the code is to build a text classification model for detecting dissatisfied customer feedback in an imbalanced binary dataset.
- The data preprocessing steps involved text cleaning, stopword removal, and tokenization.
- To convert the textual data into numerical features, I utilized the TF-IDF vectorizer.
- To address the class imbalance, I applied SMOTEENN, which combines both oversampling and under-sampling techniques.
- The model was trained using an XGBoost classifier, with hyperparameters adjusted to handle the class imbalance effectively.
- Stratified K-Fold cross-validation was implemented to evaluate model performance while maintaining the class distribution across folds.
- The F1 score was used as the primary evaluation metric, and confusion matrices were generated to provide deeper insights into the model’s predictions.
