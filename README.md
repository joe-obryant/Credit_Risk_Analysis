# Credit_Risk_Analysis
## Overview
The purpose of the assignment was to impelement various machine learning techniques to sample for loan applicants credit risk. We used six different methods and compared results across all six in order to find the best technique.

## Results
- The first method was to compare 2 Oversampling algorothims, Naive Random and SMOTE
![Screenshot 2023-03-01 at 7 58 09 PM](https://user-images.githubusercontent.com/115109628/222319642-92a39c8c-085c-460d-a8cf-b3b16d29c16f.png)

![Screenshot 2023-03-01 at 7 59 08 PM](https://user-images.githubusercontent.com/115109628/222319771-d2c10a20-c135-41ac-8e7e-5cd5c52204c3.png)
- the outputs above are from the Naive Random and SMOTE oversampling methods respectively. Both methods produced accuracry scores very similar to one another. We aslo see that both models struggle at predicting high risk applicants.

- The following method was to use a Undersampling algorithim in comparison to the two Oversampling above.
![Screenshot 2023-03-01 at 8 02 31 PM](https://user-images.githubusercontent.com/115109628/222320345-7f8c9fd3-9e61-4882-80d9-1c91a9d61d4b.png)
- This method provided us with a significantly lower accuracry score. So it was not as effecient as the two methods above.

- Here a combination of Oversampling and Undersampling was used
![Screenshot 2023-03-01 at 8 05 20 PM](https://user-images.githubusercontent.com/115109628/222320693-d02aa67f-949e-4e0f-a991-99ac9845d73c.png)
- Much like the original Oversampling methods, a accuracy score relative to those two was also produced.

- Here we used Balanced Random Forest Classifier to compare to an Easy Ensemble AdaBoost classifier
![Screenshot 2023-03-01 at 8 12 58 PM](https://user-images.githubusercontent.com/115109628/222321727-30ac4507-334a-4f89-8c6b-24e6411c18a6.png)
- The output for the Balanced Random method provided an accuracry score of 0.78 much higher than any of the other methods.

- This is the output for the AdaBoost classifier method
![Screenshot 2023-03-01 at 8 15 44 PM](https://user-images.githubusercontent.com/115109628/222321998-b8f3780c-a7a5-4521-a4d2-4eae1b8b75c1.png)
- The AdaBoost method provided the highest accuracry score with 0.92, significantly higher than any of the other methods.



