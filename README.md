# Facebook-Friend-Recommender
Facebook Friend Recommender System using Graphs

Data Overview
Taken data from facebook's recruting challenge on kaggle https://www.kaggle.com/c/FacebookRecruiting data contains two columns source and destination eac edge in graph

    Columns (total 2 columns):
    source_node - Type(int64)
    destination_node - Type(int64)

Mapping the problem into supervised learning problem:

Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.
Business objectives and constraints:

No/low-latency requirement. Probability of prediction is useful to recommend highest probability links.
Performance metric for supervised learning:
Both precision and recall is important so F1 score is good choice Confusion matrix. 
