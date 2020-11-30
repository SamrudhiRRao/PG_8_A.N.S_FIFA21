# FIFA_20-Predict-best-Footballers

The code is written and worked in Jupyter Notebook. 
We have imported libraries such as pandas, numpy, xlrd, matplotlib, seaborn, sklearn, e.t.c.
Preprocessing:
First, the dataset is cleaned. There were missing and null values which was dealt with forward fill. There were columns in dataset for positions like 'ls', 'st', 'rs', 'lw', and many more which had a '+' symbol in their values. We have omitted the symbol as it would hamper further steps. There were few columns where the numbers were in 'string' type which as then converted to 'int' type. The data was then standardized and normalized.
Data Exploration:
The graphs which are done and analytrized are as follows:
1. Overall vs Age
2. Overall vs Potential
3. Market Value in Euros vs Overall Ratings
4. Acceleration vs Other chosen Features
5. Percentage of the players preferred foot
6. Percentage of Players in Attacker Position
7. Percentage of Players in MidField Position
8. Percentage of Players in Defender Position

ML Modelling
By Linear Regression the data is trained and tested. We have trained the model using 'age','value_eur','potential','wage_eur' and 'overall' columns. Based on that model we have used to predict suitable Final 11played + 8 subs and their ratings for 2021 FIFA. The model is trained and tested various times. 
The r^2 score is 0.9751724375249999
The Pearson Correlation Coefficient:  0.9875185720968196.
