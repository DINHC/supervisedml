# supervisedml

Purpose:

To create a code foor supervised machine learning that will help analyze loans from 2019 and 2020. 

*Data has already been adjusted using undersampling before actual coding began
--------------------------------------------------------------------------------------------------------------------------------------------------

Unscaled Data Prediction:
The Linear Regression model will do better than the Random Tree model due to the data being balanced potentially producing a better accuracy score
--------------------------------------------------------------------------------------------------------------------------------------------------
Unscaled Data Results:

Linear Regression: 
   
   -Training Score: 0.65 
   
   -Testing Score: 0.52 
 
Random Forest: 
   
   -Training Score: 1.0
   
   -Testing Score: 0.67

Random Forest had a better testing score than the Linear Regression model but the Random Forest Training Score was 1 pointing to it being overfit. The Linear Regession model had lower scores but they were closer in range with one another. I can say that neither performed well here as one had overfit data and one had very low outcomes. 
--------------------------------------------------------------------------------------------------------------------------------------------------
Scaled Data Prediction:

At this point since the data will be scaled I believe the Random Tree model will do better since the scaling of the data may affect the balance of the data thus favoring the 
Random Tree model but this goes on the assumption that the data is affected in a way that would alter how it has been set before.
--------------------------------------------------------------------------------------------------------------------------------------------------
Scaled Data Results:

Linear Regression: 
   
   -Training Score: 0.71 
   
   -Testing Score: 0.72 
 
Random Forest: 
   
   -Training Score: 1.0
   
   -Testing Score: 0.67
   
It is something to note that Random Forest produce similar results to the unscaled data which is something I did not expect and once again shows that the Random Forest is overfitting again. Linear Regression produce better results as the training and testing scores are near identical showing that at least on the scaled data used for this code it will be accurate
-------------------------------------------------------------------------------------------------------------------------------------------------






