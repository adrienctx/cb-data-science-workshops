# cb-data-science-workshops
Material for datascience workshops at Cardinalblue

# Requirements
* install Anaconda from [their website](https://docs.continuum.io/anaconda/install/)
* create a new environment, following [their documentation](https://conda.io/docs/using/envs.html)
* install required packages with conda: numpy, pandas, matplotlib, seaborn, xgboost
* install ggplot package as follows (there is a currently conflict with pandas)
```
pip install git+git://github.com/yhat/ggpy.git@9d00182343eccca6486beabd256e8c89fb0c59e8 --no-cache
```
* download the data either from [Kaggle](https://www.kaggle.com/c/zillow-prize-1/data) or directly from (our Drive folder)[https://www.dropbox.com/sh/zc5qwkt41gt3805/AAB6d5RxHjQkJTCw_clyA_KIa?dl=0], and put it in ```./kaggle-zillow/input/```.
