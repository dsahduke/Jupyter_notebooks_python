# Introduction to Jupyter Notebooks and Python

For this course, we will be using Jupyter Notebooks. Jupyter notebooks are a great way to keep code and documentation in the same place and have other users or viewers be able to step through the same logic and run the code themselves if they want to reproduce your results. This repository contains example jupyter notebooks that go over basic elements of the python programming language as well as demonstrate the power and ease of Jupyter notebooks.

## Installation Instructions

You can install Jupyter (as part of Anaconda) by following the instructions below:
Note that we will be using Python 3.6+ for this course. Please make sure you have installed the correct version.
[Jupyter Installation Instructions](http://jupyter.org/install)

Alternatively, you can use software containerizations software that has Jupyter pre-installed. This method will be demonstrated later on in the course.

For those of you that are already familiar with tools such as Docker, you can pull the following container down and it will contain everything you need to run the notebooks for this course unless otherwise specified.

`docker pull jupyter/scipy-notebook` for a python docker container with jupyter that contains most of the scietific python stack.

`docker pull jupyter/datascience-notebook` is another alternative that includes kernels for R and Julia, in case you want to explore those languages as well.

