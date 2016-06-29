# OPUG-Jupyter
A beginner's overview of how to use Jupyter notebooks for data science.

## Installing Jupyter 

[http://jupyter.readthedocs.io/en/latest/install.html](http://jupyter.readthedocs.io/en/latest/install.html)

If you have Python installed and are somewhat experienced with installing packages using pip:

pip3 install jupyter

Otherwise, Install Jupyter using Anaconda and conda - which installs Python, the Jupyter notebook and other commonly used packages for scientific computing and data science.

[https://www.continuum.io/downloads](https://www.continuum.io/downloads)

## Running the Jupyter notebook

http://jupyter.readthedocs.io/en/latest/running.html#running

jupyter notebook

This starts the notebook server locally at [http://localhost:8888](http://localhost:8888) by default and opens the browser there.  Changing port -   jupyter notebook --port 9999

jupyter notebook --help

And brings up the Notebook Dashboard.  

## Notebook Dashboard

Shows a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. Most of the time, you will wish to start a notebook server in the highest level directory containing notebooks. Often this will be your home directory.

## Navigating a Notebook

* Cells - Each cell represents a chunk of code, either a single line or a few.  A cell can also be of markdown type (change by using the dropdown menu) to add comments and extra notes.

* Running cells - Each cell is run individually, by selecting run from the menu or shift/enter.  You can also go back and edit cells and then re-run them all.

* Saving - Auto-saves the notebook locally every few minutes.

* Markdown - Make your notebook like a document by adding markdown.

* Closing and reopening - since you can run/re-run each cell individually, the notebook doesn’t run any of the cells by default, so when you re-open a document either go through and run them all or select run all.

## Tutorial

Based on:  [http://nbviewer.jupyter.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_12_pandas_groupby.ipynb](http://nbviewer.jupyter.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_12_pandas_groupby.ipynb)

Data found:  [https://catalog.data.gov/dataset/baby-names-from-social-security-card-applications-national-level-data](https://catalog.data.gov/dataset/baby-names-from-social-security-card-applications-national-level-data)

Git repository for this Talk:  https://github.com/sarahbees/OPUG-Jupyter/

## PYCON Talks/Tutorials with Jupyter

**Favorite: ** BUILDING A QUANTITATIVE TRADING STRATEGY TO BEAT THE S&P500, by Karen Rubin - VP of Product at Quantopian [https://us.pycon.org/2016/schedule/presentation/1697/](https://us.pycon.org/2016/schedule/presentation/1697/)

[https://www.youtube.com/watch?v=ll6Tq-wTXXw](https://www.youtube.com/watch?v=ll6Tq-wTXXw)

**Made documenting data science practices for articles better:  **IPYTHON NOTEBOOK IN DATA INTENSIVE COMMUNITIES: ACCELERATING THE PROCESS OF DISCOVERY - from Product Manager and Data Scientist at Yelp

[https://us.pycon.org/2016/schedule/presentation/2245/](https://us.pycon.org/2016/schedule/presentation/2245/)

[https://www.youtube.com/watch?v=5gy6svL1DuU](https://www.youtube.com/watch?v=5gy6svL1DuU)

**Tutorial, Jupyter for Beginners:**

DATA CARPENTRY: AN INTRODUCTION TO PYTHON FOR DATA ANALYSIS AND VISUALIZATION

[https://www.youtube.com/watch?v=Ws34Ho-1aDs](https://www.youtube.com/watch?v=Ws34Ho-1aDs)

Extra exercises:  [https://gist.github.com/camillescott/36a246aa0a470d12397092302689427f](https://gist.github.com/camillescott/36a246aa0a470d12397092302689427f)

## Other Resources:

List of best Jupyter notebook examples:  [http://nb.bianp.net/sort/views/](http://nb.bianp.net/sort/views/)

## Sharing Notebooks on Github

#### **Uses nbviewer to render notebooks**

The Notebook Viewer uses IPython's nbconvert to export .ipynb files to HTML.

If you have IPython installed you have access to the same functionality and many more formats by invoking ipython nbconvert at a command line. Starting in IPython 2.0, you should be able to export notebooks in other formats using the file menu in the IPython notebook application.


