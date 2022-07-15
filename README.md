# DHOxSS - Text to Tech
Materials for the Text to Tech workshop at the Digital Humanities Oxford Summer School

## Binder

The workshop will rely on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Living-with-machines/dhoxss-text2tech/dev) for the hands-on activities.

## Colab

Some notebooks run on Google Colab

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/4e-word2vec.ipynb) **Introduction to Word2Vec (Guest lecture by Nilo Pedrazzini)**
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5b-Transformers-for-NLP.ipynb) **Transformers for NLP**


## Data

The workshop will rely on the  `Living Machines atypical animacy dataset` which we have added to this GitHub repo and it is also freely available [here](https://bl.iro.bl.uk/concern/datasets/323177af-6081-4e93-8aaf-7932ca4a390a?locale=en).

## Local installation

At the end of the workshop, if you would like to install Python locally we suggest the following:

- Install [Anaconda](https://www.anaconda.com/)
- Clone the content of this repository (or download it for now, if you are not familiar with GitHub)
- Create a conda environment (following instructions from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html)) with this command: `conda create --name py39 python=3.9`
- Start your environment with: `conda activate py39`
- Change directory in the terminal until you are in the course folder. There you should run: `pip install -r requirements.txt`
- Add the environment to Jupyter (following instructions from [here](https://towardsdatascience.com/get-your-conda-environment-to-show-in-jupyter-notebooks-the-easy-way-17010b76e874))
- Start Jupyter (using the Anaconda Navigator or from the terminal running `jupyter lab`)
- In your notebook select as kernel `py39`

Maybe it will work!

## Advanced Reading List

- Montfort, Nick. [Exploratory Programming for the Arts and Humanities](https://mitpress.mit.edu/books/exploratory-programming-arts-and-humanities). Cambridge, Massachusetts: The MIT Press, 2016.
- Karsdorp, Folgert. [Python Programming for Humanists](http://www.karsdorp.io/python-course/).
- Sinclair, Stéfan, and Geoffrey Rockwell. [The Art of Literary Text Analysis](https://github.com/sgsinclair/alta/blob/77b256f7c3ff3ceb6643d53da401096c8cdcc468/ipynb/ArtOfLiteraryTextAnalysis.ipynb). Melissa Mony., 2016.
- Turkel, William J., and Alan MacEachern. [The Programming Historian](https://programminghistorian.org/en/).
- Graham, Shawn, Ian Milligan, Scott Weingart. [The Historian’s Macroscope](http://themacroscope.org). Open Draft Version, Autumn 2013,
- Downey, Allen, Peter Wentworth, Jeffrey Elkner, and Chris Meyers. “How To Think Like A Computer Scientist: Learning with Python 3.” (2016).
- Walsh, Melanie. [Introduction to Cultural Analytics & Python](https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html). 
- Karsdorp, Folgert, Mike Kestemont, and Allen Riddell. [Humanities data analysis: case studies with Python.](https://www.humanitiesdataanalysis.org/) Princeton University Press, 2021.

## References

This course is based upon many previous resources, in particular:

- On the materials from previous editions of this course, written by Barbara McGillivray and Gard Jenset 
- The Turing's [Research Software Engineering](https://alan-turing-institute.github.io/rse-course/html/index.html) and [Research Data Science](https://alan-turing-institute.github.io/rds-course/index.html) Courses
- [The Turing Way](https://the-turing-way.netlify.app/welcome)
- [The Turing Digital Humanities & Research Software Engineering Summer School](https://github.com/alan-turing-institute/DH-RSE-Summer-School)
- Fede's [Computational Text Analysis](https://federiconannidotcom.wordpress.com/computational-text-analysis/) Course
...
