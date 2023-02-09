# Neural_Network_Charity_Analysis

## Overview: Explain the purpose of this analysis
The goal of this assignment was to use nerual networks and deep learning to create a model that would determine the potential for applicants on fulfilling loans successfully. 
## Results

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The "IS SUCCESSFUL" variable is the target in this excercise. 

What variable(s) are considered to be the features for your model?
- The Application Type, Affiliation, Classification, Income, and Asking Amount are variables to consider. 


What variable(s) are neither targets nor features, and should be removed from the input data?
- We removed the "EIN" and "NAME" fields because they fit this profile. I think the "Use_ Case", "Organization", and "Status" columns could probably be removed. I dont think they provide  much in terms of whether or not someone should get a loan. 


## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The first model had two layers, the first with 80 and second with 30. I did this becuase we learned this was pretty standard practice while doing the module. For the optimizations I did (100,30) for the first one. I did (80,30,10) for the second one. And I did (80,30) for the third one.  

Were you able to achieve the target model performance?
- Unfortunatly none of the optimizations allowed the model to achieve a 75% performance. 

What steps did you take to try and increase model performance?
- I tried a number of things like increasing the total number of layers, hidden layers, and trying to change the activation code but none of it worked. 

## Summmary
-Even though 4 models were created in total, none of them could reach the goal of 75%.
  -First model: 72.97%
  -First optimized: 72.95%
  -Second optimized: 72.96%
  -Third optimized: 73.04%
  
I am really unfamilier with all of the nerual network stuff so I was really struggling to think of a way to improve it. Im not sure if it would make a significant difference but I think the removal of all columns that dont directly assist in determining loan eligibility, such as the ones i mentioned earlier, would help a bit. 

