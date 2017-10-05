![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

--------

#### Update:

Calculate mAP from detection files:

```Shell
python reval_voc.py results/
```

For detailed usage, try

```shell
python reval_voc.py -h
```

Note: The evaluation script is adapt ed from [py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn).