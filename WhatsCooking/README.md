What's Cooking
=======

This is the solution to the Kaggle machine learning competition What's Cooking: https://www.kaggle.com/c/whats-cooking 

It employs a fairly simple neural network classifier, giving a classification accuracy of around 81.818% 

Code is tested to work with Python 2.7 under Ubuntu 14.04 with GeForce GT 755M (cuDNN v2 was employed as well).

How to Run?
------------

Assuming *train.json* and *test.json* exist in the directory, from command line:

```
  python cook_it_up.py
```

A submission file will be autimatically created in the correct format.

Further Performance Improvement Possibilities
--------

Many things were not tried so there is room for performance improvement. Couple of ideas:
- Advanced text processing features, *e.g., tf-idf*
- Mapping certain words to eachother with normalized Levenstein distance, *e.g. mayonnais & mayonnaise*
- Hyperparameter optimization of the neural network *e.g. number of layers, number of units, activations, batch_size, regularization etc.*


