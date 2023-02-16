Named Entity Recognition with keras and keras-tuner
A Named Entity is a unit, usually a noun phrase, which possesses a singular existence in the physical world. Named entities are typically noun phrases that contain the names of persons, organizations and locations. Named Entity Recognition has evolved as a prominent field of study in Natural Language Processing that is used to extract relevant information from a given dataset or corpus.

Systems using deep neural networks are one of the most recent developments in the field. A Bi-directional LSTM neural network is used in this program, built using the keras library.

Hyperparameters Tuning:
Hyperparameters are tuned using the keras-trainer library. The hyperparameter optimization algorithm I selected is Bayesian Optimization. The other optimizers (Random Search and Hyperband) can be run for a few trials to check for consistency of the hyperparameters obtained. When all three hyperparameter tuners converge to result in similar hyperparameters, they are usually the most optimal ones for the given model.

The kaggle dataset used can be found here:  https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus 

Most common challenges faced within Named Entity Disambiguation include scrambling of word order, absence of capitalization of the named entities and stripping lemmatization. In this case, the dataset is clean and required no preprocessing.
