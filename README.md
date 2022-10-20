# Credit_Risk_Analysis

## Overview

In this project, we predicted credit risk based on a number of factors from a CSV file. We used a variety of methods and machine learning models including resampling models, the SMOTEENN algorithm, and ensemble classifiers. 

## Results

### Random Oversampling Model

![acc_ran_oversampling](https://user-images.githubusercontent.com/106620821/197047698-6e1a63b4-8f83-4590-a5fa-5c7ae4e73242.png)

![Random_Oversampling](https://user-images.githubusercontent.com/106620821/196840655-a216162d-53c6-482b-ac96-28b188ee06a7.png)

The balanced accuray score is 65%, with a sensitivity of 62%.

### SMOTE Model

![acc_smote](https://user-images.githubusercontent.com/106620821/197048256-5f38fb2c-63fb-4751-948b-11a953e81b0b.png)

![SMOTE](https://user-images.githubusercontent.com/106620821/196840663-529929cf-21f9-45b3-802b-0614d0057ebc.png)

The balanced accuray score is nearly 66%, with a sensitivity of 68%.

### Undersampling Model

![acc_undersampling](https://user-images.githubusercontent.com/106620821/197048476-d63b99b5-141a-4b5c-a3b4-66943114d7ef.png)

![Undersampling](https://user-images.githubusercontent.com/106620821/196840682-cc5b06ef-dc69-4d6f-bdee-2c2fbc4f1bff.png)

The balanced accuracy score is similar to the SMOTE model at nearly 66%, but with a sensitivity of only 40%.

### Combination (Over and Under Sampling)

![acc_under_and_over](https://user-images.githubusercontent.com/106620821/197048839-9bcdba83-d660-4206-ad6c-111d5b4ae957.png)

![Combination](https://user-images.githubusercontent.com/106620821/196840695-c4f2e2c0-25f9-4fe2-96b6-68bd40ae1b93.png)

The balanced accuracy score is 54%, with a sensitivity of 57%.

### Balanced Random Forest Classifier

![acc_random_forest](https://user-images.githubusercontent.com/106620821/197049238-6983760f-6e82-4948-87a7-3a35c6045670.png)

![Ensemble](https://user-images.githubusercontent.com/106620821/197047049-dae8a64e-af9c-40e8-a017-8ec0d6b99e0d.png)

The balanced accuracy score is nearly 79%, with a sensitivity of 89%.

### Easy Ensemble Classifier

![acc_easy_ensemble](https://user-images.githubusercontent.com/106620821/197049436-edc67750-3d39-4fcd-8786-9ec4fed697ba.png)

![Easy_Ensemble](https://user-images.githubusercontent.com/106620821/197047081-50439ced-9a6d-434d-8118-2629556f8d53.png)

The balanced accuracy score is nearly 92%, with a sensitivity of 94%.

## Summary

From these results we can conclude that the last two models, the Easy Ensemble Classifier and the Balanced Random Forest Classifier may be the best models to use when predicting credit risk. They have both a higher accuracy score and a higher sensitivity than the previous 4 models. 
