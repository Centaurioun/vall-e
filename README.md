Language : 🇺🇸 | [🇨🇳](./README.zh-CN.md)

An unofficial PyTorch implementation of VALL-E([Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2301.02111)).

## Installation

To get up and running quickly just follow the steps below:

```
# phonemizer
apt-get install espeak-ng
## OSX: brew install espeak
pip install phonemizer

# lhotse
# https://github.com/lhotse-speech/lhotse/pull/956
pip install git+https://github.com/lhotse-speech/lhotse

# k2 icefall
git clone https://github.com/k2-fsa/icefall
cd icefall
pip install -r requirements.txt
export PYTHONPATH=`pwd`/../icefall:$PYTHONPATH

# valle
git clone https://github.com/lifeiteng/valle.git
cd valle
pip install .
```

## Getting started

The quickest way to get started is to take a look at the detailed working code
examples found in the [examples] subdirectory.

[examples]: examples/
[paper]: https://arxiv.org/abs/2301.02111



## NOTE

* model-mini config: a mini model for debuging
* model-raw config: same as the paper
* TBD

## Contributing

* TBD

## Citing

To cite this repository:

```bibtex
@misc{valle,
  author={Feiteng Li},
  title={VALL-E: A neural codec language model},
  year={2023},
  url={http://github.com/lifeiteng/valle}
}
```

```bibtex
@article{VALL-E,
  title     = {Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers},
  author    = {Chengyi Wang, Sanyuan Chen, Yu Wu,
               Ziqiang Zhang, Long Zhou, Shujie Liu,
               Zhuo Chen, Yanqing Liu, Huaming Wang,
               Jinyu Li, Lei He, Sheng Zhao, Furu Wei},
  year      = {2023},
  eprint    = {2301.02111},
  archivePrefix = {arXiv},
  volume    = {abs/2301.02111},
  url       = {http://arxiv.org/abs/2301.02111},
}
```
