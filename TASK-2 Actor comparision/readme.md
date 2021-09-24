## Overview
I have used sentiments analysis to how many positive sentiment comments are there for each actor.
## Specifications
The comments contained many emojis, hence in the first step I converted the emojis to text in order to get a better outcome in the final sentiment analysis.

After that I segregated the comments containing AYUSH  and BARKHA , Mostly the comments contained both their names, hence I made another column for BOTH.
Finally, I used PunktSentenceTokenizer to get individual sentences.
Finally, the total number of sentences containing BOTH,AYUSH & BARKHA were (1786, 850, 890).
After the preprocessing steps, I used SentimentIntensityAnalyser to get the extent of positiveness and negativeness in the sentences.

After all these steps, these were the final plots  :\

![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-2%20Actor%20comparision/plots/dual.png)


And for the final comparison plot:
![](https://github.com/shaurysrivastav27/Pocket-aces-assignment/blob/master/TASK-2%20Actor%20comparision/plots/final.png)


From the above operations, the conclusion made was, audience responded to both the actors almost equally.
