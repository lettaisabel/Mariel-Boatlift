# Mariel Boatlift
A UC Berkeley **ECON148: Data Science for Economists** project.

### Introduction
In this project, we will make an attempt to replicate a famous paper ["The Impact of the Mariel Boatlift on the Miami Labor Market"](https://davidcard.berkeley.edu/papers/mariel-impact.pdf) by Prof. David Card on the effects of the Mariel Boatlift on the Miami labor market. The analysis file can be found [here](https://github.com/lettaisabel/Mariel-Boatlift/blob/main/proj02.ipynb).

**Skill sets applied in this project include:**
- Employed `Pandas` for advanced data wrangling to prepare the dataset for subsequent analysis.
- Using the `OLS regression` to quantitatively determine the association between certain variables and wages.

### Historical Background
Amidst an economic downturn in Cuba and an increasing number of dissident Cubans seeking asylum, the Cuban leader Fidel Castro announced on April 20, 1980 that any Cuban who wished to leave the island could do so, reversing the Communist regime’s closed emigration policy. Between April and October 1980, some 1,700 boats, many arranged by Cuban exiles already in the United States, carried Cubans from the port of Mariel (the departure zone designated by the Castro government) to Florida. 

In response, President Jimmy Carter declared  a state of emergency in affected areas and, on June 20, established the the Cuban-Haitian Entrant Program (CHEP), which granted temporary status and access to asylum processing and community assistance to both Cubans and thousands of Haitians concurrently fleeing to the United States. During this period, reports that the Cuban government also released prisoners to travel to the United States prompted the U.S. Coast Guard to blockade some 1,400 boats; however, hundreds of Cubans continued to arrive in Florida daily. The CHEP coverage window ended after the Carter administration negotiated an end to the boat lifts with the Cuban government in October 1980. ([Source](https://immigrationhistory.org/item/mariel-boatlift/))

### Economic Impact
About half of the Mariel immigrants decided to live in Miami permanently, which resulted in "a 7\% increase in the labor force of Miami and a 20\% increase in the number of Cuban workers in Miami" ([Card (1990)](https://davidcard.berkeley.edu/papers/mariel-impact.pdf)). Aside from the unemployment rate rising from 5.0\% in April 1980 to 7.1\% in July, the actual damage to the economy was marginal and followed trends across the United States at the time. When observing data from 1979 to 1985 on the Miami labor market and comparing it with similar data from several other major cities across the United States, focusing on wages, the effects of the boatlift were marginal ([Alejandro and Leif (1989)](https://www.jstor.org/stable/2095716)). 

### Research Approach
Since immigrants have the freedom to choose their destinations (and will naturally choose those places with strong labor markets), it is not enough to look at whether places with more immigrants and see if these places have different unemployment rates or wages to determine the causal effect of immigrantion on a local labor market. However, Card determined that there are some circumstances under which immigrants will arrive which have very little to do with the labor market of that place; the Mariel Boatlift is one such event. Here is Card's description:

> The experiences of the Miami labor market in the aftermath of the Mariel Boatlift form one such \["natural"\] experiment. From May to September 1980, some 125,000 Cuban immigrants arrived in Miami on a flotilla of privately chartered boats. Their arrival was the consequence of an unlikely sequence of events culminating in Castro's declaration on April 20, 1980, that Cubans wishing to emigrate to the United States were free to leave from the port of Mariel. Fifty percent of the Mariel immigrants settled permanently in Miami. The result was a 7% increase in the labor force of Miami and a 20% increase in the number of Cuban workers in Miami. (Card, 1990:245-6)

Professor David Card received the Nobel Prize in Economics "for his empirical contributions to labour economics" which is highly relevant to this work. He delivered his [prize lecture](https://youtu.be/wD48p6m8U-8?t=237) on 8 December 2021.

