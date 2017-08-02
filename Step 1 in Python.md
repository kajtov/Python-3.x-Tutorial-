# Python 3.6.1
Download Python from the [official web site](https://www.python.org/downloads/). 
Once installation is done, open **Terminal** in your computer and type *python*. The output will provide an information of the version of **Python** available on your computer.

~~~python
# Input
python

# Output
Last login: Mon Jul 21 02:47:17 on ttys000
XXXX-MBP:~ username$ python
Python 3.6.1 |Anaconda 4.4.0 (x86_64)| (default, May 11 2017, 13:04:09) 
[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
~~~

If you were previewed Python of 2.x version, check for the 3.x version by typing. The ouput should be similar as above. 

~~~python
# Input
python3 --version
~~~

You can insert commands of code in the terminal, and everything you type will be executed there. As more user friendly ways exist to write your code, exit **Python** from the terminal.

~~~python
# Input
quit()

# The result of the command will close **Python**.
~~~

# Python GUI
## IDLE
One way to start writing your code is to use the graphical interface of Python, which is called **IDLE**. You can access it in the folder where **Python** was installed in your computer. It comes by default with the installation. It is also called the **Python Shell** . 

## Spyder & Jupyter Notebook
More user friendly alternatives to IDLE are **Spyder** and **Jupyter Notebook**. To use either of the two, first you need to download [Anaconda](https://www.continuum.io/downloads). Once done with the installation of **Anacodna**, open the **Anaconda Navigator** and then both the **Spyder** (Scientific Python Development Environment) app and **Jupyter Notebook** should be there to launch. 

As for Anaconda, to see everything that comes with its installation, ask for the list in the **Terminal**:

~~~python
# Input 
conda list

# Output
# packages in environment at /Users/username/anaconda:
_license                  1.1                      py36_1  
alabaster                 0.7.10                   py36_0  
anaconda                  4.4.0               np112py36_0  
anaconda-client           1.6.3                    py36_0  
anaconda-navigator        1.6.2                    py36_0  
~~~

You will get an overview of all the *packages/features/libraries* downloaded with it, along with the corresponding version. 

### Spyder

The interface of Spyder is similar to the one of R. You have an **editor** where you type your code and you can execute it all at once, or line by line if you prefer. The code you type, once executed, will halt if encounters an error. The **console** displays the execution of your code. You can write a code directly in the **console**, but it will not be saved unless you write it in the editor and save it. If you have a third window in Spyder, just close it as the only windows you need for now are the **Editor** and the **IPython console**. 

You can also open the **IPython console** through **Terminal** . The output is the same as the information you have in a new window of **Ipython Console** in **Spyder**. 

~~~python
# Input
ipython

# Output
Python 3.6.1 |Anaconda 4.4.0 (x86_64)| (default, May 11 2017, 13:04:09) 
Type "copyright", "credits" or "license" for more information.

IPython 5.3.0 -- An enhanced Interactive Python.
?         -> Introduction and overview of IPython's features.
%quickref -> Quick reference.
help      -> Python's own help system.
object?   -> Details about 'object', use 'object??' for extra details.
~~~

### Jupyter Notebook
Jupyter Notebook is another editor for **Python**. It is often preferred over **Spyder** since everything is previewed in one window, and additionally you can type markdown notes between your code to look like a notebook. 

Open it through **Anaconda navigator**, by launching the application. A new tab will pop out in your browser and your **Terminal** will open automatically to establish a connection to a server on a local host (localhost:8888/tree). Open a new notebook via the **New** button, selecting the desired version of **Python**. 
The beuaty of it is that you can download your notebook in different reusable file types (Notebook .ipynb, Python .py, HTML .html, Markdown .md, reST .rst, LaTeX .tex, PDF via LaTeX .pdf).



## Packages
To start writing code, first you need to be able to load libraries. Remember the libaries downloaded with **Anaconda**? You can use them in the Python editor, you just need to import them, or import only certain items from the library, when you don't need all the features available. 

~~~python
# Input
import nameofthelibary
import item from nameofthelibary
~~~

Alternatively, you can install a library through **Terminal**. When no error is privewed neither in the terminal nor in the console, then the library has been successfully installed. 

~~~python
# Input
pip install numpy
# Output
Collecting numpy
  Using cached numpy-1.13.1-cp36-cp36m-macosx_10_6_intel.macosx_10_9_intel.macosx_10_9_x86_64.macosx_10_10_intel.macosx_10_10_x86_64.whl
Installing collected packages: numpy
Successfully installed numpy-1.13.1
~~~







