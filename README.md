# qsar-methods

## Description
Jupyter notebooks can be a lot of fun but in the same time very useful in the initial stage of of exploring and learning before building and scaling to a bigger project. In this case I am exploring a minimal package for developling predictive ML models for small molecules.

1. **Data handling** A ```Dataset2D``` and a ```DataStructure``` classes take care of loading data in different formats, filtering for chemistry, calculating from a collection of fingerprints and descriptors using multiprocessing for efficiency, scaling/normalizing and providing ```X``` and ```y``` numpy arrays to be fed to the ML models.
2. **Training - hyperparameter optimisation** A number of popular ML algorithms are available for regression or classification. A ```Classifier``` wrapper class takes care of setting up a grid search for hyperparameters, training the models and providing predictions
3. **Testing** by cross validation with calculation of error estimates
4. **Visualisation** of models performance using different metrics and including error estimates
