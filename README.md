# fairCorrect
Fairness correction through parametrised resampling

## How it Works

* XAI Paper: kddSubmission.pdf
* Recent Slides: Turing.pdf
* Poster: Poster_CVGZ_PhD_October.pdf

## Data
All the necessary to run these scripts are available in the Datasets folder

## Scripts
data_cleanup script performs necessary cleaning and encoding for the three benchmark datasets we tested.
fairCorrect is the main script. It requires the cleaned-up data (also available in the Datasets folder).

## Required Packages

These scripts have been tested over Python 3.6.5 and Jupyter Notebooks 4.4.0

Necessary packages are:

* pandas 0.23.0
* NumPy 1.14.3
* scikit-learn 0.19.1
* imbalanced-learn 0.3.3
* Matplotlib 2.2.2
* Seaborn 0.9.0

Save file instructions are commented out in both scripts, and should be modified accordingly to the desired location before being uncommented.

Likewise, if loading datasets locally, load_csv() statements should be modified accordingly. If unmodified, datasets will load directly from this repository.
