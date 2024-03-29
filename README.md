# Building Recommendation System with Deep Reinforcement Learning and Neo4j

In this tutorial We will be building a movie recommendantion enine leveraging a blend of graph-based machine learning and deep reinforcement learning (DRL). This post details an approach using [Neo4j](https://neo4j.com) graph embeddings, generated through Node2Vec algorithm, combined with a PyTorch-based Deep Q-Network (DQN) for dynamic movie recommendations.
We will be using the [DVD Rental Database](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/) that we have used in a couple of posts before. We showed how we can download and populate the data into Neo4j database in this previous [tutorial](https://minimatech.org/from-relational-to-neo4j/). We will also be leveraging the [Graph Data Science](https://neo4j.com/product/graph-data-science/) (GDS) library in Neo4j to get the Node2Vec embeddings.

Let's quickly try to do some imports and do quick queries on the database to make sure everything is ready. We will query the labels of nodes and types of the relationships.
