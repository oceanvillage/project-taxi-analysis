# project-taxi-analysis

## Overview<br>
  NYC Taxi and Limousine Commission (TLC) likes to generate more revenues for taxi drivers utilizing the data provided.<br>
  Try tree-based modeling technique to predict better chipper on a binary target class<br>
<br>

## Objective<br>
  Analyze the data and Advise NYC TLC the best approach to increase more revenue<br>
<br>
## Results<br>
![graph 1](/assets/graph_1.png)![graph 2](/assets/graph_2.png)<br>
![table 1](/assets/table_1.png)<br>
<br>
1) Recommend to use this XGB model. F1 score is 0.75 and Accuracy is 0.71. The test sets were predicted w/ 81% which is better than random guess by 31%.<br>
2) Random Forest is not a transparent model. Vendor ID definitely has an influence for the better prediction result.<br>
3) Pick up and Drop off locations seem to have an impact on the tipping amount. Maybe we can bring a new category for premium, medium, and low-end for pick-up and drop-off locations.<br>
<br>
## Notes>br>
project-taxi-analysis.ipynb is designed to work in Google COLAB.<br>
Please create folders such as "/REG" and "/data" underneath "gdrive/MyDrive" and place ipynb file under "Mydrive".<br>
Also, utilize write/read pickle as needed.<br>
<br>
