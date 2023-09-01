
1. Overview of the analysis:

    The point of this is to create a tool that will help the Alphabet Soup Foundation select applicants for funding with the best chance of success for for their ventures.

2. Results: 

    Data Preprocessing

    What variable(s) are the target(s) for your model?

        The target variable is IS_SUCCESSFUL and the rest of the columns are the features.

    What variable(s) are the features for your model?

        The rest of the columns in application_df excluding IS_SUCCESSFUL are the features.

    What variable(s) should be removed from the input data because they are neither targets nor features?

        The variables that should be removed are the 'EIN' and 'NAME' columns.


    Compiling, Training, and Evaluating the Model

    How many neurons, layers, and activation functions did you select for your neural network model, and why?

        In the first model I chose 2 layers as relu functions with 80 and 30 neurons respectively because that is what the output contained.

    Were you able to achieve the target model performance?

        I was not able to achieve the 75% but I was able to increase the performance to 73%.

    What steps did you take in your attempts to increase model performance?

        In order to increase performance, I added more neurons to the second hidden layer, created a third hidden layer with 20 neurons, and increased the number of epochs.

3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

    All in all after adding a layer, increasing neurons, and increasing epochs, the performance went up to about 73%. I would recommend trying to a different model without removing the 'NAME' column to change the shape. It would also be interesting if we removed more columns and cleaned up more data.