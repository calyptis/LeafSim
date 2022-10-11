# Purpose of repo

This repository introduces `LeafSim`, an example-based **explainable AI** (**XAI**) technique for decision tree based ensemble methods.<br/>
The process applies the Hamming distance on leaf indices to measure similarity between instances in the test and training set.<br/>
It therefore explains model predictions by identifying training data points that most influenced a given prediction.

The proposed technique is:
- easy to interpret by non-technical people
- complementing existing XAI techniques
- straightforward to implement & maintain in production
- computationally lightweight

# Structure of repo

- `notebooks/LeafSim.ipynb` contains the code producing the results and content referenced in the blog post.
- `data/` contains the sale prices of used cars as downloaded from Kaggle](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes?select=merc.csv).