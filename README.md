# [PYTORCH] Attention Networks for Document Classification

## Introduction

Pytorch implementation of the paper **Hierarchical Attention Networks for Document Classification** [paper](https://www.cs.cmu.edu/%7Ediyiy/docs/naacl16.pdf). 




## Requirements:

* **python 3.6**
* **pytorch 0.4**
* **tensorboard**
* **tensorboardX** (This library could be skipped if you do not use SummaryWriter)
* **numpy**

## Custom Dockerfile to build the Pytorch environment training on Valohai


## Datasets:



| Dataset                | Classes | Train samples | Test samples |
|------------------------|:---------:|:---------------:|:--------------:|
| AG’s News              |    4    |    120 000    |     7 600    |
| Sogou News             |    5    |    450 000    |    60 000    |
| DBPedia                |    14   |    560 000    |    70 000    |
| Yelp Review Polarity   |    2    |    560 000    |    38 000    |
| Yelp Review Full       |    5    |    650 000    |    50 000    |
| Yahoo! Answers         |    10   |   1 400 000   |    60 000    |
| Amazon Review Full     |    5    |   3 000 000   |    650 000   |
| Amazon Review Polarity |    2    |   3 600 000   |    400 000   |


## Training on Valohai platform with Machine learning version control

* Valohai.yaml 
* Experiments on Valohai platform with Version control

![valohai](/results/valohai.png)
## Experiments:

Each experiment is run over 10 epochs.

| GLOVE word2vec|        50      |      100     |      200     |      300     |
|:---------------:|:------------------:|:------------------:|:------------------:|:------------------:|
|    ag_news    |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
|   sogu_news   |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
|    db_pedia   |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
| yelp_polarity |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
|  yelp_review  |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
|  yahoo_answer |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
| amazon_review |   updated soon   |   updated soon   |   updated soon   |   updated soon   |
|amazon_polarity|   updated soon   |   updated soon   |   updated soon   |   updated soon   |

The training/test loss/accuracy curves for each dataset's experiments (with the order from left to right, top to bottom is 50d, 100d, 200d and 300d word2vec) are shown below:

- **ag_news**

<img src="results/agnews_50.png" width="420"> <img src="results/agnews_100.png" width="420"> 
<img src="results/agnews_200.png" width="420"> <img src="results/agnews_300.png" width="420">

- **db_pedia**

<img src="results/dbpedia_50.png" width="420"> <img src="results/dbpedia_100.png" width="420"> 
<img src="results/dbpedia_200.png" width="420"> <img src="results/dbpedia_300.png" width="420">

- **yelp_polarity**

<img src="results/yelpreviewpolarity_50.png" width="420"> <img src="results/yelpreviewpolarity_100.png" width="420"> 
<img src="results/yelpreviewpolarity_200.png" width="420"> <img src="results/empty.png" width="420">

- **yelp_review**

<img src="results/yelpreviewfull_50.png" width="420"> <img src="results/empty.png" width="420"> 
<img src="results/empty.png" width="420"> <img src="results/yelpreviewfull_300.png" width="420">

- **Yahoo! Answers**

<img src="results/yahoo_50.png" width="420"> <img src="results/yahoo_100.png" width="420"> 
<img src="results/yahoo_200.png" width="420"> <img src="results/yahoo_300.png" width="420">

- **amazon_review**

<img src="results/amazonreviewfull_50.png" width="420"> <img src="results/empty.png" width="420"> 
<img src="results/amazonreviewfull_200.png" width="420"> <img src="results/empty.png" width="420">

- **amazon_polarity**

<img src="results/amazonreviewpolarity_50.png" width="420"> <img src="results/amazonreviewpolarity_100.png" width="420"> 
<img src="results/empty.png" width="420"> <img src="results/amazonreviewpolarity_50.png" width="420">

