# Uncertainty Modelling for Engineers

This repository contains the source code for Uncertainty Modelling for Engineers.

The book can be read online *here* . Alternatively a pdf is available here.  
TODO: Update links when project made public

## How to make a contribution

This book is an open source project; all readers are heartily invited to contribute with corrections and improvements.

Pull requests are most welcome.
To make a contribution you should first familiarise yourself with [JupyterBook](https://jupyterbook.org).
If you are making a major change you may first wish to discuss the change by opening a GitHub issue.

## Usage

### Building the book

If you'd like to develop on and build the book, you should:

- Clone this repository
- Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `uncertainty-book/_build/` directory
- Run `jupyter-book build uncertainty-book/`

A fully-rendered HTML version of the book will be built in `uncertainty-book/_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. A GitHub actions workflow has been created that automatically builds and pushes the book to this branch on a push or pull request to main.

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
