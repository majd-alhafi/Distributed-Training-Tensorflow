# Distributed-Training-Tensorflow
TensorFlow framework provides distributed training via data parallelism.

Data parallelism means the data is split into several slices while the model architecture is the same among different devices.

And finally, there should be one master model that aggregates all different weights from each replica (the model within the device).

TensorFlow has diffrernt stategies :

- MirrorStrattegy : single machine with one or more GPUs.

- MultiWorkerMirrorStrattegy : multiple machine with one or more GPUs.

Feel free to read [documentation](https://www.tensorflow.org/api_docs/python/tf/distribute) for more info.

![WOiyV](https://user-images.githubusercontent.com/90603477/172453277-f9fcfb33-5cba-45d4-8e82-1dd5632a9f8d.png)
