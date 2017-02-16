# Prosper-Loan-Data-Analysis

##Summary:

In this project I reviewed a Prosper Loan data set containing 113,937 loans with 81 variables on each loan, including 
loan amount, borrower rate (or interest rate), current loan status, 
borrower income, borrower employment status, borrower credit history, 
and the latest payment information.

I wanted to visualize in my analysis the difference between the average Prosper loans EstimatedReturn vs. ActualReturn
on loans for each ProsperRating yearly. I also wanted to display the amount of loans for each group.

##Design:

Original Design Choices:
I decided to use a bubble chart since it would allow me to compare the amount of loans, actual return and estimated 
return for each separate prosper loan rating. I did this since I wanted viewers to understand all loans gave a lower 
return than what was expected and the worst the prosper rating the higher likely hood in bad economic times
that the actual return would be way lower than the estimated return by prosper loans. I also changed the bars on the 
side to show the change in the total amount of loans granted per year. I color coded the bubbles to allow the eye to 
quickly understand the graph and for those that are color blind, when one hovers over a point its variable values 
appeared.

Feedback #1 Design Changes:
* Added prosper loan rating legend title
* Changes the prosper loan rating color boxes to circles to allow the eye to equate easier
* Changes order of prosper loan ratings from best to worst
* Added a comment that the loans included in the plot are only those with proser loan ratings and estimated returns.
* Placed words in graph to show above the line the actual return was higher than the estimated return and visa versa.
* Increase size of fonts and chart for easier viewing



##Feedback:

Review #1 Feedback:
* Please add a title for the legend of prosper ratings. 
* Change the prosper loan rating color boxes to circles to allow the eye to equate easier
* Change order of prosper loan ratings from best to worst
* Add a comment that the loans included in the plot are only those with proser loan ratings and estimated returns.
* Place words in graph to show above the line the actual return was higher than the estimated return and visa versa.



##Resources:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control

https://github.com/PMSI-AlignAlytics/dimple/blob/master/src/objects/axis/methods/addGroupOrderRule.js

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple#filterData

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#addOrderRule

https://www.fool.com/knowledge-center/annualized-return-vs-cumulative-return.aspx

http://www.investinganswers.com/financial-dictionary/bonds/effective-yield-1013

http://stackoverflow.com/questions/19437701/how-to-calculate-any-negative-number-to-the-power-of-some-fraction-in-r

https://discussions.udacity.com/t/annualized-return-measure/161846/3

http://stackoverflow.com/questions/24459752/can-dplyr-package-be-used-for-conditional-mutating

https://discussions.udacity.com/t/prosper-loan-definitions-calculating-investor-return/35762/4