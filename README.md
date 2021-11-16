# Machine Learning With Graphs: Going Beyond Tabular Data 
### Talk presented at the Open Data Science West 2021 conference
### Written by Dr. Clair J. Sullivan, Data Science Advocate, Neo4j
#### email: clair.sullivan@neo4j.com
#### Twitter: @CJLovesData1
#### Last updated: 2021-11-16

## Abstract

Machine learning has traditionally relied on creating models around data that can be represented in tabular format such as SQL tables, Pandas dataframes, and the like.  Inherent in this data is the assumption that there is no relationship between each entry (row) of the data.  In certain cases this is an accurate assumption.  However, there are many common use cases for machine learning where this assumption is not entirely accurate.  In these cases, by considering the relationships among those individual data points, models can be significantly enhanced and measurable improvements can be made to the appropriate metrics of that model.  Such use cases can include common data science and machine learning tasks such as churn prediction and automated recommendation engines.

In this talk we will compare and contrast models created with individual data points to those made entirely with graphs and hybrids of the two.  We will explore a variety of techniques that are used for creating graph embeddings, the vectors for representing graphs that are created in a similar fashion to the feature engineering and vector embeddings associated with traditional machine learning.  We will focus on the optimization of the graph embeddings and explore some real-world examples of their use individually and in conjunction with the traditional types of machine learning embeddings.  Special emphasis will be placed on the benefits of using graph embeddings with significant class imbalance.  We will also discuss the use of these embeddings with traditional machine learning packages and workflows, such as through the use of scikit-learn and TensorFlow.

### Code and slides

The slides for this talk are available in this repository.

The code used for this talk can be found in [this Google Colab Notebook](https://dev.neo4j.com/classic_vs_graph_ml).  Lastly, I have written a blog post on Towards Data Science that walks through this process in much more detail, which can be found here.





