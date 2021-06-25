# Starbucks
a dive into starbucks drinks

Starbucks data came from here:
https://www.kaggle.com/starbucks/starbucks-menu?select=starbucks_drinkMenu_expanded.csv
 
A few things to note about this data set - there are duplicate Starbucks drinks on here as there are different options on beverage prep. 
This includes things like which kind of milk you’d like to add. Different kinds of milk contain different calories and varying amounts of protein. 
I had to clean data because there were text strings titled “varies” and “Varies” in the protein column. These were giving me errors while trying to 
print out data. There were also a few spaces in front of the column names, so I had to strip the data of any white spaces. It was also a bit hard to 
fully analyze this data without the size of the drink. 

While this data set is pretty limited in terms of in depth analysis I was able to use pandas to calculate a few things. 
I first calculated the average amount of sugar, protein, calories, and sodium in Starbucks drinks across the menu:
Sugar: 32g
Protein: 6g
Calories: 185
Sodium: 5mg

I also charted something fairly obvious, but that was the correlation between calories and protein in a given Starbucks drink.  
linked here://www.datawrapper.de/_/tz0gd/

I also looked at the top 5 caloric drinks on the menu. I had to clean this as there were duplicate drink names with the same calories but a 
different kind of milk, which classified it as a new row and therefore,a new drink. 
I wanted to examine 5 different drinks. I was able to chart that and examine the total amount of sugar in grams each drink had. 
I found that the average amount of sugar in these drinks totaled more than 3 times the amount of recommended sugar per day for a person. 
The American Heart Association suggests that a healthy person has around 24g of sugar per day and on average these drinks had 72 grams of sugar. 
linked here: //www.datawrapper.de/_/7ZMad/

I didn't find this the most thrilling data set to analyze, but practicing over here :) I wish I would have had a better idea in mind when it 
came to analyzing this data, or rather, I wish I would have started with a question over a data set. I do think it would be interesting to see
the most popular drink on the menu/if its changed. If there a spikes in a certain drink before a new one comes out? I also think it would be 
interesting to know breakdown by price to make the drink, then how much is charged for it. I have also been reading a lot about how Starbucks 
has re-vamped itself via data over the course of the pandemic - thats interesting! https://www.tableau.com/about/blog/2021/1/how-starbucks-uses-analytics-enhance-customer-experience
Anyway, just a timing thing for me! 
