# Learning Pandas

[![Binder](https://mybinder.org/badge_logo.svg)][binder-run]

A collection of [Jupyter notebooks][jupyter] based on [pandas' documentation][pandas-docs], for conveniently trying out examples.

You can [run the notebooks online][binder-run], courtesy of [Binder][binder].

## Running locally

1. Fetch the necessary files, and create a virtual environment:

   ```bash
   git clone https://github.com/Tim-Abwao/learning-pandas.git
   cd learning-pandas
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install required packages:

   ```bash
   pip install -U pip
   pip install -r requirements.txt
   ```

3. Launch *JupyterLab* and open one of the notebooks in [/notebooks](/notebooks/).

   ```bash
   jupyter-lab
   ```

[binder-run]: https://mybinder.org/v2/gh/Tim-Abwao/learning-pandas/HEAD
[jupyter]: https://jupyter.org
[pandas-docs]: https://pandas.pydata.org/docs/
[binder]: https://mybinder.org
