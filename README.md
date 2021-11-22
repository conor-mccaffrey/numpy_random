# GMIT HDip Data Analytics 2021
 
## Programming for Data Analysis <br> An investigation into the numpy.random package
### Conor McCaffrey
***
You can view the static version of the notebook by clicking the following button:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/conor-mccaffrey/numpy_random/blob/50a587b61dc10702034ab89e86b5a2cc46815d2a/numpy_random.ipynb)


Alternatively, you can view the notebook in dynamic form by clicking the following button :

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/conor-mccaffrey/numpy_random/HEAD?labpath=numpy_random.ipynb)


## Assignment Overview
This assignment is a brief overview of the use and purpose of the numpy.random package.
There are <b>four</b> distinct tasks that have been addressed in this Jupyter notebook:

1. Explain the overall purpose of the package.

2. Explain the use of the “Simple random data” and “Permutations” functions.

3. Explain the use and purpose of at least five “Distributions” functions.

4. Explain the use of seeds in generating pseudorandom numbers.

## Packages Used in the Assignment
The following packages have been incorporated for use in the notebook: 

```Python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import scipy.special as sps  

# This  line-orientated magic command, as outlined in lectures, lets us display plots inline
%matplotlib inline
```
Numpy is the primary Python library for scientific computing [1].

Pandas is primarily used for data manipulation and analysis in Python [2].

Matplotlib.pyplot is the foundation of plotting in Python.

Seaborn is also a data visualisation library in Python, which was incorporated for two reasons : to show outside learning/research and also because it displays graphs quite nicely [3]. 

Scipy.special is a Python libray used for scientific computing and technical computing [4]

VSCode (Visual Studio Code) was also used in completing this README file. I like to use VSCode as there is an option called 'Markdown Preview Enhanced' which lets you visualise your README file in realtime.
https://code.visualstudio.com/


## How to run the Jupyter Notebook
For this assignment, I used both Jupyter Notebook and Jupyter Lab at various stages. The asssignment should render on both (and GitHub) without any difficulty. Here are some instructions on how to run the notebook.

1).  Download the Anaconda Distribution for Python 3.8.8. Anaconda also contains Jupyter Lab and Jupyter Notebook
https://www.anaconda.com/distribution/

2). Go to Github web site and search for 'conor-mccaffrey'
https://github.com/conor-mccaffrey


3). Enter the Repositories section, and select the repository called 'numpy_random'. 

* Another way to achieve the same result is to clone the SSH and enter the following script into cmdr:
git clone https://github.com/conor-mccaffrey/numpy_random.git
This will clone the repository on your local machine.

* Ensure NumPy is running version 1.21
* Refer ti requirements.txt for info on modules incorporated

### Some thoughts on the Assignment
I found the assignment to be a brilliant way to delve into the numpy.random package while concurrently learning the functionalities of Jupyter. To get into a project and start coding/doing hands on work, is much more beneficial than simply reading about how a program works. One thing that I found frustrating however was the cross-over between Jupyter and GitHub. For the most part, this was seamless however at the end my pictures (which rendered on Jupyter with no issue) would not appear correctly on GitHub. This forced me to change the coding for the pictures. Initially, I had referenced downloaded images using the standard coding "!(xxx)[xxxxx.png/jpg]" however this no longer worked suddenly. I searched GitHub on Google and it appeared there was a software update recently however whether this is related I am unsure. I searched online extensively for a workaround which I found by then simply 'dragging' the image onto the Jupyter notebook. This is crude and makes the file quite large but works. 
Other than that one issue(which took time so solve), I found the crossover okay. It was very interesting to learn how the values generated from numpy.random are in fact 'pseudo-random' and with the incorporation of 'Seeding', we can predict the set values that are generated.
I approached the project quite methodically, breaking the assignment down into smaller sections and noting references as I progressed. I hope the resulting Jupyter notebook displays what I have learnt about both the package and also what I have learnt in the use of Jupyter.

<i> Thank you. </i>

## References
1. https://www.activestate.com/resources/quick-reads/what-is-numpy-used-for-in-python/
2. https://pandas.pydata.org/
3. https://seaborn.pydata.org/
4. https://scipy.org/