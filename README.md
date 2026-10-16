# Gradient compression on CIFAR-10

This is a learning project. I was reading papers on communication-efficient distributed training and wanted to study how the algorithms behave in practice, so I trained ResNet-50 on CIFAR-10 with each of them and compared accuracy against the amount of data sent per worker.

The notebook is `efsgd.ipynb`.

## Papers

- **EFSGD:** Karimireddy, Rebjock, Stich, Jaggi. *Error Feedback Fixes SignSGD and other Gradient Compression Schemes.* ICML 2019. [arXiv:1901.09847](https://arxiv.org/abs/1901.09847)
- **EF21:** Richtárik, Sokolov, Fatkhullin. *EF21: A New, Simpler, Theoretically Better, and Practically Faster Error Feedback.* NeurIPS 2021. [arXiv:2106.05203](https://arxiv.org/abs/2106.05203)
- **1-Bit SGD:** Seide, Fu, Droppo, Li, Yu. *1-Bit Stochastic Gradient Descent and its Application to Data-Parallel Distributed Training of Speech DNNs.* Interspeech 2014.
- **DIANA:** Mishchenko, Gorbunov, Takáč, Richtárik. *Distributed Learning with Compressed Gradient Differences.* 2019. [arXiv:1901.09269](https://arxiv.org/abs/1901.09269)
- **Top-K with memory:** Stich, Cordonnier, Jaggi. *Sparsified SGD with Memory.* NeurIPS 2018. [arXiv:1809.07599](https://arxiv.org/abs/1809.07599)
