# INSTALLATION AND TEST GUIDE MAD-X WORKSHOP JUAS 2023
** Material based on CAS 2022 from D. Gamba and G. Sterbini ** 

During the course we will use **Python3** in a **[Jupyter](https://jupyter.org)**  and, mostly, the [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), [pandas](https://pandas.pydata.org/) and [cpymad](http://hibtc.github.io/cpymad/index.html) packages. We will explain in the following sections how to install all necessary software on **your laptop**.

A basic knowledge of Python is assumed. If you are not familiar with Python, you can find a few resources to fill the gap in the following sections. Do not worry about the theory for the moment (it will be discussed in details during the school) but focus on the Python syntax and data types (tuples, lists,...).

After [a short introduction](#a-very-short-introduction-to-python), where we provided some useful links to get familiar with Python, we will focus on the [software setup](#software-setup). 
Finally, in [appendix](#appendix-python-packages) you will find links and cheatsheets for the most common Python packages that will be used during the course.

> **Important:** we kindly ask you to go throw this document **before coming** to JUAS, such as to **prepare yourself** (and **your laptop**) for the course. 

---
# A very short introduction to Python
You can find several nice courses, videos and resources on the internet. Here you have a couple of suggestions you can find on YouTube:

[Python for Beginners - Learn Python in 1 Hour](http://www.youtube.com/watch?v=kqtD5dpn9C8)

[Learn Python - Full Course for Beginners](http://img.youtube.com/vi/rfscVS0vtbw)

You can also follow the tutorials in:
[Python tutorial](https://www.kaggle.com/code/colinmorris/hello-python)


### Test Python on a web page

If you are not familiar with Python and you have not it installed on your laptop, you can start playing with simple python snippets on the web (e.g., [CoLab](https://colab.research.google.com/drive/1Pk-UPE2-OCA2UCFIunqDwxXmQi9Yvp-C?usp=sharing), a google account is needed).

---
# Software Setup

In this section we will explain how to install Python and Jupyter on your laptop.
JupyterLab is a user-friendly environment to work with Python. 
You can find an overview on JupyterLab [here](https://jupyterlab.readthedocs.io/en/stable/).

> If you already have your favorite Python distribution installed on your laptop, including JupyterLab, you might want to skip the [installation](#installation) and jump to [launch Jupyter Lab](#launch-jupyter-lab) and [test that everything works](#test-that-everything-works).

## Installation

We suggest to install the **Anaconda** distribution from [here](https://www.anaconda.com/distribution/)

> We suggest to install one of the latest distribution (**for example version Python 3.9**).

The installation process clearly depends on your operating system. We suggest you to follow the official documentation for [Windows](https://docs.anaconda.com/anaconda/install/windows/), [Linux](https://docs.anaconda.com/anaconda/install/linux/), or [Mac](https://docs.anaconda.com/anaconda/install/mac-os/) as appropriate.
After having installed **Anaconda**, and [verified your installation](https://docs.anaconda.com/anaconda/install/verify-install/) - as suggested in the [installation documentation](https://docs.anaconda.com/anaconda/install/) - we invite you to start [launching Jupyter Lab](#launch-jupyter-lab) and then [test that everything works](#test-that-everything-works):

## Launch Jupyter

Once the installation of **Anaconda** is finalised or within your existing Python distribution, you should be able to start Jupyter from a terminal:

1. Open a (Anaconda) terminal on your operating system:
    - **Windows:**
        From the Start menu, search for and open “Anaconda Prompt”:
    - **macOS:**
        Open Launchpad, then click the terminal icon.
    - **Linux:**
        Open a terminal window.

2. Launch Jupyter from your terminal:

    ```bash
    jupyter notebook
    ```
    or, in case you want a jupyter lab server
    
    ```bash
    jupyter lab
    ```
    

3. Follow the instructions given in the terminal. You should end-up on your default browser with a page similar to the following:

    On the left hand side of the widows you should see all files under the folder in your operating system where you executed the `jupyter lab` command.
    This will be your **working directory**. 

4. Start playing with Python!  Please, make sure to go throw all the [PythonBasicTutorial/PythonBasic.ipynb](PythonBasicTutorial/PythonBasic.ipynb) (material based on the tutorial prepared by *Simon Albright*)to familiarize with the typical Python concepts that will be used during the course, but also to verify your installation. If you happen to experience any problem, please check to have installed the whole anaconda distribution. Alternatively, you can try to go back to your terminal, and install each single (or missing) package independently, e.g.:

```python
pip install numpy matplotlib jupyter jupyterlab cpymad
```

5. **Just before the start of the course**, we will ask you to download the **latest version** of the [MAD-XworkshopJUAS2023] repository in your **working directory**.

6. **Optional:** instead of running Jupyter lab within a browser, you can try to install and the [jupyterlab-desktop](https://github.com/jupyterlab/jupyterlab-desktop) application.

---
## Appendix: Python Packages

You can leverage python's capability by exploring a galaxy of packages. Below you can find the most useful for our course (focus mostly on `numpy` and `matplotlib`) and some very popular ones. 

### The *numpy* package
To get familiar with the *numpy* package have a look at the following [summary poster](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf).
You can google many other resources, but the one presented of the poster covers the set of instructions you should familiar with.

### The *matplotlib* package
To get familiar with the *matplotlib* package have a look at the following [summary poster](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Matplotlib_Cheat_Sheet.pdf).

### The *cpymad* package
To get familiar with the *cpymad* package have a look at the following [link](https://hibtc.github.io/cpymad/).

### The *pandas* package (optional)
To get familiar with the *pandas* package have a look at the following [summary poster](
https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PandasPythonForDataScience.pdf).



