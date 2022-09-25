# Python Project 4: Candy Bar Product Analysis

**Author**: Chinh X. Mai, **Date**: September 11, 2022

![image](https://user-images.githubusercontent.com/89245616/192158309-85802f6e-5c2f-451c-b888-f1bbd28119f5.png)

## Case description

The purchasing department of your firm would like to expand the confectionery assortment (private label). A new candy is to be created for this purpose. However, there is still disagreement within the relevant project team about the characteristics of the new candy.

For example, while some prefer a cookie-based candy, others favor a fruit gum variation. The divisional board therefore decided to commission a market research company to determine the popularity of the sweets available on the market.

The results of the market research are now available and you have been commissioned to carry out an analysis of the data. The aim is to analyze the impact of the characteristics of confectionery on their popularity and, based on this analysis, to make a recommendation for the new confectionery.

## Goal of the case study  

The project will be delivered in terms of a board presentation to the firm managerment. The presentation will last at most 15 minutes and should not focus too much on the technical details. Since the presentation is for the management, it should be short and go directly to the point by first providing an executive summary and some technical details later. Moreover, as the project will be presented in a online meeting, the participants will be close enough to the screen to read the details, but visualizations will be utilized to tell the story as they would be more intuitive and attract more attention.

## Executive summary and Conclusion

This project aims to find the characteristics of a candy bar that has the highest winning probability when matched with another. Employing `pandas`, `numpy`, `plotly`, and `statsmodel`, the analysis involves basic steps such as data import and visualization, the main workhorse is an OLS regression supported by a stepwise selection. Data includes 13 features and 85 observations, of which nine features are binary and others are numerical. The analysis shows that:

* A generic brand without any of ingredients has an estimated average winning rate of approximately 33 percent
* Among other factors, only `chocolate`, `peanutyalmondy`, `fruity`, `crispedricewafer`, `sugarpercent`, and `hard` have statistically significant impacts on `winpercent`
* In the significant factors, `hard` has a negative impact while others have positive impacts

The analysis concludes that a candy having highest winning rate is the candy including chocolate, peanutyalmondy, fruity, crispedricewafer and a high amount of sugar.

## Detailed documentation

For detailed documentation, please refer to the project repository using the following link:

[Python Project 4 Github](https://github.com/ChinhMaiGit/Project-Python-4/)

or access the analysis workbook directly

[Python Project 4 Workbook](/html/candybar.html)
