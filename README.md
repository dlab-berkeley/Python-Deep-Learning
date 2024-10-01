# D-Lab Deep Learning in Python Workshop

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)
[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)
[![Open Slides](https://img.shields.io/badge/open-slides%20-purple)](https://docs.google.com/presentation/d/1NQBDrjkM5ZdabDQFxd5_EqjXA33gt9N0-uI9viVTs6A/edit?usp=sharing)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab Deep Learning in Python workshop. 

### Prerequisites
Prior experience with [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals), [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization), [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling) amd [Python Machine Learning](https://github.com/dlab-berkeley/python-machine-learning) is assumed.

Check D-Lab's [Learning Pathways](https://dlab-berkeley.github.io/dlab-workshops/python_path.html) to figure out which of our workshops to take!

## Workshop Goals

In this workshop, we will convey the basics of deep learning in Python using keras on image datasets. You will gain a conceptual grasp of deep learning, work with example code that they can modify, and learn about resources for further study.

## Learning Objectives

After this workshop, you will be able to:

- [LearningObjective1].
- [LearningObjective2].
- [LearningObjective3].

This workshop does not cover the following:

- [NotCovered1]. These are covered in [D-LabWorkshopName](URL).
- [NotCovered2]. These are covered in [D-LabWorkshopName](URL).


## Installation Instructions

Anaconda is a useful package management software that allows you to run Python and Jupyter notebooks very easily. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.8 distribution)](https://www.anaconda.com/products/individual). Click "Download" and then click 64-bit "Graphical Installer" for your current operating system.

2. Download the [Python-Data-Wrangling workshop materials](https://github.com/dlab-berkeley/Python-Data-Wrangling-Pilot):

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/Python-Data-Wrangling.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time. 

2. Click the "Launch" button under "Jupyter Notebooks" and navigate through your file system to the `Python-Data-Visualization` folder you downloaded above.

3. Open the `lessons` folder, and click `01_pandas.ipynb` to begin.

4. Press Shift + Enter (or Ctrl + Enter) to run a cell.

Note that all of the above steps can be run from the terminal, if you're familiar with how to interact with Anaconda in that fashion. However, using Anaconda Navigator is the easiest way to get started if this is your first time working with Anaconda.

## Is Python not working on your laptop? 

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking this button: 

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Data-Wrangling-Pilot&urlpath=tree%2FPython-Data-Wrangling-Pilot%2F&branch=main)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `Python-Data-Wrangling` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Data-Wrangling-Pilot/HEAD)

Once you have opened a jupyter notebook within the Binder environment, run the following code within a cell in the notebook:  
```
! pip install pandas matplotlib
```
Note that in Binder you cannot save your work.


# Additional Resources


* Massive open online courses
    * [fast.ai - Practical Deep Learning for Coders](https://course.fast.ai/)
    * [Kaggle Deep Learning](https://www.kaggle.com/learn/deep-learning)
    * [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
    * [See this](https://developers.google.com/machine-learning/crash-course/fitter/graph) sweet interactive learning rate tool
    * [Google seedbank examples](https://tools.google.com/seedbank/seeds)
    * [DeepLearning.ai](https://www.deeplearning.ai/)

* Workshops
    * [Nvidia's Modeling Time Series Data with Recurrent Neural Networks in Keras](https://courses.nvidia.com/courses/course-v1:DLI+L-HX-05+V1/about)

* Stanford
    * CS 20 - [Tensorflow for Deep Learning Research](http://web.stanford.edu/class/cs20si/syllabus.html)
    * CS 230 - [Deep Learning](http://cs230.stanford.edu/)
    * CS 231n - [Neural Networks for Visual Recognition](http://cs231n.github.io/)
    * CS 224n - [Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)

* Berkeley
    * Machine Learning at Berkeley [ML@B](https://ml.berkeley.edu/)
    * CS [189/289A](https://people.eecs.berkeley.edu/~jrs/189/)

* UToronto CSC 321 - [Intro to Deep Learning](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/)

* Books
    * F. Chollet and J.J. Allaire - [Deep Learning with Python](https://tanthiamhuat.files.wordpress.com/2018/03/deeplearningwithpython.pdf)
    * Charniak E - [Introduction to Deep Learning](https://mitpress.mit.edu/books/introduction-deep-learning)
 

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

## Introductory Workshops

* [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals)
* [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)
* [Python Geospatial Fundamentals](https://github.com/dlab-berkeley/Geospatial-Data-and-Mapping-in-Python)

## Advanced Workshops

* [Python Web Scraping and APIs](https://github.com/dlab-berkeley/Python-Web-Scraping)
* [Python Machine Learning](https://github.com/dlab-berkeley/Python-Machine-Learning)
* [Python Text Analysis](https://github.com/dlab-berkeley/Python-Text-Analysis)

# Contributors

* Anna Björklund
* Sean Perez
* Pratik Sachdeva

