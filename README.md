# DHOxSS - Text to Tech
Materials for the Text to Tech workshop at the Digital Humanities Oxford Summer School

## Binder & Colab

The workshop will mostly rely on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Living-with-machines/dhoxss-text2tech/dev) for the hands-on activities.

Some notebooks run you can on Google Colab for computational reasons:

### Word2Vec Notebooks

**Note:** To run notebooks on Colab you need to install some required libraries. For example, to run the Word2Vec notebooks, add a cell with these commands:

```python
!pip install gensim spacy
```


- Exploring Word2Vec [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5a-word2vec-exploring.ipynb)
- Training a Word2Vec model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5b-word2vec-training.ipynb) 
- Visualizing Word2Vec vector spaces [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5c-word2vec-visualising.ipynb) 

### Language Models Notebooks

- Pretrained Language Models: GPT-2 and BERT [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5d-PLMs.ipynb) 
- Large Language Models: BLOOM and ChatGPT [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Living-with-machines/dhoxss-text2tech/blob/dev/Sessions/5e-LLMs.ipynb) 

## Local installation

* Install [Anaconda](https://www.anaconda.com/)
* Download the content of this repository and unzip
* Open Anaconda Navigator
* From Anaconda, create environment py39
* Install JupyterLab in environment
* Launch JupyterLab
* Open terminal in Jupyter Lab
* Write the following in the terminal, step-by-step:
    * `conda activate py39`
    * Update pip: `pip install --upgrade pip`
    * Change directory using the `cd` command in the terminal until you are in the course folder. There you should run: `pip install -r requirements.txt`
    * Add the environment to Jupyter (following instructions from here) or by running `ipython kernel install --user --name=py39`
Then you can already start using the notebooks: select as kernel `py39` (restart JupyterLab if the correct kernel does not show)

You find more detailed instructions [here](https://melaniewalsh.github.io/Intro-Cultural-Analytics/02-Python/01-Install-Python.html).

## Data


Datasets used:

- The  `Living Machines atypical animacy dataset`, freely available [here](https://bl.iro.bl.uk/concern/datasets/323177af-6081-4e93-8aaf-7932ca4a390a?locale=en).

- MuSe: The Musical Sentiment Dataset [Muse](https://www.kaggle.com/datasets/cakiki/muse-the-musical-sentiment-dataset)

- A historical dataset on popular baby names  in the United States from 1880 onwards. Available [here](https://www.ssa.gov/OACT/babynames/limits.html).

- A sample of British Library [19th Century Books](https://doi.org/10.21250/db14) collected from [here](https://huggingface.co/datasets/blbooks).

- A sample of British Newspapers articles, digitized by [Heritage Made Digital](https://doi.org/10.23636/1163). 

## Advanced Reading List

- Montfort, Nick. [Exploratory Programming for the Arts and Humanities](https://mitpress.mit.edu/books/exploratory-programming-arts-and-humanities). Cambridge, Massachusetts: The MIT Press, 2016.
- Karsdorp, Folgert. [Python Programming for Humanists](http://www.karsdorp.io/python-course/).
- Sinclair, Stéfan, and Geoffrey Rockwell. [The Art of Literary Text Analysis](https://github.com/sgsinclair/alta/blob/77b256f7c3ff3ceb6643d53da401096c8cdcc468/ipynb/ArtOfLiteraryTextAnalysis.ipynb). Melissa Mony., 2016.
- Turkel, William J., and Alan MacEachern. [The Programming Historian](https://programminghistorian.org/en/).
- Graham, Shawn, Ian Milligan, Scott Weingart. [The Historian’s Macroscope](http://themacroscope.org). Open Draft Version, Autumn 2013,
- Downey, Allen, Peter Wentworth, Jeffrey Elkner, and Chris Meyers. [How To Think Like A Computer Scientist: Learning with Python 3](https://buildmedia.readthedocs.org/media/pdf/howtothink/latest/howtothink.pdf). (2016).
- Walsh, Melanie. [Introduction to Cultural Analytics & Python](https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html). 
- Karsdorp, Folgert, Mike Kestemont, and Allen Riddell. [Humanities data analysis: case studies with Python.](https://www.humanitiesdataanalysis.org/) Princeton University Press, 2021.

## References

This course is based upon many previous resources, in particular:

- On the materials from previous editions of this course, written by Barbara McGillivray and Gard Jenset 
- The Turing's [Research Software Engineering](https://alan-turing-institute.github.io/rse-course/html/index.html) and [Research Data Science](https://alan-turing-institute.github.io/rds-course/index.html) Courses
- [The Turing Way](https://the-turing-way.netlify.app/welcome)
- [The Turing Digital Humanities & Research Software Engineering Summer School](https://github.com/alan-turing-institute/DH-RSE-Summer-School)
- Fede's [Computational Text Analysis](https://federiconannidotcom.wordpress.com/computational-text-analysis/) Course
