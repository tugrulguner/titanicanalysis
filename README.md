In this project, I try to get high scores in kaggle competition by predicting the Titanic survivals, which you can find the dataset and detailed descriptions about it in the following link: [Titanic](https://www.kaggle.com/c/titanic).

I want to share my code that mainly focuses on feature engineering. With this code I was able to achieve ~0.8 score, and with this score I got my position as 1633th best score over 15532 submissions, which puts me in best 10%. What I did here can definitely be improved, and I will update here whenever I obtain better results. Thank you.

For the code: 'titanicprocessing', I put some comments for every function, parameter, model, etc. to make everything as simple as possible in terms of understanding and following it line by line. Please keep me noticed if you find anything confusing or unclear.  

Here is the heatmap(seaborn) figure of training data indicating how much columns are correlated with each other and with 'Survived':

![Seaborn Heatmap of the Training data](Seaborn_heatmap_trainingdata.png)


Here is the confusion matrix that I obtain after having 0.85 score (with my own error calculating function: cross-validation)


![Confusion matrix of the Training data](Confusion_Matrix_trainingdata.png)


It obvious that we have still some serious prediction problems. The model or preprocessing or both should be improved in order to reduce
these error that my model made.
