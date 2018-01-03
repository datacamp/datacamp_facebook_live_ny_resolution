# IMPORTANT

**If you're planning to code along, make sure to clone, download, or re-pull this repository on the morning of Thursday January 4th, 2018. All edits will be completed by 1159pm ET Wednesday January 3rd.**



## Identifying New Year's Resolutions with Google Trends

In this Facebook live code along session, you're going to check out Google trends data of keywords 'diet', 'gym' and 'finance' to see how they vary over time. Could there be more searches for these terms in January when we're all trying to turn over a new leaf? Let's find out! In this session, you'll code along with Hugo to import google trends data into your Jupyter notebook and use `pandas` and a bunch of other packages from the Python data science stack to analyze and interpret these time series. You'll learn a bunch about time series analysis while getting your hands dirty with the world's new year's resolutions. You're not going to do much mathematics today but you'll source your data, visualize it and learn about trends and seasonality in time series data. The emphasis will be squarely on a visual exploration of the dataset in question.

Join Hugo live on Thursday January 4th, 2018 at 10:30am ET on Facebook!

## Prerequisites

Not a lot. It would help if you knew

* programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about Jupyter Notebooks;
* your way around the terminal/shell.


**However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.**

Also, if you'd like to watch and **not** code along, you'll also have a great time and these notebooks will be downloadable afterwards also.

If you are going to code along and use the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below), I ask that you install it before the session.


## Getting set up computationally

### 1. Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/datacamp/datacamp_facebook_live_ny_resolution
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `datacamp_facebook_live_ny_resolution` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called `fb_live_ny_res`. To activate the environment on OSX/Linux, execute

```
source activate fb_live_ny_res
```
On Windows, execute

```
activate fb_live_ny_res
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the notebook `New_Years_Resolutions_Workshop.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.
