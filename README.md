# Convolutional Neural Network for Sentence Classification, in TensorFlow
This is a full (slightly modified and extended) TensorFlow implementation of the model presented by Kim in [Convolutional Neural Networks for Sentence Classification](http://www.aclweb.org/anthology/D14-1181). With this code can reproduce all results we present in [Word Embeddings and Their Use In Sentence Classification Tasks](https://arxiv.org/abs/1610.08229)

## Features:
- Supports Random, Static, and non-Static modes
- Runs on (almost) all datasets from the original article + 2 srom [here](https://arxiv.org/abs/1510.03820) + 2 new ones. 
- Optimizer changed to ADAM, improving training time and some of the results
- Support for L2 loss added

## Credits
If you're using this code please make sure you cite both following papers:
- Kim's paper:
```
@article{Kim2014ConvNetSent,
  Author = {Kim, Yoon},
  Journal = {arXiv preprint arXiv:1408.5882},
  Title = {Convolutional Neural Networks for Sentence Classification},
  Year = {2014}
}
```
- Our paper:
```
@article{Man2016WordEmbbed,
  Author = {Mandelbaum, Amit and Shalev, Adi},
  Journal = {arXiv preprint arXiv:1610.08229},
  Title = {Word Embeddings and Their Use In Sentence Classification Tasks},
  Year = {2016}
}
```
Also, small parts of the code were taken from:
- [Yoon Kim's git repository](https://github.com/yoonkim/CNN_sentence)
- [Denny Britz's git repository](https://github.com/dennybritz/cnn-text-classification-tf)
We'd like to thank them for that.

## Requirements
- Python (2.7)
- NumPy
- TensorFlow (>=0.8)
- Pandas

## Usage
