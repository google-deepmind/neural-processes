# Conditional Neural Processes

We provide a notebook implementation of Conditional Neural Processes (CNPs) that
can be run in the browser. The notebook includes an overview of the different
building blocks of the model and the code to run it. Any further details can be
found in our [paper](https://arxiv.org/pdf/1807.01613.pdf).

## Quick run

The easiest way to run the code is to download the `.ipynb` file and upload it
to [Colab](https://colab.research.google.com/). Colaboratory is a free Jupyter
notebook environment provided by Google that requires no setup and runs entirely
in the cloud. The hosted runtime already includes the following dependencies:

*   Numpy
*   Tensorflow
*   Matplotlib

which are all we need to run CNPs.

Alternative you can open the `.ipynb` file using
[Jupyter notebook](http://jupyter.org/install.html). If you do this you will
also have to set up a local kernel that includes Tensorflow.

## If you enjoy conditional neural processes...

... you might like our follow up work
[Neural Processes](https://arxiv.org/pdf/1807.01622.pdf), where we introduce a
latent variable version of CNPs that allows us to generate different samples
given the same context.

## Citing CNPs

If you like our work and end up using CNPs for your research give us a shout-out:

Garnelo M, Rosenbaum D, Maddison CJ, Ramalho T, Saxton D, Shanahan M, Teh YW,
Rezende DJ, Eslami SM. Conditional Neural Processes. In International Conference
on Machine Learning 2018.

## Contact

Any feedback is much appreciated! Drop us a line at garnelo@google.com

## Disclaimer

This is not an official Google product.
