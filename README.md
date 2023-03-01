# Fairphone Purchase-Intention
Investigating Fairphone's customers purchase intentions.

<img width="676" alt="Fairphone_image" src="https://user-images.githubusercontent.com/94328819/221056848-95920635-1ee5-4f63-98bf-827d9ae39109.png">

Note: The code cannot be displayed due to privacy reasons, likewise most of the plots from the projects.

## Project Description and Initiation
Fairphone, a smartphone manufacturer focused on creating sustainable smartphones, wants to gain insight into their marketing strategies across different country customer bases and important factors that influence purchase intention in order to determine their most effective marketing approach.

**Variables**

Dependent variable: Purchase Intention

Some of the predictor/independent variables: 
- _Emotions_ (e.g. how much trust/joy/guilt in relation to purchasing a Fairphone?)
- _Technical characteristics_ (e.g. how much is camera/appearance/price important when purchasing a Fairphone?) 
- _Environmental Identity_ (e.g. how much does the customer perceive themselves to be an environmentalist?)
- _Demographics_ (e.g. gender and age, but also how much is the customer interested in promoting social change vs social tradition?)

**Analyses**
1. A measurement invariance analysis - Fairphone would like to gain insight into their scales and variables used. Measurement invariance is important to decide whether the scales are comparable across the countries.

2. A network analysis - Additionally, Fairphone is interested in looking at the purchase intentions and environmental variables from a network perspective.

3. A regression analysis - Lastly, they would like to find out which variables are relevant predictors for purchase intentions across the countries.

## Objectives and Learning Goals

**Objectives**
1. Conduct the three main analyses in order to answer the three main questions Fairphone has
2. Deliver a report and well-structured code notebook with methodology and key takeaways from the different analyses

**Learning goals**
1. Building up statistical and machine learning models from a business objective
2. Display skills in various forms of statistical analysis
3. Display communicative, collaborative and presentation skills

## Data Acquisition and Analysis Approach

**Data acquisition**
- Data was provided by Fairphone, in collaboration with the social psychology department of the University of Amsterdam (UvA). The data from surveys across 4 different countries were provided to be analyzed.

**Exploratory data analysis**
- A series of plots using ggplot were employed to explore the available data. Furthermore, analyses on outliers, missing data, correlations and reliability were conducted to ensure data was filtered properly and did not contain unnecessary or faulty entries.

**Measurement invariance analysis** 
- Using approaches as indicated by Mellenbergh (1989) and Wicherts & Dolan (2010), measurement invariance was analyzed. Through this analysis, it could be determined whether the purchase tendencies are similar across countries or if they differed.

**Network analysis**
Through a unified network structure and an analysis of the strength and position of nodes and edges in the network, clusters of important predictors for purchase intentions of fair trade smartphones could be determined for each of the countries under investigation.

**Regression analysis**
Lastly, in order to determine which factors significantly predict purchase intentions in all 4 countries, a regression analysis was set up. After checking for assumptions, 4 distinct models were constructed, all yielding different results in terms of important predictor variables.

## Key Takeaways From the Project

1. The measurement invariance analysis, as well as the network analysis, indicated that there are differences in purchase intention and factors influencing purchase intention between the 4 different countries.
2. There were very few predictors that were consistent across all countries. With green product interest being an important predictor in 3 of the 4 countries
3. The clients were very positive about the contact and the deliverables of the project, thus consultancy case was deemed a successful project.

## Relevant Skills Employed
- Programming in R(Studio)
- Communication with stakeholder, consultancy skills, report writing, presentation
- Translating business ideas into statistical and machine learning objectives

## References

Mellenbergh, G. J. (1989). Item bias and item response theory. International journal of educational research, 13(2), 127-143.

Wicherts, J. M., & Dolan, C. V. (2010). Measurement invariance in confirmatory factor analysis: An illustration using IQ test performance of minorities. Educational Measurement: Issues and Practice, 29(3), 39-47.


## Example Plots from the Project

### Exploratory Analysis - Distribution of Purchase Intentions (Dependent Variable)

<img width="654" alt="Screenshot 2023-02-24 at 00 48 34" src="https://user-images.githubusercontent.com/94328819/221057837-54782a05-ab15-40fe-b194-43673e2ddf63.png">


### Zoom In on Results from Measurement Invariance
<img width="675" alt="MIN" src="https://user-images.githubusercontent.com/94328819/221057899-ea6a55bb-4f47-45d9-9230-60fe5f6f28b4.png">


### Preview of one of the Network Architectures (Netherlands) 

<img width="647" alt="Network_NL" src="https://user-images.githubusercontent.com/94328819/221057951-1146622c-3bac-4c0e-921c-15ae4ba24f20.png">





