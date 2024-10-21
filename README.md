# Federated-Learning
## Tutorial

NeurIPS 2020, Federated Learning Tutorial
https://sites.google.com/view/fl-tutorial/home

Aurélien Bellet, Introduction to Federated Learning
http://researchers.lille.inria.fr/abellet/talks/federated_learning_introduction_long.pdf

## Survey
[Advances and Open Problems in Federated Learning](https://www.nowpublishers.com/article/Details/MAL-083)

[A Field Guide to Federated Optimization](https://repository.kaust.edu.sa/bitstream/handle/10754/670335/Preprintfile1.pdf?sequence=1)

[Decentralized federated learning: Fundamentals, state of the art, frameworks, trends, and challenges](https://ieeexplore.ieee.org/iel7/9739/5451756/10251949.pdf)

## Methods
### Centralized
#### FedAvg
FedAvg: [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf) 

AC-SA (baseline in optimization): [An optimal method for stochastic composite optimization](https://link.springer.com/article/10.1007/s10107-010-0434-y)

Convergence of FedAvg with convexity:

local-SGD: [Local SGD converges fast and communicates little](https://arxiv.org/pdf/1805.09767)

Parallel restarted SGD for non-convex optimization with faster convergence and less communication.

Convergence of FedAvg with non-convexity:

Parallel restarted SGD for non-convex optimization with faster convergence and less communication

Cooperative SGD: A unified framework for the design and analysis of communication-efficient SGD algorithms (can be extended to decentralized)

On the convergence of FedAvg on non-IID data

Tackling the objective inconsistency problem in heterogeneous federated optimization
#### Others
FedProx: Federated optimization in heterogeneous networks

SCAFFOLD: Scaffold: Stochastic controlled averaging for federated learning
### Decentralized
D-PSGD: Can Decentralized Algorithms Outperform Centralized Algorithms? A Case Study for Decentralized Parallel Stochastic Gradient Descent

LD-SGD: Communication efficient decentralized training with multiple local updates

MATCHA: MATCHA: Speeding Up Decentralized SGD via Matching Decomposition Sampling
### Compression
Distributed mean estimation with limited communication

QSGD: Communication-efficient SGD via gradient quantization and encoding

Qsparse-local-sgd: Distributed sgd with quantization, sparsification, and local computations

Distributed fixed point methods with compressed iterates

Fedboost: A communication-efficient algorithm for federated learning
### DP-FL
The error-feedback framework: Better rates for SGD with delayed gradients and compressed communication
## Researchers:
H. Brendan McMahan, Google Research 
https://research.google/people/author35837/?&type=google

Aurélien Bellet, Inria
http://researchers.lille.inria.fr/abellet/talks.html

## Applications:
Google https://machinelearning.apple.com/video/pfl-framework

NVIDIA https://venturebeat.com/ai/healthcare-organizations-use-nvidias-clara-federated-learning-to-improve-mammogram-analysis-ai/

Apple https://machinelearning.apple.com/video/pfl-framework

