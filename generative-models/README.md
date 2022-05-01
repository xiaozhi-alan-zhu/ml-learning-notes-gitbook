# Generative models

The "Generative modeling" is a broad area of machine learning which deals with models of distributions $$P(X)$$, defined over datapoints $$X$$ in some potentially high-dimensional space $$\mathcal{X}$$. One often cares about producing more examples that are like those already in a database, but not exactly the same. 
Training this type of model has been a long-standing problem in the ML community and most approaches have had one of three serious drawbacks:
1. They might require strong assumptions about the structure in the data.
2. They might make severe approximations, leading to sub-optimal models.
3. They might rely on computationally expensive inference procedures like Markov Chain Monte Carlo.
