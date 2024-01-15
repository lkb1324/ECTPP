---------README---------


This code can run on CPU environments of Python 3.6 and above (tested on CPU environments of Python 3.6 and Python 3.9)



Code: 

ECTPP: it is the main running code. 
Running the file train.py can run the model in this paper, and the required data is in the same file directory

Data processing: used to construct a user-topic hypergraph, fuse duplicate user hyperedges, and calculate the ChatGPT heat index for each topic



Data: 

Raw data: original data on topics related to ChatGPT on Weibo and Twitter, including data directly obtained from Weibo and Twitter, selected topics for constructing hypergraphs, and related tweets; 

The preliminary processed data includes information on the aforementioned topics as well as user information on tweets;

 The further processed data includes the constructed hypergraph incidence matrix, hyperedge weights, and fused hyperedge features