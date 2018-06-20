# Intent detection with recurrent networks in CNTK
This repository contains a python notebook that demonstrates how to use
Microsoft Cognitive Toolkit to build an intent detection model.

## Prerequisites
Please make sure that you have the following tools on your machine:

 - Anaconda for Python 3.x (https://anaconda.org/)
 - CNTK 2.x (`pip install cntk-gpu` or `pip install cntk`)
 - Tensorboard (`pip install tensorboard`)

## Getting started
Clone this repository to disk using `git clone`.

Once you have the tools installed you can open up the Anaconda command prompt
and execute `jupyter notebook` in the root folder of this repository.

You can run the code in the notebook by selecting individual cells and then
using the <kbd>Ctrl</kbd>+<kbd>Enter</kbd> keys to execute the cell.

## Be aware
Training a neural network like the one I demonstrate in the notebook 
takes a lot of power. And as a consequence is really slow on a CPU.

It may take quite a few minutes to have the network trained when you're not
using a GPU.

**If you can, please train this network only on a GPU!**