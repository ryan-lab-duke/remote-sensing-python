# Remote Sensing in Python

This repository hosts course materials for **Remote Sensing for Earth and Environmental Science** designed by [Johnny Ryan](https://nicholas.duke.edu/people/faculty/ryan).

## Repository structure

The Python package [`jupyter-book`](https://jupyterbook.org/intro.html#install-jupyter-book) processes the Jupyter notebook files from this repository and outputs them as the publication-quality HTML files that generate the [corresponding website](https://ryan-lab-duke.github.io/remote-sensing-python/).

The HTML files are currently hidden in this branch of the GitHub repository, but you can find them in the [gh-pages branch](https://github.com/ryan-lab-duke/remote-sensing-python/tree/gh-pages).

## Build

The book can be updated by running:

`jupyter-book build book/`

`ghp-import -n -p -f book/_build/html`

## License

This book is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
