## Credit Risk Analysis Report

The purpose of this analysis is to evaluate important information for a hypothetical client, using machine learning. We used a dataset of historical lending activity from a peer-to-peer lending services company to build this model to evaluate the creditworthiness of borrowers. Using logistic regerssion, we analyzed the data using the `classification_report` viewing the results of our alogrythmic process. 

# Results

* Machine Learning Test Model:

  * Accuracy = `94%`. This accuracy comes from the Balanced Accuracy Score function. This means that after taking into account the true positive and true negative rates, the model was able to match it up with a 94% success rate

  * Precision = `92%`. Basically means that 92% of the tests were predicted correctly.

  * Recall = `95%`. The model was correct 95% of the time in identifying true positive values in our training set


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I would recommend using this model, however there is further training to be done. I believe that potentially using another library like RandomForest and not just using a test set would yield better results. While our model had an accuracy rate of 94%, 6% could still be a large margin of error, especially when it comes to large financially decisions like loans. On top of that, the logistical regression model predicts healty loans with 100% accuracy, while identifying more volatile, high-risk loans at 85% accuracy. This would be troublesome for our hypothetical client if toxic loans got looked over and passed off as healthy loans.