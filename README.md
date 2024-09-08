# preseea_analysis

This repository contains the code for the analysis of the PRESEEA dataset.

## Installation

You can install the repository by running the following command:

```bash
git clone https://github.com/ramajoballester/preseea_analysis.git
cd preseea_analysis
pip install -e .[dev]
```

## Notebooks

- first: tree-based search for clusters with highest / lowest values of subject presence. Additionallly, it includes brute force comparison up to 3 variables for the same purpose but ranking by higher number of examples.
- sociologico: clustering of sociological variables and representation based on the top 3 PCA components (3D plot).