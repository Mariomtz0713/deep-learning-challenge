# Report Overview
This analysis looks at the results of neural network models that predict the likelihood of applicants achieving success who seek funding by the fictional organization Alphabet Soup.

## Data Preprocessing
Questions 
1. What variable(s) are the target(s) for your model?
- My name
2. What variable(s) are the features for your model?
- Yes
3. What variable(s) should be removed from the input data because they are neither targets nor features?
- idk yet

I had one attempt where I analyzed the 'ASK_AMT' column to reduce and remove any outlier values. To my surprise the model scored the lowest out of all my attempts and subsequently scrapped the idea.

## Compiling, Training, and Evaluating the Model
Questions
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Well
2. Were you able to achieve the target model performance?
- I was not able to achieve the target model performance after multiple attempts.
3. What steps did you take in your attempts to increase model performance?
- I tried to 

Original attempt - accuracy: 72.65 %, 2 layers [8,5] neurons
1st optimization - accuracy: 72.77 %, 3 layers [5, 10, 20] neurons
2nd optimization - accuracy: 72.86 %, 3 layers [5, 10, 20] neurons
3rd optimization - accuracy: 73.08 %, 3 layers [4, 6, 8] neurons


## Conclusion
Across my 4 attempts the neural network model did not achieve a target accuracy of 75% only peaking at 73.08%. To reach a higher accuracy futher data cleanup could be conducted to remove futher outliers or use a different model that has more data with greater correlation between input and output and improve generalization.

All models used an activation function of relu and conducted with 100 Epochs. 