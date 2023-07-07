# DHOxSS - Text to Tech
Materials for the Text to Tech workshop at the Digital Humanities Oxford Summer School

## Binder & Colab

The workshop will mostly rely on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Living-with-machines/dhoxss-text2tech/dev) for the hands-on activities.

Some notebooks run you can on Google Colab for computational reasons:

### LM and Word2Vec Presentation

Link to [slides](https://docs.google.com/presentation/d/1i56HKtjcdQFTxacxsjgya_giDx8Mv1xZn-IDNc_mK8I/edit?usp=sharing)

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

## Background reading (optional):

- Walsh, Melanie. Introduction to Cultural Analytics & Python, https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome
- Karsdorp, Folgert. Python Programming for Humanists. http://www.karsdorp.io/python-course/.
- Montfort, Nick. Exploratory Programming for the Arts and Humanities. Cambridge, Massachusetts: The MIT Press, 2016. https://mitpress.mit.edu/books/exploratory-programming-arts-and-humanities.
- Sinclair, Stéfan, and Geoffrey Rockwell. The Art of Literary Text Analysis. Melissa Mony., 2016. https://github.com/sgsinclair/alta/blob/77b256f7c3ff3ceb6643d53da401096c8cdcc468/ipynb/ArtOfLiteraryTextAnalysis.ipynb.
- Graham, Shawn, Ian Milligan, Scott Weingart. The Historian's Macroscope. Under contract with Imperial College Press. Open Draft Version, Autumn 2013, http://themacroscope.org
- Downey, Allen, Peter Wentworth, Jeffrey Elkner, and Chris Meyers. “How To Think Like A Computer Scientist: Learning with Python 3.” (2016).
- Karsdorp, Folgert, Mike Kestemont and Allen Riddell, Humanities Data Analysis: Case Studies with Python, https://www.humanitiesdataanalysis.org

## Advanced reading list (optional):

- Jurafsky, Daniel, and J. H. Martin. "Vector semantics and embeddings." Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition (2019): 94-122. https://web.stanford.edu/~jurafsky/slp3/6.pdfLinks to an external site.
- Smith, Noah A. "Contextual word representations: A contextual introduction." arXiv preprint arXiv:1902.06006 (2019). https://arxiv.org/pdf/1902.06006.pdfLinks to an external site.
- Boleda, Gemma. "Distributional semantics and linguistic theory." Annual Review of Linguistics 6 (2020): 213-234. https://arxiv.org/pdf/1905.01896.pdfLinks to an external site.
- Rogers, Anna. "Changing the World by Changing the Data." arXiv preprint arXiv:2105.13947 (2021). https://arxiv.org/pdf/2105.13947.pdfLinks to an external site.
- Wevers, Melvin, and Marijn Koolen. "Digital begriffsgeschichte: Tracing semantic change using word embeddings." Historical Methods: A Journal of Quantitative and Interdisciplinary History 53, no. 4 (2020): 226-243. https://www.tandfonline.com/doi/pdf/10.1080/01615440.2020.1760157Links to an external site.
- Bender, Emily M., and Alexander Koller. "Climbing towards NLU: On meaning, form, and understanding in the age of data." In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pp. 5185-5198. 2020. https://www.aclweb.org/anthology/2020.acl-main.463.pdfLinks to an external site.
- Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. "Text as data: A new framework for machine learning and the social sciences." Princeton University Press, 2022. https://press.princeton.edu/books/paperback/9780691207551/text-as-data

## Other Resources

This course is based upon many previous resources. Apart from the ones above:
- Nilo Pedrazzini's introduction notebook to Word2Vec.
- Materials from previous editions of this course, written by Barbara McGillivray and Gard Jenset 
- The Turing's [Research Software Engineering](https://alan-turing-institute.github.io/rse-course/html/index.html) and [Research Data Science](https://alan-turing-institute.github.io/rds-course/index.html) Courses
- [The Turing Way](https://the-turing-way.netlify.app/welcome)
- [The Turing Digital Humanities & Research Software Engineering Summer School](https://github.com/alan-turing-institute/DH-RSE-Summer-School)
- Fede's [Computational Text Analysis](https://federiconannidotcom.wordpress.com/computational-text-analysis/) Course
