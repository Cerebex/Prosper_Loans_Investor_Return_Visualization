# Prosper Loan Data Analysis Visualization

##Summary:

In this project I reviewed a Prosper Loan data set containing 113,937 loans with 81 variables on each loan, including 
loan amount, borrower rate (or interest rate), current loan status, 
borrower income, borrower employment status, borrower credit history, 
and the latest payment information.

I wanted to visualize in my analysis the difference between the median Prosper loans Estimated Return vs. my 
calculated Actual Return on loans for each Prosper Credit Rating yearly. 

##Files:
* index.html, index.css and index.js houses the main dimple.js/d3.js visualization.

* The original loan data is within the prosperLoanData.csv file. 

* The original loan data variable classifications is with the Prosper Loan Data - Variable Definitions.csv file.

* Wrangle_Original_Data_with_R.Rmd is the R file in which I calculate the actual return of each loan and wrangle the
	data to a form to input into my visualization

* Prosper_Loans_Actual_Return.csv is my wrangled data which is input into my visualization


##Design:

Original Design Choices:
I decided to use a bubble chart since it would allow me to compare the amount of loans, actual return and estimated 
return for each separate prosper loan rating. I did this since I wanted viewers to understand all loans gave a lower 
return than what was expected and during specific years the worse the prosper rating the higher likely hood
that the actual return would be a lot less than the estimated return by prosper loans. I then explained that the larger 
difference between the actual return and the expected return for 2008-2012 as compared to 2013 could be based on the 
fact that there was a financial crisis in the USA in 2008 and it took until 2013 for the loan market to recover. In 
recovery more people were able to pay off there loans and interest as expected leading the actual loan returns being
more in-tune with the expected return. Also when loans recovered from the financial crisis they lined up in 
prosper loan rating which is to be expected based upon interest rates for loans being correlated to 
ones prosper loan credit rating.

understand this negative relationship was significantly correlated to bad economic times by separating the 
data by based upon 

I also changed the bars on the 
side to show the change in the total amount of loans granted per year. I color coded the bubbles to allow the eye to 
quickly understand the graph and for those that are color blind, when one hovers over a point its variable values 
appeared.

Feedback #1 Design Changes:
* Added prosper loan rating legend title
* Changes the prosper loan rating color boxes to circles to allow the eye to equate easier
* Changes order of prosper loan ratings from best to worst
* Added a comment that the loans included in the plot are only those with prosper loan ratings and estimated returns.
* Placed words in graph to show above the line the actual return was higher than the estimated return and visa versa.
* Increase size of fonts and chart for easier viewing

Review #2 Design Changes:
* Added footnote that bubble size equals total amount of loans for specific credit rating
* Changed to Prosper Loan Rating to Prosper Loan Credit Rating for Legend Title
* Made title left justified
* Put box around two legends
* Changed main chart title to "Actual vs. Estimate Median Returns According To Prosper Loan Credit Rating"
* Added open line before "Bar size equates to total yearly loans" in legend title
* Deleted "Above 1:1 dashed line" and "Below 1:1 dashed line"

Review #3 Design Changes:
* Changed font to bold for wording inside the graph to emphasize its presence
* Change the footnote to emphasize data is being excluded
* Slowed the animation to allow the eyes to understand the change

Review #4 Design Changes:
* Centered the visualization for easy review and aesthetics
* Changed capitalization of second footnote to add symmetry to footnote 
* Made main title of graph more explanatory 
* Added short introductory paragraph above graph to explain your main conclusion from the visualization
* Changed legend and tooltip labels to add clarity
* Changed color coding in the legend to grey scale add clarity 
* Increase size and remove abbreviation of Actual Return < Estimated Return 
* Made bubble size constance since it does not add to my intended conclusion from the data



##Feedback:

Review #1 Feedback:
* Please add a title for the legend of prosper ratings. 
* Change the prosper loan rating color boxes to circles to allow the eye to equate easier
* Change order of prosper loan ratings from best to worst
* Add a comment that the loans included in the plot are only those with prosper loan ratings and estimated returns.
* Place words in graph to show above the line the actual return was higher than the estimated return and visa versa.

Review #2 Feedback:
* Please add footnote that bubble size equals total amount of loans for specific credit rating
* Change to Prosper Loan Rating to Prosper Loan Credit Rating for Legend Title
* Make title left justified
* Put box around two legends
* Change main chart title to "Actual vs. Estimate Median Returns According To Prosper Loan Credit Rating"
* Add open line before "Bar size equates to total yearly loans" in legend title
* Change so starts from top to bottom 2009 - 2013
* Delete "Above 1:1 dashed line" and "Below 1:1 dashed line"

Review #3 Feedback:
* Please bold the wording inside the graph to emphasize its presence
* Change the footnote to emphasize data is being excluded
* Slow the animation to allow the eyes to understand the change

Review #4 Feedback:
* Make main title of graph more explanatory 
* Add short introductory paragraph above graph to explain your main conclusion from the visualization
* legend and tooltip labels - these could be clearer. i.e. "Median Actual Return" instead of "Median_Actual_Return" or 
"Prosper Loan Credit Rating" instead of "ProsperRating.Alpha"*.
* colour coding - it would be clearer if your bar labels had a different colour code. Currently they are the same as 
E and HR rating. You could go grey scale - grey and light grey?
* Actual Return > Estimated Return - these labels could go a bit bigger? They also need to be consistent - the 
bottom right hand label is abbreviated and the top left isn't.
* Bubble size - while I understand that it adds another dimension to your findings, I'm wondering whether your key 
message would be clearer without the z measure - i.e. keeping the bubbles the same size? This would allow you to 
make them all a little bit larger both on the chart and the key? And, if you are feeling up to the challenge, you 
could go the extra mile and add a third chart to your 'dashboard' - a pie chart or donut with the loan split for each year?



##Resources:

* http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control

* https://github.com/PMSI-AlignAlytics/dimple/blob/master/src/objects/axis/methods/addGroupOrderRule.js

* https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple#filterData

* https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#addOrderRule

* https://www.fool.com/knowledge-center/annualized-return-vs-cumulative-return.aspx

* http://www.investinganswers.com/financial-dictionary/bonds/effective-yield-1013

* http://stackoverflow.com/questions/19437701/how-to-calculate-any-negative-number-to-the-power-of-some-fraction-in-r

* https://discussions.udacity.com/t/annualized-return-measure/161846/3

* http://stackoverflow.com/questions/24459752/can-dplyr-package-be-used-for-conditional-mutating

* https://discussions.udacity.com/t/prosper-loan-definitions-calculating-investor-return/35762/4
