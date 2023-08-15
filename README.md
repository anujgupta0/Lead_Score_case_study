# Lead Source Case Study
## Problem Statement
- To identify the hot leads , so that sales team can focus on the hot leads.
- Company require to build a model where we need to assign a lead score to each of the lead so that customer which having high score have high   conversion chances. The score should be between 0 and 100.
- To get to know the which columns are most important and which is not important.

By using this predictive model, X Education intends to enhance their lead conversion process, concentrate their sales endeavors on the most potential leads, and ultimately attain the desired conversion rate of 80%.


### Steps Followed

    1.  Importing the data and inspecting the data frame
    2.  Data preparation 
    3.  EDA
    4.  Dummy variable creation
    5.  Test-Train split
    6.  Feature scaling 
    7.  Feature Selection
    8.  Model Building (RFE , VIF and p- values) 
    9.  AUR-ROC Curve
    10. Accuracy sensitivity and specificity trade off value
    11. Making the Confusion matrix
    12. Making predictions on test set
    13. Conclusion and Recommendations


### Conclusion:

#### Evaluation Martics: 
     Train Data Accuracy, Sensitivity and Specificity
        1. Accuracy    : 79.27%
        2. Sensitivity : 80.61%
        3. Specificity : 78.45%
     Test Data Accuracy, Sensitivity and Specificity
        1. Accuracy    : 78.89%
        2. Sensitivity : 83.25%
        3. Specificity : 76.20%
    
    
#### Lead Count for Different Lead Score 
    1. Number of rows with Lead_score > 90: 228 counts 
    2. Number of rows with Lead_score > 80: 429 counts 
    3. Number of rows with Lead_score > 70: 578 counts 
    4. Number of rows with Lead_score > 60: 813 counts 
    5. Number of rows with Lead_score > 50: 957 counts





