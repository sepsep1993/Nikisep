# Split Computing and Early Exiting for Deep Learning

## Authors
- Niki Akhavanniaki
- Sepehr Abdi Goudarzi

## Project Title
Split Computing and Early Exiting for Deep Learning


## Introduction
Recently, split computing (SC)-based approaches have emerged, where the DNN (Deep Neural Network) is divided into a head and a tail model. These models are then processed on the edge server and the mobile device, respectively. This approach aims to reduce both bandwidth and energy consumption. Models are trained using a different strategy termed early exiting (EE). Early exiting involves incorporating several "exits" earlier in the architecture, each of which offers progressively better target precision. Consequently, the trade-off between accuracy and latency can be adjusted based on the circumstances or the requirements of an application.

## Our Study
In this project, we provide a re-implementation of the benchmarks presented in the original paper on early exits. We offer two models:

1. Model without Early Exits
![1](https://github.com/sepsep1993/Nikisep/issues/1#issue-1877627737.jpg)
2. Model with 2 Early Exits
![2](https://github.com/sepsep1993/Nikisep/issues/2#issue-1877629243)

These models are evaluated on the CIFAR-10 dataset, where they are trained to predict the labels of images.

