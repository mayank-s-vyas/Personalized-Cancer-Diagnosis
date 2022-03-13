# Personalized-Cancer-Diagnosis(Multi-Class Classification Problem)

1. Business Problem (Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/): 
   Classify the cancer mutations based on text based clinical literature
   
   
2. Data: Memorial Sloan Kettering Cancer Center (MSKCC)
3. Constraints :
   * No low-latency requirement.
   * Interpretability is important.
   * Errors can be very costly.
   * Probability of a data-point belonging to each class is needed.

4. Performance Metric
   (Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment#evaluation) :

   Metric(s):

   * Multi class log-loss
   * Confusion matrix
   
   
## Results
After applying different Models on different Text Encoded data, and Hyper-parameter tuning, Logistic Regression Performed best and shown the performance as foolows:

 * Text Data Encoding :  TFIDF(Uni & Bi-Grams)
 * Model    : Logistic Regression
 * train_log_Loss : 0.3866104195807289
 * cv_log_Loss    : 0.9909461077457965
 * test_log_Loss  : 0.9938288741108963
 * Misclassified Pnts : 0.35037593984962406

