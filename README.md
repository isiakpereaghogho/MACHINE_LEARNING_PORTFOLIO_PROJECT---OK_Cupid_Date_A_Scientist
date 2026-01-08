# MACHINE_LEARNING_PORTFOLIO_PROJECT : OK_Cupid_Date_A_Scientist
This is a walkthrough project for codecademy data science career path. This project will apply machine learning algorithms to the OKCupid Date a Scientist dataset

CODECADEMY WALKTHROUGH MACHINE LEARNING PORTFOLIO PROJECT: OKCUPID DATE A SCIENTIST

INTRODUCTION

In recent years, there has been a massive rise in the usage of dating apps to find love. Many of these apps use sophisticated data science techniques to recommend possible matches to users and to optimize the user experience. These apps give us access to a wealth of information that we’ve never had before about how different people experience romance.

This portfolio project will analyze some data from OKCupid, an app that focuses on using multiple choice and short answers to match users.

SCOPING

Project scoping creates a structure for the entire project. This includes stating the goals for the project, gathering the data, considering the analytical steps required through analysis and evaluation which will help build conclusions and findings from the analysis. A proper project scope can be a great road map for any project.

PROJECT GOALS

The project goal is to utilize the machine learning skills and its techniques to the OKCupid App User Profile dataset. Zodiac symbols are important for many users, but some users don’t add them in. This project will classify Zodiac signs using drinking, smoking, drugs, and essays as the features and will predict a user’s zodiac signs so we can guess the missing zodiacs when we make matches.

DATA

The data is stored in profiles.csv provided by codecademy. The dataset provided has the following columns of multiple-choice data:

age: continuous variable of users age
body_type: categorical variable of body type of user
diet: categorical variable of dietary information
drinks: categorical variable of alcohol consumption
drugs: categorical variable of drug usage
education: categorical variable of educational attainment
ethnicity: categorical variable of ethnic backgrounds
height: continuous variable of height of user
income: continuous variable of income of user
job: categorical variable of employment description
offspring: categorical variable of children status
orientation: categorical variable of sexual orientation
pets: categorical variable of pet preferences
religion: categorical variable of religious background
sex: categorical variable of gender
sign: categorical variable of astrological symbol
smokes: categorical variable of smoking consumption
speaks: categorical variable of language spoken
status: categorical variable of relationship status
last_online: date variable of last login
location: categorical variable of user locations
And a set of open short-answer responses to :

essay0: My self summary
essay1: What I’m doing with my life
essay2: I’m really good at
essay3: The first thing people usually notice about me
essay4: Favorite books, movies, show, music, and food
essay5: The six things I could never do without
essay6: I spend a lot of time thinking about
essay7: On a typical Friday night I am
essay8: The most private thing I am willing to admit
essay9: You should message me if…

ANALYSIS

After the data is received, summary statistics, descriptive statistics like mean, median, range, correlations,Data visualizations for univariate and multivariate exploration and short summary notes explaining insights gained from exploration. Since zodiac signs are being classified to make predictions on missing zodiac signs, machine learning classification algorithms will be implemented to solve the problem of this project.

EVALUATION

Once the model is created, metrics of success are used to evaluate the model performance(s). This include the use of confusion matrix and finding the accuracy, precision, recall, f1 of the model(s) used, and create graphs showing how they changed. The main components to include in the machine learning evaluation are:

Table showing model performance
Charts showing model performance
