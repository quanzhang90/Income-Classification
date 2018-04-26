# Income-Classification

In this project, I employed several supervised algorithms to accurately classify individuals' income using data collected from the 1994
U.S. Census. Among those models I chose the best candidate algorithm from preliminary results and further optimize this algorithm to best
model the data. My goal with this implementation is to construct a model that accurately predicts whether an individual makes more than
$50,000. While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will 
see) infer this value from other publically available features.  

The dataset for this project originates from the UCI Machine Learning Repository. The datset was donated by Ron Kohavi and Barry Becker, 
after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". You can find the 
article by Ron Kohavi online. The data I investigated here consists of small changes to the original dataset, such as removing the 'fnlwgt'
feature and records with missing or ill-formatted entries.
