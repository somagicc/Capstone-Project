# Gender Recognition by Voice
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Hello_computer.gif)

### Presentation
Watch the [presentation](https://docs.google.com/presentation/d/1huSoQE3e1uz74Howpzvw_peBVImpeXq_cgswhPmRRyk/edit "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://www.youtube.com/watch?v=yUopC0USor4&t=137s "video ")presentation.

Or just continue here.
## About the data
This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human vocal range).

## Problem Statement
The goal is to build a model to predict to gender by speech analysis.

![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Problem_Statement.gif)
## Applications
Speech recognition has various applications including human to machine interaction, sorting of telephone calls by gender categorization, video categorization with tagging and so on.
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Application.png)
## Attributes of Data
Find the attributes of the data [here](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/About%20the%20Data "here").

## Pre-Processing Data
The voiced speech of a typical adult male will have a fundamental frequency from 85 to 180 Hz, and that of a typical adult female from 165 to 255 Hz but the data had values beyond these ranges which needed to be removed.
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Initial%20Distribution%20of%20Mean%20Fundamental%20Frequency%20Across%20Gender.jpeg)

## Distribution of Data
Initial distribution of the data was 50-50 as shown below.
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Initial%20Distribution%20of%20Gender.png)

## Algorithms Used
I used five algorithms and then compared them on the basis of different model evaluation metrics. Algorithms used are:
- Naive Bayes Classifier 
- Logistic Regression
- k-Nearest Neighbours
- Decision Trees
- Random Forest

### Model Evaluation Metrics Used:
- Recall
- Precision
- f1 Score
- Accuracy

## Comparison of Models
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/Comparison%20of%20models.png)

Clearly Random Forest is outperforming the others.

## ROC Curve Analysis
![](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Images/ROC_Curve_Analysis.png)

END.
