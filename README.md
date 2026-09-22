# FedFinGuard: Trust-Aware Federated Learning for Adversarially Robust Financial Fraud Detection

This repository contains the official implementation of FedFinGuard, a trust-aware federated learning framework designed to integrate prototype contrastive attention, focal loss, and trust-aware aggregation for adversarially robust financial fraud detection.

**Note on Code Availability:** A portion of the basic source code for FedFinGuard has been uploaded to this repository to provide a foundational overview of the framework. The complete source code, including all training scripts, advanced defense modules, and detailed preprocessing pipelines, will be made publicly available upon the official acceptance of our manuscript. For the duration of the peer-review process, the full codebase has been provided to the journal editors and reviewers as part of the submission package to ensure transparency and reproducibility.

## Dataset Information
FedFinGuard was evaluated on two publicly available financial datasets. We do not host the raw data in this repository due to size and licensing constraints, but the official sources are listed below. Preprocessing and stratified splitting scripts will be included in the final release.

1. **European Credit Card Fraud**: Official Kaggle Repository (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
2. **Taiwan Credit Card Default**: Official UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

## Reproduction and Setup
Upon public release, this repository will include:

* A `requirements.txt` file for dependency management.
* Step-by-step scripts for data preprocessing, non-IID client partitioning, and federated model training.
* Configuration files matching the hyperparameters reported in the manuscript.

## Citation
If you find this work or the provided code useful for your research, please cite our paper:

```bibtex
@article{fedfinguard2026,
  title={Trust-Aware Federated Learning with Prototype Contrastive Attention for Adversarially Robust Financial Fraud Detection},
  author={Author Names},
  journal={Journal Name},
  year={2026},
  note={Submitted for publication},
  publisher={Publisher}
}
```
