# Recommendations With IBM

In this project I built the following three recommendation models for **IBM Watson Studio**. 

1. Rank Based Filter
2. User-to-User Recommendations
3. Matrix Factorizatin Based Recommendations

## Recommenders 

The first one is the most basic and generic one. It's only there to recommend articles to new users where we hit cold
start problem. 

Second model has two variations. First variation does not prioritize most similar users. The second one adresses to this
problem.

The third one relies on Singular Value Decomposition. It's prone to overfitting due to low sample size that it can make 
recommendations to. 

## Data
Data is provided by IBM. It's purely anonymised data where we don't have any information about the users. Even the 
demographics are not included. 

## Packages
for data wrangling and calculations
> Pandas, numpy,

for visualisations
> matplotlib and Plotnine 

packages were used. In the final phase, to ensure visualisation standars I replaced all matplotlib visualisations with 
the ones with plotnine

## Notes and References
Regarding fixing a messy for loop within a function, I picked a solution from a stackoverflow discussion, however I am
not able to reference it as I lost the tab. Other SO references are commented in the notebook. 

I read these two notebooks before my analysis and occasionally made returned to make comparisons with my approach.\

https://github.com/samarasadeek/Udacity_DSProject3_Recommendation_System 

https://github.com/MrYelameli/IBM_Watson_Studio_Project





