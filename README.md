# Video Compression Assignment 3

## Task descriptions

See the [`resources/assignment.pdf`](./resources/assignment.pdf) for more information.

## Solutions and outputs

See the [`notebooks/assignment.ipynb`](./notebooks/assignment.ipynb) for the solutions and outputs.

The PDF report generated from the notebook can be found at [`docs/README.pdf`](./docs/README.pdf)

## Development

### Prerequisites

- Programming langauge: Python 3.10+ (IPython)
- Framework: Jupyter

```shell
pip install -Ur requirements.txt
```

### Formatting

```shell
python -m black --line-length 80 . 
```

### Printing PDF

```shell
jupyter nbconvert notebooks/assignment.ipynb --execute --to webpdf --output-dir docs/ --output README
```
