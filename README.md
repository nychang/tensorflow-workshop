# TensorFlow Workshop at Google

[TensorFlow Page](https://www.tensorflow.org/)

## Anaconda Installation

**Create a conda environment called tensorflow:**

Python 2.7
```
$ conda create -n tensorflow python=2.7
```

**Activate the environment:**

```
$ source activate tensorflow
(tensorflow)$  # Your prompt should change
```
 
**Use conda or pip to install TensorFlow inside the environment:**
*(using pip because conda didn't work)*

**Select the correct binary to install:**

Mac OS X, CPU only, Python 2.7:
```
(tensorflow)$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.11.0rc2-py2-none-any.whl
```
**Install for Python 2:**
```
(tensorflow)$ pip install --ignore-installed --upgrade $TF_BINARY_URL
```

## Test Installation

**Activate TensorFlow:** *(if not already activated)*

```
$ source activate tensorflow
(tensorflow)$
```

**Start Python:**
```
$ python
...
>>> import tensorflow as tf
>>> hello = tf.constant('Hello, TensorFlow!')
>>> sess = tf.Session()
>>> print(sess.run(hello))
Hello, TensorFlow!
>>> a = tf.constant(10)
>>> b = tf.constant(32)
>>> print(sess.run(a + b))
42
>>>
```
**Quit Python (Ctrl+D) and deactivate Tensorflow:**
```
(tensorflow)$ source deactivate
$  # Your prompt should change
```


