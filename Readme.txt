Librarys needed:
- NumPy
- SciPy
- matplotlib
- IPython
- pandas
- scikit-learn
- jupyterlab

linux/MacOs:
 pip install numpy scipy matplotlib ipython scikit-learn pandas pillow jupyterlab mglearn
(run in bash cmd, can be done from VScode terminal within venv aswell as witout venv)

To run jypyterlab browser extention, run: jupyter-lab in bash console

Throughout the book all the code (therefore our chapter examples) assumes these imports:

import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import mglearn
from IPython.display import display

if youre using matplotlib:
%matplotlib inline

Remember to run this in any new notebook (at the start of the file prefreably for style)