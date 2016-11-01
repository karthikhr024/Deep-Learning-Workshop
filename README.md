# Deep-Learning-Workshop

==

### Requirements:
* Python **2.7** is the required version of Python for these classes. Fo windows users: make sure python path is added to your enviroment variables - [Instruction](http://stackoverflow.com/questions/21372637/installing-python-2-7-on-windows-8)
* Python libraries required: **IPython notebook**, **Numpy/scipy**, **Pandas**, **theano**, **lasagne**.

**==> If you have an existing Python 2.7 installation:**
* ***pip*** (*should be installed on recent Python distributions*) -  [Installation instructions](http://python-packaging-user-guide.readthedocs.io/installing/#install-pip-setuptools-and-wheel).
* ***IPython notebook*** - ```pip install jupyter``` - [Installation instructions](http://jupyter.readthedocs.org/en/latest/install.html)
* ***Numpy/scipy***:    ```pip install numpy``` - [Installation instructions](http://www.scipy.org/scipylib/building/index.html)
* ***lasagne***:  [Installation instructions](http://lasagne.readthedocs.io/en/latest/user/installation.html)
* ***theano***:  [Installation instructions](http://deeplearning.net/software/theano/install.html)
* ***Pandas***:   ```pip install pandas``` - [Installation instructions](http://pandas.pydata.org/pandas-docs/stable/install.html)

**==> If you don't have any Python 2.7 installation:**

Follow ***either*** one of the following bullets.
The first bullet provides  a minimal installation of Python, allowing you to control your Python installation. The second bullet installs Python Anaconda, a fully-featured Python installation for scientific computing.
* ***Python*** [Installation Instructions](https://www.python.org/downloads/)
  * Once installed, add C:\Python27 and C:\Python27\Scripts to your ```%PATH```.
  * Follow the steps in '==> If you have an existing Python 2.7 installation'.
* ***Python Anaconda*** (fully-featured Python installation for scientific computing): [Installation instructions](http://docs.continuum.io/anaconda/install) - Choose the **Python 2.7** installation.
  * ***Ipython notebook***: ```conda install jupyter```


### Download class materials
* **From Git**:
  * ***git***: [Installation instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  * ```git clone https://github.com/nhanteh/Deep-Learning-Workshop```

### Run IPython Notebook
**Anaconda distribution:**
* Copy the IPython Notebook launcher from the menu to the desktop.
* Right click on the new launcher and change the ```Start in``` field by pasting the full path of the folder which will contain all the notebooks: ```/path/to/Deep-Learning-Workshop```.
* Double-click on the IPython Notebook desktop launcher (icon shows [IPy]) to start the Jupyter Notebook App.

**Command line:**
* ```cd /path/to/Deep-Learning-Workshop```
* ```ipython notebook``` (```ipython/jupyter``` has to be in your ```PATH```)
