# Tooth Image Analysis

Repository for exploring how to process tooth image files for analysis using machine learning.

The image files may be either 2D or 3D.

## Virtual environment setup
- To create a virtual environment run the command `python -m venv venv`. 
  This will create a virtual environment in the `venv` directory. You can specify a different directory name if you wish.
- Run `source venv/bin/activate` to activate (i.e., run) the virtual environment.
- **After** activating the environment, install the project libraries using the command `pip install -r requirements.txt -U`.

## Jupyter hack for virtual environments
Jupyter notebooks won't necessarily have access to the libraries installed in the virtual environment.  
One hack to get around this is to create a softlink to the Jupyter binary created in the virtual environment like so `ln -s venv/bin/jupyter`.

You can then start Jupyter within the virtual environment using the softlink. E.g., `./jupyter lab`.  
The allows the Jupyter notebook to access the libraries in the virtual environment.

Another option is create a Jupyter kernel from the virtual environment. See [here](https://towardsdatascience.com/link-your-virtual-environment-to-jupyter-with-kernels-a69bc61728df) for details.


