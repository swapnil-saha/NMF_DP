# Privacy-preserving Non-negative Matrix Factorization with Outliers

This repository contains the code and resources for the project **"Privacy-preserving Non-negative Matrix Factorization with Outliers"**, as published in the paper:

> Saha, Swapnil and Imtiaz, Hafiz. "Privacy-preserving Non-negative Matrix Factorization with Outliers." *ACM Transactions on Knowledge Discovery from Data*, vol. 18, no. 3, pp. 1--26, 2024. ACM New York, NY.

## Overview
In this data-driven world, it is well-known that the performance of a data-driven optimization model for finding insightful population information depends on the quality of the data features. But there is tension regarding privacy, how "safe" a person of that population feels about sharing his private data with the world. Focusing on preserving individual participants' privacy and gaining their trust, we worked on developing a privacy-preserving Non-negative Matrix Factorization (NMF). More specifically, we developed the privacy-preserving non-negative matrix factorization using the Differential Privacy algorithm. As there's no such thing as a free lunch - the system model has to sacrifice its performance/utility (compared to a non-privacy-preserving setup) to give privacy to individual data participants. To make life easier for the system designers, we showed the analysis of the utility gap vs. privacy parameter so that one can choose one's privacy guarantee based on the tolerance of utility loss. 


## Features
- **Privacy-preserving NMF**: A method designed to protect sensitive data using Differential Privacy algorithm while performing Non-negative Matrix Factorization (NMF).
- **Outlier handling**: Efficiently handling outliers makes it suitable to be effective in real-world noisy environments.
- **Simulation Result**: Extensive simulations validated the algorithm's effectiveness in topic modeling and facial decomposition.

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.8 or later
- Required libraries (see `requirements.txt`)

### Installation
```bash
git clone https://github.com/swapnil-saha/NMF_DP.git
cd NMF_DP
pip install -r requirements.txt
