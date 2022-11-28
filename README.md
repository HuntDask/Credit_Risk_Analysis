# Credit_Risk_Analysis

## Overview of the analysis
In this project, we are using machine learning to build models and algorithms to determine credit risk for a loan company. Our machine learning building will lead to more accurate identificaton of good loans for applicants. We are assisting the lead data scientist to help build and develop machine learning models to help determine the right candiates for credit application. We evalute the performance of our clients through models created to predict how well they are suited to apply for a loan with our company.

## Results
- For our Naive Random Oversampling, we were able to find that the balanced accuracy was 0.65, with a precision that is low for high risk and high for low risk. It had a recall of .65/.67.
<img width="1190" alt="Screen Shot 2022-11-28 at 11 06 20 AM" src="https://user-images.githubusercontent.com/107444840/204360811-42fc9aab-9995-49e9-b1b7-4b2651a2dffb.png">
- For our SMOTE Oversampling, we were able to find that the balanced accuracy was 0.65, with a precision that is low for high risk and high for low risk. It had a recall of 0.65/0.66.
<img width="1353" alt="Screen Shot 2022-11-28 at 11 06 55 AM" src="https://user-images.githubusercontent.com/107444840/204361436-ea4d2421-e137-4f0f-b1e7-8eaa72201c3a.png">
- For our Undersampling, we were able to find that the balanced accuracy was also 0.59, with a precision that is low fir high risk and high for low risk.It had a recall of 0.59/0.44
<img width="1391" alt="Screen Shot 2022-11-28 at 11 07 15 AM" src="https://user-images.githubusercontent.com/107444840/204361722-92cb7fa2-0d48-448d-8124-5ef7c0304f34.png">
- For our Combination Under-Over sampling, we were able to see a balanced accuracy of around 0.51, with a precison low for high risk and high for low risk. it would be about 0.70/0.57 for the recall.
- For our balanced random forest classifier, we were able to see a balanced accuracy of around 0.78, with a precison that is low for high risk and high for low risk. It would be a recall of about 0.67/0.91.
- For our last one, the Easy Ensemble AdaBoost Classifier, we can see a balanced accruracy around 0.92, with a precision that is low for high risk and high for low risk. For our recall it would be around 0.91/0.94.

## Summary
As we can see from our results above, we are able to tell the accuracy, precision, and the recall from both the credit rist ensemble and the credit risk resampling codes we created in Jupyter Notebook. From our information we collect, we can see that with around a 0.92 balanced accuracy our Easy Ensemble AdaBoost Classifier would be the best option for when we are trying to look at loans and credit card credit information. From looking at our other data, we can see that not any other reslut found was close to our Easy Ensemble AdaBoost Classifier, with the next closest being the balanced random forest classifier being around 0.78. Our East Ensemble AdaBoost classifier had the best results from our collected data, and for our credit risk analysis this is the machine learning model that we should use to collect the most accurate and best results.
