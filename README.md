# Hands-on with Blosc2: Accelerating Your Python Data Workflows (PyData Global 2025 tutorial)

Here you will find materials for the ironArray SLU tutorial on Python-Blosc2 for PyData Global 2025.

## What is Blosc2?

Look into these slides for a gentle intro to Blosc2 and its capabilities:
https://www.blosc.org/docs/2025-PyDataGlobal-Blosc2.pdf

## Preliminaries

Before the tutorial, it is advisable to have jupyter notebook installed (see [here](https://jupyter.org/install)).
This can be managed via Anaconda if you prefer (download [here](https://www.anaconda.com/download) and follow the instructions), 
but in the command line (Windows/Linux/MacOS) it is very simple.

Before installing Jupyter Notebook, make sure you have Python (version 3.10 or later) installed and ``pip``
```
python --version
pip --version
```

You may want to create an environment via
```shell
conda create --name testenv python=3.12
conda activate testenv
```
if you have ``conda`` installed.


You will still have to use ``pip`` to install the packages though.

### Clone this git repo

Use either SSH, url or a zip file (click on the green 'Code' button in the top right), making sure to clone into the relevant directory. 
One may navigate to the repo via the command line, or from the jupyter notebook web browser interface.

```
git clone https://github.com/Blosc/PyData-Global-2025-Tutorial.git
cd PyData-Global-2025-Tutorial
```

### Install dependencies

From the command line run
```
pip install caterva2[services] pip notebook jupyterlab psutils blosc2 matplotlib ipympl --upgrade
```

Finally, run the notebooks with:
```
jupyter lab
```

That should be it! Open the first notebook and check that the first few cells all run to be sure.
