# Installing Python for data analysis and visualization

## Anaconda

[Continuum Analytics][continuum], a data analysis company, provides a nice Python distribution for data analysis and visualization. It is called [Anaconda][conda] and you can freely download and use. It is usually the easiest solution to install and maintain necessary Python packages for data analysis, regardless of your platform. Here is the download link:

- [Download Anaconda](https://www.anaconda.com/download)

After installing it, you can keep it updated by executing `conda`. 

    conda update conda
    conda update anaconda

With `conda`, you can also install many Python packages. For instance:

    conda install pandas

## Without Anaconda

If you use Mac or Linux and does not want to use Anaconda, you can install packages by using Python's `pip` program.  Install Python using either [homebrew][brew] or the [official Python download][python-download]. Use `pip` (or `pip3`) to install necessary packages. You can run

     pip3 install numpy scipy networkx jupyter jupyterlab ipython pandas matplotlib seaborn bokeh scikit-learn

to install most packages that you can use for data analysis and visualization.

## Jupyter notebook

Once you have `Jupyter lab` (or notebook) (`Anaconda` creates a shortcut), you can simply run 

    jupyter lab 
or 

    jupyter notebook 

in the shell or use the launcher to launch ipython notebook. A browser window will appear and show the `IPython notebook` interface. From here, you can create your notebooks and load other notebooks.  

# Cloud options

There are also a variety of cloud-based options where you can run Jupyter notebook on the cloud. You may find them more convenient. Of course it may be more difficult to install the packages that you want. 

## Kaggle

- https://www.kaggle.com/kernels

## Google's colaboratory

- https://colab.research.google.com/notebook


[conda]: http://continuum.io/downloads
[python-download]: https://www.python.org/downloads/
[brew]: http://brew.sh/
[continuum]: https://anaconda.org/anaconda/continuum-docs
[wakari]: https://wakari.io
