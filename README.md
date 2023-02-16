# NER_neural-network_keras-tuner
A Named Entity is a unit, most often a noun phrase, which possesses a singular existence in the physical world. Named entities are typically noun phrases that contain the names of persons, organizations and locations. Named Entity Reccognition has evolved as a prominent field of study in Natural Language Processing that is
used to extract relevant information from a given dataset or corpus. A Bi-directional LSTM neural networks is used.

Most common challenges faced within Named Entity Disambiguation include scrambling of word order, absence of capitalization of the named entities and stripping lemmatization.

Hyperparamaters Tuning:
Hyperparameters are tuned using the keras-trainer library. The hyperparameter optimization algorithm I selected is Bayesian Optimization. The other optimizers (Random Search and Hyperband) can be run for a few trials to check for consistency of the hyperparameters obtained. When all three hyperparameter tuners converge to result in similar hyperparameters, they are usually the most optimal ones for the given model.


