# Deep-Learning-Workshop

==

### Requirements:
* Python **2.7** is the required version of Python for these classes. 
* ***Python*** [Installation Instructions](https://www.python.org/downloads/)
  * Once installed, make sure you add C:\Python27 and C:\Python27\Scripts to your ```%PATH```. This is important for windows users-[follow this link to learn how to add the path to your enviromental variables in windows](http://stackoverflow.com/questions/21372637/installing-python-2-7-on-windows-8)
* Python libraries required: **IPython notebook**, **Numpy/scipy**, **theano**, **lasagne**.

**==> If you have an existing Python 2.7 installation and you are a Mac user install the following packages:**
* ***pip*** (*should be installed on recent Python distributions*) -  [Installation instructions](http://python-packaging-user-guide.readthedocs.io/installing/#install-pip-setuptools-and-wheel). For windows users: If pip is not recognized make sure it is added to the path - [Follow instruction on this error here](http://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command)
* ***Numpy/scipy***:    ```pip install numpy``` - [Installation instructions](http://www.scipy.org/scipylib/building/index.html)
* ***lasagne***:  [Installation instructions](http://lasagne.readthedocs.io/en/latest/user/installation.html)
* ***theano***:  [Installation instructions](http://deeplearning.net/software/theano/install.html)
* ***IPython notebook*** - ```pip install jupyter``` - [Installation instructions](http://jupyter.readthedocs.org/en/latest/install.html)

**==> If you are a windows user follow the steps below for simple installation of Theano and Lasagne under Anaconda:**

Python Anaconda is a fully-featured Python installation for scientific computing and contains numpy and scipy.

* ***Python Anaconda*** (fully-featured Python installation for scientific computing): [Installation instructions](http://docs.continuum.io/anaconda/install) - Choose the **Python 2.7** for windows 32 or 64 installation depending on your machine. Make sure you add the path of your Anaconda2 to enviroment variables similarly.
  * Once Anaconda is installed open a terminal and install the following packages:
  * ***Theano***: ```conda install theano```
  * ***mingw***: ```conda install mingw libpython```
  * ***Lasagne***: ```conda install lasagne```
     
     
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
