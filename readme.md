# AoIR IR16 pre-conference workshop - Web Scraping

## QUT DMRC - 2015

Patrik Wikström & Brenda Moon

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/qut-dmrc/AoIR-IR16-web-scraping-workshop)

### Notebooks

* [Introduction](index.ipynb)
* Step 1. [Extract album title from a single item on a single page](metacritic-AOIR-step1.ipynb)
* Step 2. [Extract all album titles on a single page](metacritic-AOIR-step2.ipynb)
* Step 3. [Extract all review data from a single page](metacritic-AOIR-step3.ipynb)
* Step 4. [Structure the data extraction as a function](metacritic-AOIR-step4.ipynb)
* Step 5. [Store the data in a dataframe and save to disk](metacritic-AOIR-step5.ipynb)
* Step 6. [Restructure the code for clarity](metacritic-AOIR-step6.ipynb)
* Step 7. [Plotting, tiny stat analysis and improved I/O](metacritic-AOIR-step7.ipynb)
* Final. [Support for multiple pages](metacritic-AOIR-final.ipynb)

### Installation

This workshop uses Python 3 and the python modules listed below.

One of the easiest ways to install Python and packages that are relevant for web scraping is to use Anaconda developed by Continuum Analytics. Do note however, that Python is available in two versions, "2.7" and "3.4". We will be using Python 3.4, so make sure you download the correct one.

Anaconda can be downloaded from https://www.continuum.io/downloads

### Python modules used in this workshop

We use three Python modules in this workshop. The full documentation for each is available on their websites:

* [Requests](http://docs.python-requests.org/en/latest/) - get webpages from urls
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - select text out of webpages
* [Pandas](http://pandas.pydata.org/) - python data analysis library

These pages are in [Jupyter Notebook](https://jupyter.org/)
