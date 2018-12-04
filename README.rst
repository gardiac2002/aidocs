
======
AIDOCS
======


Best practices
===============

Feature Engineering
--------------------

* Use a fast subset of your data for feature engineering. When you feel comfy and confident you
  can make the long-lasting calculation later. But do not try it in an interactive session.
  However, the validation set should stay the same size.

Training data
-------------

* Replace strings with categories.
* Order categories if possible.
* Consider to replace missing values with the median and add a variable (_na).

* Use a training, validation and testing set. Use the test set at the real end.

Evaluation data
---------------

* Try to use data "in the future" to see if you really can model predictions.


Result and Evaulation
----------------------

* Check what is the evaluation metrics and change your determinant variable 
  accordingly.

* Check the data which kaggle uses for the test set. Is it a randomly chosen
  one or somewhere in the future.


