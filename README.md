<h2>Transaction-fraud-detection</h2>

This project implements a fraud detection model using Logistic Regression. The model is designed to classify transactions as either fraudulent or non-fraudulent based on features extracted from transaction data.

Data
The dataset used in this project is payment_fraud.csv, which includes the following columns:

<ul>
  <li>accountAgeDays: Number of days since the account was opened.</li>
  <li>numItems: Number of items purchased.</li>
  <li>localTime: Time of the transaction.</li>
  <li>paymentMethod: Method of payment (e.g., credit card, PayPal).</li>
  <li>paymentMethodAgeDays: Number of days since the payment method was added.</li>
  <li>label: Target variable indicating whether the transaction is fraudulent (1) or not (0).</li>
</ul>



Libraries Required
pandas, scikit-learn, seaborn, matplotlib

Results
The model achieved an accuracy of 100% on the test set. 
The confusion matrix and classification report indicate perfect classification performance, with no false positives or false negatives.

Notes
Ensure that the dataset is properly preprocessed and all categorical variables are converted to numeric values before training the model.
The model's performance might vary with different datasets or under different conditions. 
Consider tuning the model and evaluating it on diverse datasets for a more robust assessment.

Feel free to adjust the sections as needed based on the specifics of your project or any additional details you want to include.
