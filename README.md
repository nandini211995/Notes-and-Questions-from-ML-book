# Notes and Questions from ML book

# **Chapter 1 : The Machine Learning Landscape**

1. What is supervised learning? Name some most important supervised learning algorithms?
```diff
+ In supervised learning, training set has label information of inputs. 
+ Some algorithms name as: Linear Regression, Logistic Regression, Decision Tree, Random Forests, 
+ Support Vector Machine(SVM), k-nearest neighbours, Some neural networks.
```

2. What is unsupervised learning? Name some most important unsupervised learning algorithms?
```diff
+ In unsupervised learning, training data is unlabelled.
+ Clustering(K-means, DBSCAN, Hierarchical Cluster Analysis(HCA)), Anomaly Detection and novelty Detection
+ (One-class SVM, Isolation Forest), Visualization and dimensionality reduction ( Principal Component Analysis (PCA),
+ Kernel PCA, Locality Linear Embedding(LLE), t-Distributed Stochastic Neighbour Embedding(t-SNE)), Association
+ Rule Learning(Apriori, Eclat)
```

3. What is association rule learning?
```diff
+ Through association rule learning, we discover interesting relations between attributes in large amounts of data.
```

4. What is semisupervised learning?
```diff
+ In which data are partially labeled
```

5. What is reinforcement learning?
```diff
+ In this learning, agent learns from the environment, select and perform actions and get rewards(punishment) in return. 
```

6. What is batch learning(offline learning)? What are the disadvantages in it?
```diff
+ In batch learning, system must be trained using all the available data. 
+ Incable of learning incrementaly, take a lot of time, training on the full set requires a lot of computing resources.
```
7. What is online learning? What are the advantages?
```diff
+ Train the system incrementally by feeding it data instances sequentially, either individually or in small groups(mini batches). 
+ It also used to train systems on huge datasets that cannot fit in one machine memory.Then divide the datasets into parts and perform training.
```
8. What is learning rate ? Effect of low and high learning rate in the model?
```diff
+ It is important parameters of the model, how fast they should adapt to changing data; this is called learning rate.
+ High learning rate, model will rapidly adapt the new data but quickly forget to old data.
+ Low learning rate, model will learn slowly, it will also less sensitive to noise in the new data.
```

9. What is instance based learning? 
```diff
+ System learns the example by heart then generalizes to new cases by using a similarity measure to compare them to the learned examples.
```

10. What is model based learning?
```diff
+ Build a model of the set of examples and then use that model to make predictions.
```
11. Define utility function and cost function?

```diff
+ A utility function(fitness function) that measures how good your model is.
+ A cost function that measures how bad it is.
```


```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
