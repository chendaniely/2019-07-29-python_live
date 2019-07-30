# 2019-07-29-python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chendaniely/2019-07-29-python_live/master)

Install Python using Anaconda: https://www.anaconda.com/distribution/

We will be using the Jupyter Notebook (via jupyter lab) which is pre-installed with the Anaconda distribution

Getting the data:

1. If you know git, you can `clone` this repository.
2. If you do not know git, there is a green "Clone or download" button on the top of the page.
  You can click "Download ZIP" to download the contents of this project (including the datasets).

## Test your installation

If you can run the following lines in Python without error, you should be good to go

```python
import pandas as pd
import seaborn as sns
import sklearn as sk
```

As a plug: you can try my new package to load datasets in a project:

https://github.com/chendaniely/pyprojroot

```
pip install pyprojroot
```

You can load it using

```python 
from pyprojroot import here
```
