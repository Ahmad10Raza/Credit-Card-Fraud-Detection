# Credit-Card-Fraud-Detection


# Datasets Information:

Credit card fraud detection datasets typically contain transactional data associated with credit card usage, including features that help in identifying fraudulent activities. Here are some common features found in credit card fraud detection datasets:

**1. Transaction Amount:** The monetary value of the transaction. Unusual or unusually high transaction amounts can be indicative of fraudulent activity.

**2. Transaction Date and Time:** The date and time when the transaction occurred. Analyzing patterns in transaction timing can help identify anomalies or suspicious behavior.

**3. Credit Card Features:** Information specific to the credit card used in the transaction, such as card type (e.g., Visa, Mastercard), issuer, expiration date, etc.

**4. Merchant Information:** Information related to the merchant or establishment where the transaction took place, such as merchant category code (MCC), merchant ID, location, etc. Unusual merchant categories or locations can raise red flags.

**5. Transaction Type:** Indicates the type of transaction, such as purchase, cash withdrawal, online transaction, etc. Certain types of transactions, such as large cash withdrawals or online purchases, may be more susceptible to fraud.

**6. Currency:** The currency in which the transaction was conducted. Analyzing transactions in multiple currencies or unfamiliar currencies can help detect fraudulent activity.

**7. Cardholder Information:** Data related to the cardholder, including demographics, location, age, etc. Comparing transaction details with cardholder information can identify discrepancies or potential fraud.

**8. Historical Transaction Behavior:** Features that capture the cardholder's historical transaction behavior, such as average transaction amount, frequency of transactions, spending patterns, etc. Deviations from the cardholder's usual behavior can be indicative of fraudulent activity.

**9. IP Address:** The IP address associated with the transaction, especially in the case of online or remote transactions. Unusual or multiple IP addresses can indicate potential fraud.

**10. Device Information:** Information about the device used for the transaction, including device type, operating system, browser, etc. Unfamiliar or suspicious device characteristics can be indicative of fraudulent activity.

**11. Fraud Label:** A binary label indicating whether the transaction is fraudulent (1) or legitimate (0). This label serves as the ground truth for training machine learning models and evaluating their performance.

**These features provide valuable insights and patterns that enable the development of effective fraud detection models. Machine learning algorithms can be trained on historical data containing these features to learn patterns associated with fraudulent transactions and identify new instances of fraud. By analyzing these features collectively, credit card fraud detection systems can accurately detect and prevent fraudulent activities, minimizing financial losses for both cardholders and financial institutions.**


**The dataset above provided is a CSV file that contains information about credit card fraud. The file contains 31 features, each of which describes a different aspect of a credit card transaction. The features are as follows:**

* **Time:** The time of the transaction, in Unix timestamp format.
* **V1:** An anonymized version of the credit card number.
* **V2:** An anonymized version of the credit card expiration date.
* **V3:** The amount of money charged in the transaction.
* **V4:** The merchant ID of the store where the transaction took place.
* **V5:** The city where the transaction took place.
* **V6:** The state where the transaction took place.
* **V7:** The country where the transaction took place.
* **V8:** The IP address of the device that made the transaction.
* **V9:** The browser that was used to make the transaction.
* **V10:** The operating system that was used to make the transaction.
* **V11:** The device type (e.g., desktop, laptop, mobile phone).
* **V12:** The date of the transaction.
* **V13:** The day of the week of the transaction.
* **V14:** The hour of the day of the transaction.
* **V15:** The minute of the day of the transaction.
* **V16:** The number of days since the credit card was issued.
* **V17:** The number of days since the credit card expiration date.
* **V18:** The number of transactions made with the credit card in the past 6 months.
* **V19:** The average amount of money charged per transaction in the past 6 months.
* **V20:** The standard deviation of the amount of money charged per transaction in the past 6 months.
* **V21:** The number of times the credit card has been used in a different country in the past 6 months.
* **V22:** The number of times the credit card has been used in a different state in the past 6 months.
* **V23:** The number of times the credit card has been used in a different city in the past 6 months.
* **V24:** The number of times the credit card has been used at the same merchant in the past 6 months.
* **V25:** The number of times the credit card has been used with the same IP address in the past 6 months.
* **V26:** The number of times the credit card has been used with the same browser in the past 6 months.
* **V27:** The number of times the credit card has been used with the same operating system in the past 6 months.
* **V28:** The number of times the credit card has been used with the same device type in the past 6 months.
* **Label:** A binary variable indicating whether the transaction was fraudulent (1) or not (0).

The dataset also contains a **Label** feature, which indicates whether the transaction was fraudulent (1) or not (0). This feature can be used to train a machine learning model to predict whether a new transaction is fraudulent.
