# DeepDTS: Diverse Test Selection Method for Deep Neural Networks

Welcome to the official code repository for **DeepDTS: Diverse Test Selection Method for Deep Neural Networks**. This repository accompanies our paper published in the *2024 IEEE 24th International Conference on Software Quality, Reliability and Security (QRS)*.

## Overview

DeepDTS is a novel approach designed to enhance the reliability of deep neural networks by selecting diverse test cases. This method aims to provide a more comprehensive evaluation of neural network behavior, improving robustness against various input conditions.

### 📄 Paper

You can access the full paper [here](https://ieeexplore.ieee.org/document/10726966).

### 📍 Abstract

Deep Neural Networks (DNNs) are extensively ap-plied in data-driven modeling tasks. Testing these networks is critical due to their involvement in safety-critical applications. However, their black-box nature poses challenges in explaining their decisions and identifying incorrect behaviors. Detecting faults in a DNN requires selecting a diverse and error-revealing test set from a vast, unlabeled dataset. Diversity in the test set expands the coverage of the decision space of DNN, aiding in the identification of distinct faults. In this paper, we introduce Singular Entropy Density (SED) metric to evaluate the diversity of a test set on a DNN model. We demonstrate its effectiveness against other diversity measures. Additionally, we present DeepDTS, a diverse test selection method designed to identify misclassified inputs with higher diversity scores according to SED. To evaluate the effectiveness of DeepDTS relative to other coverage and uncertainty-based test selection methods, we conducted experiments with widely employed datasets and DNN models. Our results demonstrate that Deep-DTS outperforms other selection methods in terms of selecting a diverse test set.

## Getting Started

### Installation

```pip install -r requirements.txt```

### Usage

You can try different data and model combinations by changing data_name and model_name variable values.

## Citation
If you use this code or dataset, please cite our paper:
```
@INPROCEEDINGS{10726966,
  author={Dedekoy, Mert and Sen, Alper},
  booktitle={2024 IEEE 24th International Conference on Software Quality, Reliability, and Security Companion (QRS-C)}, 
  title={DeepDTS: Diverse Test Selection Method for Deep Neural Networks}, 
  year={2024},
  pages={250-259},
  doi={10.1109/QRS-C63300.2024.00041}}
```
