# data-cleaning-pandas


Overview

This aim of this project is to clean and format a dataset containing information about shark attacks, and use the data to produce visualizations that will either prove or disprove my hypotheses.
<br>

# Requirements/Libraries Used:
This code was written in Python/Jupyter Notebook, using the following libraries:
<br>
- Pandas
- matplotlib.pyplot
- Seaborn
<br>
 

# Hypotheses:
<br>

## 1- Shark attacks are mostly fatal
## 2- Most attacks are performed by white sharks
## 3- Australia is the country with the most shark attacks
## 4- Australian sharks are the deadliest

<br>

# 1- Shark attacks are mostly fatal
My initial thought was that most shark attacks are fatal, but based on the reported data it appears that this is not the case at all. The following pie chart showcases the percentage fatalities in terms of all documented cases: 

![fatalities](https://github.com/victorbescos/data-cleaning-pandas/blob/17d6890a3ea1e821649ab667a375608a95806beb/fatality_total.png)

# 2- Most attacks are performed by white sharks
White and Great White sharks are infamously dangerous and deadly. The following plot shows the distribution of shark species in the documented attack cases.  

![species](https://github.com/victorbescos/data-cleaning-pandas/blob/17d6890a3ea1e821649ab667a375608a95806beb/species_total.png)

The following shows the absolute number of attacks by the species with highest attack count and their respective fatality. 

![species](https://github.com/victorbescos/data-cleaning-pandas/blob/17d6890a3ea1e821649ab667a375608a95806beb/species_fatality.png)


#3 - Australia is the country with the most shark attacks: 
Australia is famous for its dangerous fauna, so one could make the assumption that its sharks are the most dangerous too. Thw following chart shows the all-time distribution of shark attacks by country (only indicating top 7), also indicating if how often they have been deadly.

![fatality by country](https://github.com/victorbescos/data-cleaning-pandas/blob/17d6890a3ea1e821649ab667a375608a95806beb/countries_fatality.png)

As clearly indicated in the chart. the country with the most documented shark attacks is the United States by a large factor. However, reports in Australia claim a much higher death count both in absolute and relative terms.

## 4- Australian sharks are the deadliest

In order to understand why Australia has such a high fatality rate, we can look at the most common species reported in the dataset for that particular country. The following pie chart shows the distribution by species in documented attacks in Australia.  


![aus_species](https://github.com/victorbescos/data-cleaning-pandas/blob/17d6890a3ea1e821649ab667a375608a95806beb/species_australia.png)

We can see that the most common sharks in Australia are the White, Whaler and Tiger shark, which we have seen are among the most violent and deadly. 


# Conclusion

In conclusion: 
- Most shark attacks are not fatal
- White sharks are the most violent and the deadliest
- Australia has the highest fatality rate in cases of shark attacks historically
- The USA claims the highest reported count of shark attacks but a relatively low fatality rate. 




