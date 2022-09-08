# Titanic-Survuval-Prediction
Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during
her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of
2224 passengers and crew. This sensational tragedy shocked the international
community and led to better safety regulations for ships.
What particularly we need do in this challange ?
In this challenge, we need to complete the analysis of what sorts of people were likely to
survive. In particular, we apply the tools of machine learning to predict which passengers
survived the tragedy.
Overview
The data has been split into two groups:
• training set (train.csv)
• test set (test.csv)
The training set should be used to build your machine learning models. For the training
set, we provide the outcome (also known as the “ground truth”) for each passenger. Your
model will be based on “features” like passengers’ gender and class. You can also use
feature engineering to create new features.
The test set should be used to see how well your model performs on unseen data. For
the test set, we do not provide the ground truth for each passenger. It is your job to
predict these outcomes. For each passenger in the test set, use the model you trained to
predict whether or not they survived the sinking of the Titanic.
We also include gender_submission.csv, a set of predictions that assume all and only
female passengers survive, as an example of what a submission file should look like.
What does this data set mean?
The data has been split into two groups:
• training set (train.csv)
• test set(test.csv)

The training set includes passengers survival status(also know as the ground truth from
the titanic tragedy) which along with other features like gender, class, fare and pclass is
used to create machine learning model.
The test set should be used to see how well my model performs on unseen data. The test
set does not provide passengers survival status. We are going to use our model to predict
passenger survival status.
Lets describe whats the meaning of the features given the both train & test datasets.
Variable Definition Key.
• Survival
• 0= No
• 1= Yes
• pclass (Ticket class)
• 1=1st
• 2=2nd
• 3=3rd
• sex
• age
• sibsp (# of siblings / spouses aboard the Titanic)
• parch (# of parents / children aboard the Titanic)
• tickets
• fare
• cabin
• embarked Port of Embarkation.
• C = Cherbourg,
• Q = Queenstown,
• S = Southampton
• pclass: A proxy for socio-economic status (SES)
• This is important to remember and will come in handy for later analysis.
• 1st = Upper
• 2nd = Middle
• 3rd = Lower
