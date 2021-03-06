BayesianNetwork
===============

Construct and calibrate a Bayesian network from survey data. BayesianNetwork contains a set of routines for computing marginal probabilities in a Bayesian network using belief propagation.

## INSTALLATION

Unzip the source file and type:  python setup.py install

##### OR

Add the package path to python's system directory by:
```python
import sys
sys.path.append(PACKAGE_PATH_NAME)
```
Then import the Bayesian network routines with
```python
from BayesianNetwork.BayesNet import *
from BayesianNetwork.utils import *
```
Routines should now be in the python environment. See examples for further implementation details/ideas.

##### REQUIREMENTS

Requires numpy, and graphviz for graphical output.
pydot and IPython are optional.

