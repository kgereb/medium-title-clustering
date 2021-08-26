# medium-title-clustering


A collection of article titles from Medium are used to carry out doc2vec transformation of the titles, then cluster them in the vector space using t-SNE.

The dataset is from: https://www.kaggle.com/nulldata/medium-post-titles?select=medium_post_titles.csv

To run this notebook, dataset will have to be downloaded and saved in a folder called 'kaggle_datasets'.

The work can be found in the following notebook:

`sent2vec_tsne.ipynb`

## Requirements:

The notebook was created in a Python 3.8.0 virtual environment. To install the necessary libraries, run:

pip install requirements.txt

# The final results looks like:

![Clusters](https://github.com/kgereb/medium-title-clustering/blob/main/clusters.png)



