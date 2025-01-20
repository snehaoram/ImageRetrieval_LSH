# ImageRetrieval_LSH
- This is course project on implementation of the paper [1] in CS635: Information Retrieval & Mining for Hypertext & the Web in IIT Bombay.
- For a given query image, the task is to predict similar images following three methods - (i) K-Means clustering (ii) Random locality sensitive hasing (LSH) (iii) Neural locality sensitive hasing (LSH)
- With K-Means clustering, the performance of precision@1, precision@10, and MRR are analyzed with increasing and decreasing number of clusters and with dimensionality reduction by PCA.
- With random LSH, the number of hyperplanes and number of hashtables are taken as hyperparameters to analyze the models's performance with reference to the same three metrics.
- With neural LSH, three loss functions (bit balance, no sitting on the fence, weak supervision) are aggregated for the training process to bring the retrieved image labels near the query labels.


# Reference
[1] Roy, I., De, A. and Chakrabarti, S., 2021, May. Adversarial permutation guided node representations for link prediction. In Proceedings of the AAAI conference on artificial intelligence (Vol. 35, No. 11, pp. 9445-9453).
