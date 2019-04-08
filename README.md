# Pitch Profiles Exercise

## Getting Started

1. Install [git](https://git-scm.com/) or the [GitHub desktop app](https://desktop.github.com/).
2. Clone this repository.
3. Setup `python` and `jupyter`.
   - If you have not used python and/or jupyter before, see below for installation instructions.
4. Install `pandas` and `seaborn` (again, see below)
5. Run `jupyter` and open the notebook `pitch_profiles.ipynb`

## Installing Python

If you have not installed python before or don't know how to get started, follow these steps:

1. [Install `conda`](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).
   Go to "Regular Installation" and select your operating system.
   We advise to install Miniconda instead of Anaconda, as it does not require a 3Gb download.
2. Start conda (Windows) or a terminal (Mac/Linux)
3. Create a new environment using
   ```
   conda create --name pitch_profiles
   ```
   Environments are useful to install dependencies for different projects separately.
4. Activate your new environment using
   ```
   conda activate pitch_profiles
   ```
5. Once the `pitch_profiles` environment is active, install `jupyter`, `pandas`, and `seaborn`:
   ```
   conda install jupyter pandas seaborn
   ```
6. Run jupyter using
   ```
   jupyter notebook
   ```
   You browser should open a new tab with jupyter.
   Navigate to the repo that you cloned before and start the notebook `pitch_profiles.ipynb`.
7. Enjoy!

If you are not using `conda`, use `pip install` to install your packages.
You might want to use a virtual environment in that case.
