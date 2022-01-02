# FANG-COVID

This repository contains the German fake news dataset "FANG-COVID" introduced in [FANG-COVID: A New Large-Scale Benchmark Dataset for Fake News
Detection in German](https://aclanthology.org/2021.fever-1.9.pdf). 

For questions, please write an e-mail to justus.mattern@rwth-aachen.de

### Training Splits

Our [paper](https://aclanthology.org/2021.fever-1.9.pdf) presents results for two training splits, a random training split and a media-seperated split. The former follows the standard 5-fold validation framework, the latter seperates training and test split by publishers to test the generalization capabilities. 

To replicate the media-seperated split, use the following sources for testing and remove them from the training set:

- 



Please use this citation provided by the [ACL Anthology](https://aclanthology.org/2021.fever-1.9/) when working with the dataset:

```
@inproceedings{mattern-etal-2021-fang,
    title = "{FANG}-{COVID}: A New Large-Scale Benchmark Dataset for Fake News Detection in {G}erman",
    author = "Mattern, Justus  and
      Qiao, Yu  and
      Kerz, Elma  and
      Wiechmann, Daniel  and
      Strohmaier, Markus",
    booktitle = "Proceedings of the Fourth Workshop on Fact Extraction and VERification (FEVER)",
    month = nov,
    year = "2021",
    address = "Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.fever-1.9",
    pages = "78--91"}
    
