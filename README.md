# Introduction to Python

This tutorial is aimed at English majors and aspiring digital humanists at California State, Northridge but should be suitable for anyone wishing to get started with Python.

## What is Python?

Python is a programming language that is easy to learn, even for those without any background in computer programming. There are a few simple concepts to learn, and, after that, you can simply Google "How do I do X in Python?" to find lots of code samples which you can copy to achieve whatever goal you have in mind. By this method, you can learn how to do more and more with Python gradually on the fly.

## Why would I want to use Python?

Some knowledge of coding is a huge asset in the workplace, and Python is a good language to start with. Once you learn the concepts, learning other programming languages is relatively easy. Python, specifically, is in high demand in many growing fields such as data science, but it is used in a huge variety of fields. Within academia, it is very common in the digital humanities, so it allows you to do research in the types of scholarship students like English majors are interested in. Subjects like literary studies focus on texts, and Python is especially good at manipulating text. For instance, Python is often used to study literary style.

## How do I get started?

The first step to working with Python is to download and install a Python distribution on your computer. A distribution is simply a copy of the Python language, generally with some tweaking to run in individual settings. The easiest distribution to work with is Anaconda, which is free and relatively simple to install. Instructions for installing Anaconda are available [here](how-to-install-anaconda.md). However, for the initial stages of learning, it is convenient to use a distribution based in the cloud so that you don't have to install anything. Once you are ready to do more complicated things, you can install Python on your own computer.

Once you have a Python distribution up and running, there are several ways to use Python. The default method is to run Python from the command line (called the "command prompt" in Windows and the "terminal" on the Mac). This is essentially a small window where you can type in commands like `python start.py`. This command will launch Python and run a Python program you have written and saved to the file `start.py` (Python programs conventionally end in `.py`). However, many people choose to run their code inside their web browser using something called a Jupyter notebook. This is the method you will use in this tutorial.

## How Jupyter notebooks work

A "notebook" is like a web page with form fields (called "cells") into which you type your Python code. You can then run the code and get feedback. There are a number different notebook implementations, but Jupyter notebooks (formerly called iPython notebooks) are by far the most popular. Recently, the Jupyter team have introduced Jupyter Lab. This is effectively a better interface for running Jupyter notebooks. To use either you simply type `jupyter notebook` or `jupyter lab` on the command line, and a window will open in your web browser containing the jupyter notebook interface.

When you open a specific notebook, you enter (or paste) your code in the cells and then click the `Run` button or type `Shift+Enter` to run your code. Jupyter notebooks are great to learn from because your can open them with the cells pre-populated with sample code. Jupyter notebooks are also great because they allow you to enter explanatory material such as a description of what the code is doing.

## Versions of Python

One final point to be aware of before you get started is that there are two major version of Python: Python 2 and Python 3. Python 2 will no longer be supported starting in 2020, so Python 3 is the future. However, there are many, many Python 2 tools and code samples on the internet after years of use, and you may encounter them if you do some Googling. The differences are fairly minor until you start doing advanced stuff. For instance, the command `print "hello"` does what you probably think it does in Python 2. In Python 3, it is `print("hello")`. Just be aware of that you may see these differences if you copy code off the internet. This tutorial will exclusively use Python 3.

## Ready to get started?

The rest of this tutorial will run inside a Jupyter notebook hosted on a cloud-based service called Binder. It's important to understand how this service works. When you start the tutorial, Binder builds a virtual computer and installs a Python distribution before launching your Jupyter notebook. This takes a bit of time to set up, so please be patient during this process. To start the tutorial, click the "Launch" button.

[![button](images/Launch-Button-300x199.jpg)](https://mybinder.org/v2/gh/scottkleinman/python-tutorials/master?filepath=basic_python_tutorial.ipynb)
