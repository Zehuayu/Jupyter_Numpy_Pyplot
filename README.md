# Jupyter_Numpy_Pyplot

## Introduction of Jupyter ,numpy and matplotlib


[Jupyter](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) (The Jupyter Notebook App is a server-client application that allows editing and running notebook documents via a web browser. The Jupyter Notebook App can be executed on a local desktop requiring no internet access (as described in this document) or can be installed on a remote server and accessed through the internet.)
[numpy](http://www.numpy.org/) (Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.)

[matplotlib](https://en.wikipedia.org/wiki/Matplotlib)(is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+. There is also a procedural "pylab" interface based on a state machine (like OpenGL), designed to closely resemble that of MATLAB, though its use is discouraged. SciPy makes use of matplotlib.)


## setting environment

Pip3 install  Jupyter

Pip3 install numpy 

Pip3 install matplotlib 

After installing the three things, all function could be running


## some problem for question

1. How to import CSV document? 

copy all data from website, then pasting all into the Number, which is a app in MCOS. Put the import in file and found out CSV.

2. How to open data from document

iris_data = np.genfromtxt('irisdata.csv', delimiter=',', skip_header=1, usecols=(), dtype=None)  [this reource from the note of class]

3. draw line and change color

pl.plot(petal_length, m * petal_length + c, 'b-', label='Best fit (np.polyfit): $%0.1f x + %0.1f$' % (m,c))
[this is draw line, i ask my classmate and discuss it]
pl.plot(sepal_length[0:50:1], sepal_width[100:150:1], 'b.', label = 'virginics')#draw photo
['b.' means is blue, filling the color on point]

4. other question

[import pandas](http://pandas.pydata.org/)

[Calculate](https://www.youtube.com/watch?v=1P5gHtyKU2Q&feature=youtu.be) and i asked my friend
