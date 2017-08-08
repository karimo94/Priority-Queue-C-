Priority Queue C#.Net by Karim Oumghar

My templatized priority queue implementation.

Not for official use, you are responsible for any code you write/copy!

This is based on Min-Heap (i.e. #1,2,3, etc takes higher priority).

Constructors:
<ul><li>Default: initializes the priority queue with default size of 100.</li></ul>
Methods:
<ul>

<li>Enqueue(T obj, int p): takes in a generic object, with its priority, and enqueues into the structure</li>
<li>SiftUp(int index): takes the newly inserted object (index) and places it in its correct position in the priorty queue</li>
<li>GetParentIndex(int index): takes index as input, and returns the parent node index</li>
<li>DecreasePriority(T obj, int p): decreases the priority of a an object within the structure, and assigns new priority value</li>
<li>DequeueMin(): dequeues the object at the front of the priority queue, and returns its instance</li>
<li>SiftDown(int nodeIndex): after dequeuing, we take the data of node at the end of the queue, insert it to the top, delete the last node, re-assign a new index, and pick the next successor to be at the front of the queue</li>
<li>GetLeftChildIndex(int index): returns the left child index of a node index passed in</li>
<li>GetRightChildIndex(int index): returns the right child index of a node index passed in</li>
<li>Peek(): returns the object instance at the front of the queue</li>
<li>Empty(): returns true if there is nothing in the queue</li>

</ul>


![alt text](http://algorithms.tutorialhorizon.com/files/2015/02/Min-Heap.png)
