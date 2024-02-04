# ITIS-6410-8410-Personalization-and-Recommender-Systems

Certainly! Below is a README template that you can use for your GitHub repository:

---

# LensKit Recommender System

## Overview

LensKit is a Python library for building, analyzing, and evaluating recommender systems. This repository provides an introduction to LensKit, guides on building a recommender system, and the implementation of two algorithms - ItemItem (k-nearest neighbors) and Biased Matrix Factorization (ALS).

## Installation

To install the LensKit library and dependencies, use the following commands:

```bash
pip install lenskit
pip install surprise
```

Note: The surprise library is used for loading datasets.

## Building a Recommender System

The recommender system is built using the ml-100k dataset, a benchmark dataset for collaborative filtering recommendation systems. The process includes loading the dataset, creating and evaluating two recommendation algorithms (ItemItem and Biased Matrix Factorization).

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/lenskit-recommender.git
cd lenskit-recommender
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:

```bash
jupyter notebook
```

Open the notebook `Recommender_System.ipynb` to explore and run the code.

## Evaluation

The performance of the algorithms is evaluated using the nDCG (Normalized Discounted Cumulative Gain) metric. The results are visualized through a bar plot, allowing easy comparison between algorithms.

## Conclusion

After analyzing the two algorithms, it was found that the ALS (Alternative Least Square) algorithm performed better in terms of nDCG values. This demonstrates the effectiveness of LensKit in building and evaluating recommender systems.
