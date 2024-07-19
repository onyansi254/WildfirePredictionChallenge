# WildfirePredictionChallenge
Each year, thousands of fires blaze across the African continent. Some are natural occurrences, part of a ‘fire cycle’ that can actually benefit some dryland ecosystems. Many are started intentionally, used to clear land or to prepare fields for planting. And some are wildfires, which can rage over large areas and cause huge amounts of damage. Whatever the cause, fires pour vast amounts of CO2 into the atmosphere, along with smoke that degrades air quality for those living downwind.

Figuring out the dynamics that influence where and when these fires occur can help us to better understand their effects. And predicting how these dynamics will play out in the future, under different climatic conditions, could prove extremely useful.

The objective of this challenge is to create a machine-learning model capable of predicting the burned area in different locations over 2014 to 2016.

We’ve aggregated data on burned areas across Zimbabwe for each month since 2001. You’ll be given the burn area data up to the end of 2013, along with some additional information (such as rainfall, temperature, land cover etc) that extends into the test period.

Evaluation
The evaluation metric for this competition is Root Mean Squared Error.

You need to predict the proportion of the burned area per area square, with values of 0 to 1.

The IDs take the form of [area ID]_yyyy-mm-dd. There are 3821 area squares each with a unique ID ranging from 0 to 3820.

Your submission file should look like this (numbers to show format only)

ID                 burn_area
0_2014-01-01         0.5624  
1_2014-01-01         0.7654 
2_2014-01-01         0.1134 
3_2014-01-01         0.9751
