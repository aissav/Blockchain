# Blockchain in the Era of Deep Learning and Graph Theory (_Review and Open Challenges_)
## _Graph Theoretical Measurements To Analyze Blockchain Networks_


We employ two different datasets for our implementations and results. 

    - We employ Ethereum public datasets for data exploratory analysis (EDA) and analyzing the centrality of blockchain nodes. For this, we use Ethereum collected using  Google BigQuery. This forever free public dataset in which it is created and updated for the public to avoid the overcharge by GCP.

    - The first dataset consists of the first publicly available explicit weighted signed network of a who-trusts-whom directed network (network of bitcoin transactions) [1-2]. Since Bitcoin users are anonymous, a record of their reputation is required to prevent transactions with fraudulent and risky users. Members of Bitcoin OTC score each other on a scale of -10 (total distrust) to +10 (total trust) in increments of one.
    The dataset consists of 5,881 nodes, 35,592 edges, and 89\% of positive edges.

## Objectives
- Etherium Centrality Analysis.
- Investigating the impact of deep learning (DL) and graph theoretical measurements (GTMs) on blockchain systems and discussed various metrics to analyze Bitcoin/Ethereum networks. 
- Implementing some graph theoretical measurements to analyze the centrality/decentrality of Bitcoin/Ethereum networks. 
- We applied various supervised techniques, including Logistic Regression, Random Forest Classifier,
Gradient Boosting Algorithm and multiple Neural Network Models to predict edge weights for an architectural component of Blockchain (Nodes in this case) to enhance Blockchain transactions on Bitcoin OTC Network.

## Requirments

- Netwotkx
- Keras
- Tensorflow
- Numpy
- Pandas
- TQDM


## References

[1] Srijan Kumar, Francesca Spezzano, VS Subrahmanian, and Christos Faloutsos. Edge weight prediction in weighted signed networks. In Data Mining (ICDM), 2016 IEEE 16th International Conference on, pages 221–230. IEEE, 2016.

[2] Srijan Kumar, Bryan Hooi, Disha Makhija, Mohit Kumar, Christos Faloutsos, and VS Subrahmanian. Rev2: Fraudulent user prediction in rating platforms. In Proceedings of the Eleventh ACM International Conference on Web Search and Data Mining, pages 333–341. ACM, 2018



