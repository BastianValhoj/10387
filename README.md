Bastian Valhøj Kristensen, August 2025.

# Packages used
* NumPy
* MatPlotLib
* SciPy
* Jupyter Notebook
* QuTiP
* Seaborn

Create virtual environment (venv) before installing packages (duh!).  
### Example for `conda` users:  
`$ conda create -n <venv-name> numpy matplotlib scipy notebook qutip seaborn -C conda-forge`

Of course the `<venv-name>` is a placeholder and should be named something memorable and meaningfull like `course-10387`, `qutip-venv`, or similar.

The `-C conda-forge` adds the channel "conda-forge" to possible package repos (needed for `QuTiP`).  

Activate environment using `$ conda activate <venv-name>`

