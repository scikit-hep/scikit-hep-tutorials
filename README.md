# Scikit-HEP ecosystem tutorials

Repository collecting tutorials, demos and examples on how to exploit
the Scikit-HEP ecosystem packages.

### Local notebook testing and build

To install locally, make sure miniconda is installed then run from this
directory:

```bash
conda env create
conda activate scikit-hep-tutorials
python -m ipykernel install --user --name scikit-hep-tutorials
jupyter lab
```

Only the activate and lab lines need to be run once this is installed. Use
`conda env update` to bring the environment back up to date.

To build the notebooks:

```bash
jupyter-book build .
```


