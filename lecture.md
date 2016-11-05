goo.gl/nrdsxM

artificial intelligence = trying to get machines to do what people do

machine learning = specific way of writing smart programs: programming + data

inception - img reception
parsey mcparseface - 
 - img caption
text summarization

TensorFlow
- open-source ML library
- one system for research & production
- tensor = multidimensional array, data
- flow = graph of operations, how we do math with matrices
- run almost everywhere (CPU, GPU, TPU, mobile)
- CPU vs GPU vs TPU
CPU good at doing complicated operations
GPU good at doing lots of simple operations like multiplying matrices (which is what TensorFlow does) but takes lots of power
TPU designed for tensors

Writing a TensorFlow program:
1. Build a graph...(blueprint for coputation you want done)
```
import tensorflow as tf
a = tf.constant(1)  # node
b = tf.constatnt(2)  # node
c = tf.add(a, b)

session = tf.Session()
value_of_c 
```

