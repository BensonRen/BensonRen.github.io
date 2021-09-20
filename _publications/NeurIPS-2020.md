---
title: "Benchmarking deep inverse models over time, and the neural-adjoint method"
collection: publications
permalink: /publication/NeurIPS-2020
excerpt: 'This paper is about deep learning and inverse problems (scientific discovery but not imagery). We benchmarked state-of-the-art deep inverse models and proposed a new algorithm called neural-adjoint that accurately and efficiently solves the inverse problems'
date: 2020.12.09
venue: '**NeurIPS 2020**: Advances in Neural Information Processing Systems 33'
paperurl: 'https://proceedings.neurips.cc/paper/2020/hash/007ff380ee5ac49ffc34442f5c2a2b86-Abstract.html'
citation: '**Ren, S**., Padilla, W., & Malof, J. (2020). Benchmarking Deep Inverse Models over time, and the Neural-Adjoint method. In H. Larochelle, M. Ranzato, R. Hadsell, M. F. Balcan, & H. Lin (Eds.), Advances in Neural Information Processing Systems (Vol. 33, pp. 38–48). Curran Associates, Inc.'
---

Abstract: We consider the task of solving generic inverse problems, where one wishes to determine the hidden parameters of a natural system that will give rise to a particular set of measurements. Recently many new approaches based upon deep learning have arisen, generating promising results. We conceptualize these models as different schemes for efficiently, but randomly, exploring the space of possible inverse solutions. As a result, the accuracy of each approach should be evaluated as a function of time rather than a single estimated solution, as is often done now. Using this metric, we compare several state-of-the-art inverse modeling approaches on four benchmark tasks: two existing tasks, a new 2-dimensional sinusoid task, and a challenging modern task of meta-material design. Finally, inspired by our conception of the inverse problem, we explore a simple solution that uses a deep neural network as a surrogate (i.e., approximation) for the forward model, and then uses backpropagation with respect to the model input to search for good inverse solutions. Variations of this approach - which we term the neural adjoint (NA) - have been explored recently on specific problems, and here we evaluate it comprehensively on our benchmark. We find that the addition of a simple novel loss term - which we term the boundary loss - dramatically improves the NA’s performance, and it consequentially achieves the best (or nearly best) performance in all of our benchmark scenarios.

[Download paper here](http://academicpages.github.io/files/paper3.pdf)

Recommended citation: **Ren, S.**, Padilla, W., & Malof, J. (2020). Benchmarking Deep Inverse Models over time, and the Neural-Adjoint method. In H. Larochelle, M. Ranzato, R. Hadsell, M. F. Balcan, & H. Lin (Eds.), Advances in Neural Information Processing Systems (Vol. 33, pp. 38–48). Curran Associates, Inc.
