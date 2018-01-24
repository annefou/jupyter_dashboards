---
layout: page
title: Setup
root: .
---

# Installing Python

[Python](http://python.org/) is a popular language for research computing, and great for general-purpose programming as well. Installing all of its research packages individually can be a bit difficult, so we recommend Anaconda, an all-in-one installer. Regardless of how you choose to install it, please make sure you install **Python version 3.6**. We will teach Python using the [Jupyter Notebook](http://jupyter.org/), a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not).

## Windows

[Video tutorial](https://www.youtube.com/watch?v=xxQ0mzZ8UvA)

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the Python 3 installer for Windows.
3. Install Python 3 using all of the defaults for installation except make sure to check that the Anaconda distribution is the default Python.

## Mac OSX

[Video tutorial](https://www.youtube.com/watch?v=TcSAln46u9U)

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the Python 3 installer for OS X.
3. Install Python 3 using all of the defaults for installation.
    * If you want to install Anaconda in your home directory (“for me only”), and the respective dialog when it initially appears prohibits this choice, change the location to system-wide (“for every user”), and then change it back. (This is a bug in the installer that can manifest on some versions of MacOSX.)

## Linux

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the Python 3 installer for Linux.
3. Install Python 3 using all of the defaults for installation. (Installation requires using the shell. If you aren’t comfortable doing the installation yourself stop here and request help at the workshop.)
4. Open a terminal window.
5. Type:
~~~
 bash Anaconda3-
~~~
{: .bash}

and then press tab. The name of the file you just downloaded should appear.

Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).

# Installing [Anaconda navigator](https://anaconda.org/anaconda/anaconda-navigator)

One of the useful things about Anaconda Python is its tools for Python **package management** and **project environments**. The core tool for this is the command-line utility **conda**. However, there is also a GUI tool called "Anaconda Navigator".

As part of this workshop, we will learn how to use Anaconda Navigator to manage our Python environment and for this setup section, you only need to check Anaconda Navigator is available on your laptop. Do not hesitate to contact us if you have any problems. We will be able to help you with the installation during the workshop so do not worry!

## Test Installation

Launch "Anaconda Navigator" from your menu. This should work on any operating system (Windows, Mac-OSX and Linux) and a window should pop up:

<img src="images/anaconda-navigator.png" style="width: 700px;"/>


On Mac-OSX or Linux, you may want to launch it from the command line:

~~~
$ anaconda-navigator
~~~
{: .bash}
# Credits

This installation tutorial is taken from [Software Carpentry](http://swcarpentry.github.io/workshop-template/#setup)
