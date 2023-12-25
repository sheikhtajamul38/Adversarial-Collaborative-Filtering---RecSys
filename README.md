# SharpCF: Sharpness-aware Collaborative Filtering

Welcome to the SharpCF repository, where we present an innovative approach to Collaborative Filtering (CF). Our method enhances model generalizability and robustness, addressing the challenges in existing CF methods caused by noisy data. SharpCF connects adversarial training with Sharpness-aware Minimization, significantly reducing computational overhead.

## Introduction

Collaborative Filtering has long been a staple in recommendation systems. However, the presence of noisy data in these systems often deteriorates the quality of recommendations. Traditional methods, leveraging adversarial learning to regularize user/item representations, lack theoretical guarantees and are computationally intensive. SharpCF introduces an efficient and theoretically grounded solution to these challenges.

## Key Features

- **Theoretical Foundation**: Establishes a connection between adversarial collaborative filtering methods and Sharpness-aware Minimization.
- **Trajectory Loss**: A novel trajectory loss that aligns current and past model states, facilitating adversarial training without additional computational burdens.
- **Performance**: Outperforms traditional methods like BPR and APR, with considerable improvements and comparable time complexity.

## Installation

To install SharpCF, follow these simple steps:

- git clone [https://github.com/your-repo/SharpCF.git](https://github.com/sheikhtajamul38/Adversarial-Collaborative-Filtering---RecSys.git)
- cd SharpCF


This will clone the SharpCF repository into your local machine and change your current directory to the newly cloned SharpCF directory. Now, you are all set to begin using the implementation.

Proceed to the "Usage" section for guidance on how to execute SharpCF and compare it with baseline models.


## Usage

To run our implementation of SharpCF or compare it with baseline models, copy the .ipynb file and run it in Kaggle notebooks since google colab provides low amount of ram usage.

## Acknowledgement
This project is an implementation of the methodology described in the paper "Adversarial Collaborative Filtering for Free" (arXiv:2308.13541). We acknowledge the original authors for their groundbreaking work.


