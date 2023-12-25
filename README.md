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

```bash
git clone https://github.com/your-repo/SharpCF.git
cd SharpCF


This will clone the SharpCF repository into your local machine and change your current directory to the newly cloned SharpCF directory. Now, you are all set to begin using the implementation.

Proceed to the "Usage" section for guidance on how to execute SharpCF and compare it with baseline models.

---

This section of the README provides clear instructions for cloning the repository and prepares the user to move on to the next steps in setting up and using SharpCF.

## Usage

To run our implementation of SharpCF or compare it with baseline models, copy the .ipynb file and run it in Kaggle notebooks since google colab provides low amount of ram usage.

## Acknowledgement
This project is an implementation of the methodology described in the paper "Adversarial Collaborative Filtering for Free" (arXiv:2308.13541). We acknowledge the original authors for their groundbreaking work.


## License

This project is licensed under the MIT License - see the LICENSE file for details.
---

This README provides a clear introduction to the purpose of the repository, acknowledging the original research and presenting your implementation with a focus on replicating and testing the described methodology.

