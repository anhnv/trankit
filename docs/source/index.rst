.. trankit documentation master file, created by
   sphinx-quickstart on Jan 06 10:21:23 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Trankit's Documentation
================================================

Trankit is a *light-weight Transformer-based Python* Toolkit for multilingual Natural Language Processing (NLP). It provides a trainable pipeline for fundamental NLP tasks over 100 languages, and 90 pretrained pipelines for 56 languages. Built on a state-of-the-art pretrained language model, Trankit significantly outperforms prior multilingual NLP pipelines over sentence segmentation, part-of-speech tagging, morphological feature tagging, and dependency parsing while maintaining competitive performance for tokenization, multi-word token expansion, and lemmatization over 90 Universal Dependencies v2.5 treebanks. Our pipeline also obtains competitive or better named entity recognition (NER) performance compared to existing popular toolkits on 11 public NER datasets over 8 languages.

Trankit's Github Repo is available at: https://github.com/nlp-uoregon/trankit

Trankit's Demo Website is hosted at: http://nlp.uoregon.edu/trankit

Citation
========
If you use Trankit in your research or software. Please cite `our following paper <https://arxiv.org/pdf/2101.03289.pdf>`_:

.. code-block:: bibtex

   @misc{nguyen2021trankit,
      title={Trankit: A Light-Weight Transformer-based Toolkit for Multilingual Natural Language Processing},
      author={Minh Nguyen and Viet Lai and Amir Pouran Ben Veyseh and Thien Huu Nguyen},
      year={2021},
      eprint={2101.03289},
      archivePrefix={arXiv},
      primaryClass={cs.CL}


.. toctree::
   :maxdepth: 2
   :caption: Introduction

   installation
   overview
   howitworks
   performance

.. toctree::
   :maxdepth: 1
   :caption: Usage

   pkgnames
   ssplit
   tokenize
   posdep
   lemmatize
   ner
   training
