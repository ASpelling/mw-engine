# mw-engine
Engine to improve the return of MW-Trading

Using ML techniques to find favourable indicators such as can be used to be implemented in MW-Trading improving the return of investment. Using a script to loop through historical data to create samples and extract possible features. Probablility for profit without predicting is about 23%. At this point the prediction probablility has improved to about 50% using ML prediction, F1 value of about 0.35. As the possible trades are many it is believed that it is more important to improve the precision rather than the recall. 

### Feature engineering
Main influencer wheather a buy will be successfull or not seem to be related to the Index indicators more than the individual asset indicators. Believed that the clustering ML will be able to provide improved features in a later step for overall improvements.

### Classification:
Implementing a neural network from a set of features to predict outcomes. 

Feature engineering
- Asset related
- StockEx related
(- Industry related - see below in Clustering)
(- Other influences - see below in Clustering)

### Clustering:
Later step to cluster assets to indentify additional features
