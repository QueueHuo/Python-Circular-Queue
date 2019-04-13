# Python-Circular-Queue
An simple implementation of circular queue, for timeout operations.

# AN IMPORTANT DECLARATION
I apologize that I failed to install the whole 'pybst' module.
To still use the fantastic AVL tree module inside pybst, I moved some files from the module to this project.
They are:
    avltree.py
    bstree.py
These two files are written by Tyler Sanderson <tylerbtbam@gmail.com>
under the GNU General Public License.

# How to use it
Here's an example:
```Python
from pycq import CircularQueue
circular_queue = CircularQueue(5,10)
circular_queue.start()
circular_queue.insert(1,"hi")
print(circular_queue.poll(1))
```
