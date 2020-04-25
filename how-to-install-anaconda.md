# How to Install Anaconda

Anaconda is an easy-to-install Python distribution with almost all the Python packages commonly used by digital humanists pre-installed.

Excellent instructions for installing Anaconda are available at problemsolvingwithpython.com. The links below go directly to the instructions for each operating system. However, before you follow them, please read the following note.

When installing Anaconda, you may be asked to install Visual Studio Code at the same time. Visual Studio Code is Microsoft's code editor, and it is free and awesome! However, you may not need a dedicated tool for editing code if you are working primarily in Jupyter notebooks. It's up to you whether you want to install Visual Studio Code. If you choose not to install it, you can always go to the [Visual Studio Code web site](https://code.visualstudio.com/) and download it at a later date. As you get better at writing Python, you may want to create your own scripts written with a code editor. There are lots of advantages to doing so, particularly the editor provides hints to help you find errors.

Now here are the links:

- [Installing Anaconda on Windows](https://problemsolvingwithpython.com/01-Orientation/01.03-Installing-Anaconda-on-Windows/)
- [Installing Anaconda on MacOS](https://problemsolvingwithpython.com/01-Orientation/01.04-Installing-Anaconda-on-MacOS/)
- [Installing Anaconda on Linux](https://problemsolvingwithpython.com/01-Orientation/01.05-Installing-Anaconda-on-Linux/)

It is apparently possible to install Anaconda on a Chromebook, but the process is not straightforward. If you have a Chromebook, you may have to Google a solution or just make use of a service like Binder to do your work in the cloud (that is the point of a Chromebook, right?)

If you successfully followed all the instructions above, you will now have a working installation of Python on your computer.

## Launching Jupyter Notebooks

You are now ready to work in Jupyter notebooks or Jupyter Lab. Open the Anaconda prompt and type either `jupyter notebook` for the classic interface or `jupyter lab` for the new one. After a few seconds, a new window should open in your web browser. You will see a system for navigating the files and folders on your browser. Go to the location where you wish to create a new notebook. In Jupyter notebooks, click the `New` button in the top right corner and select `Python 3`. A new Jupyter notebook wil open. In Jupyter lab, just click the "Python 3" button under "Notebook" in the launcher tab.

When you are finished with Jupyter notebooks, return to the Anaconda prompt and type `Control + C` (sometimes several times are required) to interrupt the process. Otherwise Jupyter notebooks will continue to run in the background. When you are done, you can close the Anaconda prompt window.
