# Multi-Array Queue

A new Queue data structure that inherits the positive properties of array-based Queues
while removing their main drawback: a fixed size.

The Queue is backed by arrays of Objects with exponentially growing sizes, of which all are in use,
but only the first one (with initialCapacity) is allocated up-front.

[Repository](https://github.com/MultiArrayQueue/MultiArrayQueue)

<img src="Diagram_MultiArrayQueue.png" height="600">

