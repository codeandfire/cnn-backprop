This is a short tutorial describing how backpropagation is performed in a convolutional neural network.

Backpropagation through the convolution and max pooling operations of a convolutional network seems like a mathematical nightmare, which is best left to the deep learning libraries to perform under-the-hood!
However, on a closer look, you realize that it is not as complicated as you first imagined, and the expressions turn out to have a neat and elegant form.

You can read this article as a PDF by compiling the files `cnn_backprop.tex` and `cnn_backprop.bib`.
For example, you could use a tool such as [Latexmk](https://mg.readthedocs.io/latexmk.html):
```
$ latexmk -pdf
```

If you use this article in your work, please cite it as follows:
```bibtex
@misc{cnnbackprop,
  author={Maheshwari, Saniya},
  title={Backpropagation in convolutional networks},
  howpublished={\url{https://github.com/codeandfire/cnn-backprop}},
  year={2021},
}
```
