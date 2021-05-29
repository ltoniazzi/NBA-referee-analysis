# NBA-referee-analysis
This notebook contains an analysis of referees' effectiveness in the last 2 minutes of an NBA the game. The analysis is based on Bayesian hierarchical models, performed with [PyMC3](https://docs.pymc.io/).



### How to easily use this notebook
### 1. Clone the repository locally

In your terminal, use `git` to clone the repository locally.

```bash
git clone https://github.com/necbal/NBA-referee-analysis.git
```

### 2. Download Anaconda

Download the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3.

### 3. Set up your environment

If this is the first time you're setting up your compute environment,
use the `conda` package manager
to **install all the necessary packages**
from the provided `environment.yml` file.

```bash
conda env create -f environment.yml
```

To **activate the environment**, use the `conda activate` command.

```bash
conda activate NBA-referees-analysis
```

**If you get an error activating the environment**, use the older `source activate` command.

```bash
source activate NBA-referees-analysis
```

To **update the environment** based on the `environment.yml` specification file, use the `conda update` command.

```bash
conda env update -f environment.yml
```




### 4 Open your Jupyter notebook in Jupyter Lab

In the terminal, execute `jupyter lab`.
