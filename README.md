# deep-learning-challenge
Module 21 Challenge

Analysis Report:

The purpose of this practice to use machine learning to assess charity applicant with the best chance of success. We used provide data of previous organizations that have received funding to train our code to predict whether applicant will be successful or not through the steps outlined below:

Data Processing:
    - The target of our model was "IS_SUCCESSFUL" column from our data because that was the binary needed to show an organizations success.

    - The types of variables feautred in our model were APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," and "SPECIAL_CONSIDERATIONS.
    - Variable EIN and NAME were removed from the data because they served no function in our model.

Compiling, training and evaluating the model
    - For my model I selected my first layer to have 4 neuron and with its activation set to "relu", my second to also have 4 with activation "relu" and my output layer to have just one neuron with activation "sigmoid". I chose these numbers because they were similar number to ones we have used in classwork and were able to see success with them.
    - Ultimately I was not able to achieve my target level of performance of 75%.
    - I attempted increasing the neuron layers from 4 to 8 to 10, as well as adding an third layer to my model. However, the highest accurancy I was able to achieve was only %72

In conclusion, my attempts at a deep learning model for this dataset were unsuccessful in achieving a %75 or higher accuracy score. In the future, I shouldnt be afraid to increase my number of neurons in my models layers. I think if I had set them to 15, 20 or 50, I would've had better results. In addition, a different approach to classification, such as Random Forest, could capture more complex dta interactions and thus improve the model's performance. 


