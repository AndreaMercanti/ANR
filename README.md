# Code for CIKM 2018 paper

This is a fork of the original implementation code "__ANR: Aspect-based Neural Recommender__" in CIKM 2018 for my personal needs, whose paper is 
available [here](https://dl.acm.org/citation.cfm?id=3271810).

For a quick overview of the paper, you can refer to these [slides](https://drive.google.com/open?id=1lLrOhHO8K9V-euVg0Ur2xtsKYhRPNyfb).

If you too use in some ways or find useful its code, please consider to cite the work:

```
@inproceedings{Chin:2018:AAN:3269206.3271810,
 author = {Chin, Jin Yao and Zhao, Kaiqi and Joty, Shafiq and Cong, Gao},
 title = {ANR: Aspect-based Neural Recommender},
 booktitle = {Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
 series = {CIKM '18},
 year = {2018},
 isbn = {978-1-4503-6014-2},
 location = {Torino, Italy},
 pages = {147--156},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3269206.3271810},
 doi = {10.1145/3269206.3271810},
 acmid = {3271810},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {aspect-based recommendation, co-attention, neural attention, recommender systems},
}
```

## Environment Setup

- Python 3.6.3
- PyTorch 0.3.0

## Walkthrough
The author, in his experiments, used the [Amazon instant video dataset](http://jmcauley.ucsd.edu/data/amazon), while I used a personal dataset in mine. 
The dataset was built ad hoc by running my [URB-RS](https://github.com/AndreaMercanti/URB-RS) repo and then stored in the `datasets` folder.

1. I downloaded the Google's file for pretrained word embeddings [here](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit), unzipped and stored it in the upper folder
2. I preprocessed, pretrained and finally trained and tested the data

For more clarification on point 2, please, do refer to [\_\_\_README\_\_\_.txt](____README____.txt).

