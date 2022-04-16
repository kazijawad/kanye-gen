# KANYE-GEN

KANYE-GEN is an exploration of a machine learning system that is trained to create new Kanye West rap verses based on his existing catalog of lyrics and songs. The ML system is composed of a lyric generation model that can be piped into a voice generation model.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software:

```
Python 3.8.x
```

### Installing

A step by step guide that tell you how to get a development environment running.

1. Clone the repository:

```bash
git clone https://github.com/kazijawad/kanye-gen.git
```

2. Install necessary packages, an [Anaconda](https://www.anaconda.com) environment is recommended:

```bash
# Python Packages
conda create -n p-kanye python=3.8
conda activate p-kanye
pip install tensorflow tensorflow-datasets notebook matplotlib ipywidgets
```

3. Run the application:

```bash
jupyter notebook
```

## Built With

- [TensorFlow](https://tensorflow.org)
- [Kanye West Rap Verses Dataset](https://www.kaggle.com/datasets/viccalexander/kanyewestverses)

## Authors

- [Kazi Jawad](https://kazijawad.com)
- [Richard Zhou](https://www.richardczhou.com)
- [Michael Kim](https://maikool.com)
