# KT

*PyTorch implementations of various Knowledge Tracing models* 

## Pre-processed Dataset
* Download Link: https://bit.ly/2w7J3On
* Dataset format: log files are seperated by users. Once you download and unzip each tar.gz file, there's a folder `processed`, and there are 5 subdirectories named from `1` to `5` for cross validation. Each subdirectory has its own train/val/test separation, where test dataset is shared by all 5 separations. Separation ratio are given in the following table. 

| Dataset          | Train:Val:Test |
|------------------|----------------|
| ASSISTments2009  |       56:14:30       |
| ASSISTments2015  |       56:14:30       |
| ASSISTments2012  |                      |
| ASSISTmentsChall |       6:2:2          |
| STATICS          |       56:14:30       |
| Junyi Academy    |                      |
| KDDCup2010       |                      |
| EdNet-KT1        |                      |

* For ASSISTments2009, ASSISTments2015, and STATICS data we use the same data (with different format) that used in [this](https://github.com/jennyzhang0215/DKVMN) DKVMN implementation. 

## DKT (Deep Knowledge Tracing)
* Paper: https://web.stanford.edu/~cpiech/bio/papers/deepKnowledgeTracing.pdf
* Performances: 

| Dataset          | ACC | AUC | Hyper Parameters |
|------------------|-----|-----|------------------|
| ASSISTments2009  |     |     |                  |
| ASSISTments2015  |     |     |                  |
| ASSISTments2012  |     |     |                  |
| ASSISTmentsChall |     |     |                  |
| STATICS          |     |     |                  |
| Junyi Academy    |     |     |                  |
| KDDCup2010       |     |     |                  |
| EdNet-KT1        |     |     |                  |

## DKVMN (Dynamic Key-Value Memory Network) (TODO)
* Paper: http://papers.www2017.com.au.s3-website-ap-southeast-2.amazonaws.com/proceedings/p765.pdf
* Performances: 

## SAKT (Self-Attentive Knowledge Tracing) (TODO)
* Paper: https://files.eric.ed.gov/fulltext/ED599186.pdf
* Performances: 

## NPA (Neural Padagogical Agency) (TODO)
* Paper: https://arxiv.org/abs/1906.10910
* Performances: 

## SAINT (Separated self-AttentIve kNowledge Tracing) (TODO)
* Paper: https://arxiv.org/pdf/2002.07033.pdf
* Performances
