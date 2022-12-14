# AI-PP7 computer vision and image classification

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP7-computer-vision-and-image-classification/blob/master/AI-PP7-computer-vision-and-image-classification.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/PP7-computer-vision-and-image-classification/blob/master/LICENSE)

Practical Project 7 (PP7) for Artificial Intelligence studies to solidify basics of **computer vision and image classification** by practicing.

## Usage

### Automatic launch

1. To run in browser click on [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP7-computer-vision-and-image-classification/blob/master/AI-PP7-computer-vision-and-image-classification.ipynb) badge.
2. (Or) To launch locally on Windows just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/PP7-computer-vision-and-image-classification/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/PP7-computer-vision-and-image-classification.git
```

2. Navigate into project:

```bash
cd PP7-computer-vision-and-image-classification/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook AI-PP7-computer-vision-and-image-classification.ipynb
```

## Requirements

- [x] Take Covid data from [this article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7372265/) … or any other place you can find a credible source of Covid lung imaging datasets.
- [x] Train a model that can classify people as having Covid and not having Covid based on the images.
- [x] No requirements on the performance of the model, anything >50% (random guessing) would be great!
- [x] No requirements for the usage of a framework: you can use Keras, Pytorch or Fast.ai - or even all.
- [x] No requirements to use transfer learning (however it is recommended).
- [x] Write a short paragraph on what you learned while implementing a solution for this specific task (5 sentences / ideas minimum).
- [x] Provide a link to the Google Colab notebook (double-check the share options of the notebook) or GitHub link with jupyter notebook code when finished for review and evaluation.
