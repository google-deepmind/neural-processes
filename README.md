# The Neural Process Family

This repository contains notebook implementations of the following Neural Process variants:

*   Conditional Neural Processes (CNPs)
*   Neural Processes (NPs)
*   Attentive Neural Processes (ANPs)

The code for CNPs can be found in `conditional_neural_process.ipynb` while the
code for both NPs and ANPs is located in `attentive_neural_process.ipynb`.

The
notebooks include an overview of the different building blocks of the models
as well as the code to run each model in the browser. Any further details
can be found in the [CNP paper](https://arxiv.org/pdf/1807.01613.pdf), the
[NP paper](https://arxiv.org/pdf/1807.01622.pdf) and the
[ANP paper](https://arxiv.org/pdf/1901.05761.pdf).

## Quick run

The easiest way to run the code is to run it in the browser on [Colab](https://colab.sandbox.google.com). 
Here below are the links to each of the notebooks in Colab:

* [Conditional Neural Processes](https://colab.sandbox.google.com/github/deepmind/neural-processes/blob/master/conditional_neural_process.ipynb)
* [(Attentive) Neural Processes](https://colab.sandbox.google.com/github/deepmind/neural-processes/blob/master/attentive_neural_process.ipynb)

Colaboratory is a free Jupyter notebook environment provided by Google that requires no setup and runs entirely
in the cloud. The hosted runtime already includes the following dependencies, tested on the following versions in brackets:

*   Numpy (1.14.6)
*   Tensorflow (1.13.1)
*   Matplotlib (2.2.4)

which are all we need to run the code in this repository.

Alternatively, you can open the `.ipynb` files using
[Jupyter notebook](http://jupyter.org/install.html). If you do this you will
also have to set up a local kernel that includes Tensorflow.

## Citing CNPs

If you like our work and end up using neural processes for your reseach give us a shout-out:

1. **Conditional Neural Processes**: Garnelo M, Rosenbaum D, Maddison CJ, Ramalho T, Saxton D, Shanahan M, Teh YW,
Rezende DJ, Eslami SM. *Conditional Neural Processes*. In International Conference
on Machine Learning 2018.

1. **Neural Processes**: Garnelo, M., Schwarz, J., Rosenbaum, D., Viola, F., Rezende, D.J., Eslami, S.M. and Teh, Y.W. *Neural processes*. ICML Workshop on Theoretical Foundations and Applications of Deep Generative Models 2018.

1. **Attentive Neural Processes**: Kim, H., Mnih, A., Schwarz, J., Garnelo, M., Eslami, A., Rosenbaum, D., Vinyals, O. and Teh, Y.W. *Attentive Neural Processes*. In International Conference on Learning Representations 2019.

## Contact

Any feedback is much appreciated! Drop us a line at garnelo@google.com (Conditional Neural Process) or hyunjikk@google.com ((Attentive) Neural Process).

## Disclaimer

This is not an official Google product.
