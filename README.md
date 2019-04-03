# PACE
A step-by-step Keras implementation of PACE (Preference And Context Embedding) described in our KDD 2017 paper. To run the code, you need to have Python 3 and iPython Notebook installed.

Please cite the following work.

Carl Yang, Lanxiao Bai, Chao Zhang,  Quan Yuan and Jiawei Han. 2017. Bridging Collaborative Filtering and Semi-Supervised Learning: A Neural Approach for POI Recommendation. In Proceedings of KDD17, Halifax, NS, Canada, August 13-17, 2017, 10 pages.

## Usage:
* Visit `https://snap.stanford.edu/data/loc-gowalla.html` or `https://www.yelp.com/dataset/challenge` to download the Gowalla or Yelp datasets. Please refer to `dataset.py` the paper for data preprocessing.
* Start iPython Notebook Server `ipython3 notebook` and sequentially run cells in `train.ipynb`

If you are using remote machine, you can:
* Start iPython Notebook Server on remote machine: `ipython notebook --no-browser --port=8889`
* Redirect ssh connection to localhost `ssh -N -f -L localhost:8880:localhost:8889 <user>@<host>`
* Open browser and go to `<user>@<host>:8880`
