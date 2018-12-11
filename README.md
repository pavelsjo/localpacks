# Basic Tools


- Install [ANACONDA](https://www.anaconda.com/download/) view many examples in [Anaconda Gallery](https://anaconda.org/gallery)

- Enable [JupyterLab Extensions](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator)
    - [Snippets Menu](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/snippets_menu/readme.html)
    - [Table of Contents (2)](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/toc2/README.html)
    - [Gist it](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/gist_it/readme.html)

# Save the current KERNEL 

```python
import dill
dill.dump_session('notebook_env.db') #save the current kernel

import dill
dill.load_session('notebook_env.db') #restored the previusly saved kernel
```