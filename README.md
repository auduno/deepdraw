DeepDraw
======

![Image generated](http://auduno.github.io/deepdraw/images/deepdraw_example_0013.png)

**DeepDraw** is a ipython notebook example of generating class visualizations, such as the one above, from deep neural networks using [Caffe](http://caffe.berkeleyvision.org/). The examples and settings in this notebook was based on the pretrained GoogLeNet model available with Caffe, but it's easy to modify to use other networks, such as AlexNet. For some more detailed information about how these class visualizations are generated, check out [this blogpost]().

To run this code, you'll need an installation of Caffe with built pycaffe libraries, as well as the python libraries numpy, scipy and PIL. For instructions on how to install Caffe and pycaffe, refer to the installation guide [here](http://caffe.berkeleyvision.org/installation.html). Before running the ipython notebooks, you'll also need to download the [bvlc_googlenet model](https://github.com/BVLC/caffe/tree/master/models/bvlc_googlenet), and insert the path of the pycaffe installation into ```pycaffe_path``` and the model path to the googlenet model into ```model_path```.

If you create some cool work or visualizations based on this library, let me know [via twitter](https://twitter.com/matsiyatzy)!

This code was based on the [deepdream code](https://github.com/google/deepdream) shared by Google, as well as [some modifications](https://github.com/kylemcdonald/deepdream/blob/master/dream.ipynb) kindly shared by Kyle McDonald. This repository is freely shared under Apache License 2.0.
