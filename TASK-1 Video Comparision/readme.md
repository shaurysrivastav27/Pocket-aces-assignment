## Overview
I have implemented sentiment analysis using the python library called nltk.  
## Specifications
First, I implemented the stop words removal technique in order to remove the most common occurring words which do not contribute much to the sentiment analysis.
After that, I used SentimentIntensityAnalyser to check the degree of positiveness and negativeness in  comments. But most of the comments turned out to be neutral.
![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-1%20Video%20Comparision/plots/before_emoji.png)

This problem was mainly due to :
Most of the comments contained emojis only.
Most of the comments contained Hindi words which were missing from the Vader lexicons. 
I used the emoji library of python to convert emojis to text to get most features from the texts. After that, I added the most commonly used Hindi words for better understanding of the text.


After applying these methods, the final value count became better :

![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-1%20Video%20Comparision/plots/afterall.png)

Finally, I used the SentimentIntesityAnalyser to get the final percentage of negative and positive comments.
Below are the final comparison plots :

![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-1%20Video%20Comparision/plots/dual_plots.png)

As it is clear from the barplot , that If Salary Were a Person had better response from people .
Here, the orange plot is for the If Salary Were A Person  and blue is for Every Exam Preparation Ever.

![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-1%20Video%20Comparision/plots/finapol.png)
