# Learning Pandas

[![Binder](https://mybinder.org/badge_logo.svg)][1]

A collection of [Jupyter notebooks][2] based on the  [official Pandas documentation][3]. These are meant to help anyone going through the *pandas docs* to conveniently try out the described code examples.

## Getting started

You can [run the notebooks online][1], right from your browser, courtesy of [Binder][4].

To set up a local environment, download the files:

```bash
git clone https://github.com/Tim-Abwao/learning-pandas.git
cd learning-pandas
python3 -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

Then launch the notebook server and select a notebook ( *.ipynb file) to run.

```bash
jupyter notebook
```

[1]: https://mybinder.org/v2/gh/Tim-Abwao/learning-pandas/HEAD
[2]: https://jupyter.org
[3]: https://pandas.pydata.org/docs/
[4]: https://mybinder.org
