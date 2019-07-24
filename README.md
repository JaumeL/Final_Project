## Final Project carried out during Data Science course at Flatiron School, London in January - March 2019.

### Summary:

The goal was to come up with a question that could be answered with the same data that I used at my mid-term project (please refer to the mid-term project available in https://github.com/JaumeL/Mid_Term_Project).  

### Goals: 

The question to answer is:

-	Is it possible to predict the number of victims per accident occurred?

### Techniques:

I have broken down the code into functional chunks and commented it appropriately.

I started importing the required libraries.

In a first attempt to find out more about correlations between variables, I plotted a matrix of correlations along with a heatmap. Apparently, there aren't so many correlations.  

I performed pre-processing techniques such as creating ‘dummy’ variables from categorical variables to use that information within a regression model.

I performed a multiple regression model, using ‘train’ and test ‘splits’ appropriately and selecting ‘victims’ as our target variable, the one I wanted to predict. 

Due to its poor performance, only 2% of accuracy, I tried to improve the model adding more numerical variables. 

Despite having improved a little bit the accuracy adding more variables, the model’s predictive ability was still very insignificant, only 4% of accuracy.  
 
### Results:

Unfortunately, the predictive ability of the model was very insignificant. Hence, there is not a relevant explanatory power.  

### Next steps:

We should take a look to other models to check if they could perform better than linear regression.  
