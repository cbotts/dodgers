# Dodgers EDA
Exploratory data analysis of dodger game data 

## Objectives 
Make recommendations for improving dodger game attendence based on game data

## How to Run 
```
gh repo clone cbotts/dodgers/
jupyter notebook Botts_DSC630_Week3.pdf
```

## Data
Each instance of the dataset provided data about one dodger game. The features of the dataset include:

month             
day                
attend          
day_of_week   
opponent       
temp               
skies
day_night       
cap               
shirt            
fireworks       
bobblehead    

## Methods 
Histograms were created to view data distribution. Box and whisker plot displayed outliers. Data was then one hot encoded, so that a correlation analysis could be performed. Correlations were check for statistical significance. 

## Conclusion
Based on the EDA, it is recommended to reallocated marketing resources from naturally popular summer months to the less popular months. It is recommended to run a promotion on Thursdays to increase low attendance rates. 'bobblehead' feature should be explored more becauase of its high correlation with attendance. 
