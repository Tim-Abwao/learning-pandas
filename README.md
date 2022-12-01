# Learning Pandas

[![Binder](https://mybinder.org/badge_logo.svg)][binder-run]

A collection of [Jupyter notebooks][jupyter] based on [pandas' documentation][pandas-docs]. For conveniently trying out examples.

## Getting started

You can [run the notebooks online][binder-run], courtesy of [Binder][binder].

To set up a local environment:

```bash
git clone https://github.com/Tim-Abwao/learning-pandas.git
cd learning-pandas
python3 -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

Afterwards, launch *JupyterLab* and select a notebook ( *.ipynb file) to run.

```bash
jupyter-lab
```

[binder-run]: https://mybinder.org/v2/gh/Tim-Abwao/learning-pandas/HEAD
[jupyter]: https://jupyter.org
[pandas-docs]: https://pandas.pydata.org/docs/
[binder]: https://mybinder.org
