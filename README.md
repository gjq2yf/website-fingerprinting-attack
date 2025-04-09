# Website Fingerprinting Attack

This project explores how encrypted HTTPS traffic can still leak information about which websites a user visits. We implement a basic fingerprinting attack using packet metadata (size, direction, timing) and train classifiers like logistic regression to identify visited sites.

## Goals
- Collect and label encrypted traffic
- Extract meaningful metadata features
- Train ML models to classify websites
- Evaluate model performance and robustness

## Setup
Install dependencies:

```bash
pip install -r requirements.txt
