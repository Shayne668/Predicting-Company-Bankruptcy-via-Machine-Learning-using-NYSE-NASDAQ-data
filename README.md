1. Due to the class imbalance between being bankrupt and not being bankrupt, the **Synthetic Minority Oversampling Technique (SMOTE) was applied, which improved the prediction accuracy and precision of the test datasets.
  
2. In the efforts to improve bankruptcy detection, I made a thoughtful decision to **prioritize the recall rate over accuracy (contradicting with what many others have done) for model performance evaluation**, to minimize false negatives, which is vital in financial analysis, where missing critical bankruptcy cases can be costly!

3. **Among all 7 algorithms using the NASDAQ data, accuracy and precision were both highest in Random Forest, followed by KNN and SVM**, with results being {RF:{Accuracy:0.89, Precision:0.88}, KNN:{ Accuracy:0.82, Precision:0.87}, SVM:{ Accuracy:0.82, Precision:0.86}}.

4. In NASDAQ data, **if taking computation cost, total computation time in this case into consideration, KNN can be considered outperforming random forest**, as it took KNN 7.1sec to conclude the results while random forest took 70mins. Details can be found in Table 1

5. In Taiwan Exchange Stock data, **KNN combined with non-linear PCA outperformed all other models**, indicating that these features are non-linearly seperatable. Details can be found in Table 2

6. **Further improvements**, including outlier removal techniques, predictor reduction, and exploration of unsupervised models, will refine the predictions. Addressing imbalanced data and fine-tuning model selection through sample scenarios will also contribute to more robust and relevant bankruptcy predictions, empowering better decision-making in this dynamic landscape 
