# GraphEmbedding4DDI

In this work, we aimed to present realistic evaluation settings to predict DDIs using knowledge graph embeddings. We have applied Logistic Regression, Naive Bayes and Random Forest on Drugbank knowledge graph with the 10-fold traditional cross validation using RDF2Vec, TransE and TransD. We also propose a simple disjoint cross-validation scheme to evaluate drug-drug interaction predictions for the scenarios where the drugs have no known DDIs.
 
We performed cross-validation using different setting:

### Traditional CV:
- ddi_predict_traditional.ipynb
### Proposed disjoint CV:
- ddi_predict_disjoint.ipynb
### Time-slice CV:
 - ddi_predict_timeslice.ipynb


