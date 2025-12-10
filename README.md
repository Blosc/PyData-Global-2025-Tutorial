# Hands-on with Blosc2: Accelerating Your Python Data Workflows (PyData Global 2025 tutorial)

Here you will find materials for the ironArray SLU tutorial on Python-Blosc2 for PyData Global 2025.

## What is Blosc2?

Look into these slides for a gentle intro to Blosc2 and its capabilities:
https://www.blosc.org/docs/2025-PyDataGlobal-Blosc2.pdf

## Setup

Before the tutorial, it is advisable to have jupyter notebook installed (see [here](https://jupyter.org/install)).
This can be managed via Anaconda if you prefer (download [here](https://www.anaconda.com/download) and follow the instructions), 
but in the command line (Windows/Linux/MacOS) it is simpler.  You can also use uv, which is increasingly used (see below).

### Using Conda

```bash
conda create --name testenv python=3.12
conda activate testenv
pip install -r requirements.txt
```

### Using uv

If you prefer to use [uv](https://docs.astral.sh/uv/) instead of conda:

```bash
# Install uv if you haven't already
# curl -LsSf https://astral.sh/uv/install.sh | sh

# Create a virtual environment with Python 3.12 (or your preferred >= 3.10 version)
uv venv --python 3.12

# Activate the environment
source .venv/bin/activate  # On macOS/Linux; add .fish to the end of the line if you're using fish
# or
.venv\Scripts\activate  # On Windows

# Install dependencies
uv pip install -r requirements.txt
```

### Clone this git repo

Use either SSH, url or a zip file (click on the green 'Code' button in the top right), making sure to clone into the relevant directory. 
One may navigate to the repo via the command line, or from the jupyter notebook web browser interface.

```
git clone https://github.com/Blosc/PyData-Global-2025-Tutorial.git
cd PyData-Global-2025-Tutorial
```

Finally, run the notebooks with:
```
jupyter lab
```

That should be it! Open the first notebook and check that the first few cells all run to be sure.
