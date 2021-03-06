# JS-DataStructure
Collection of Data Structure concepts, implemented using Javascript.
1. [Stack](#stack)
1. [Queue](#queue)
1. [BubbleSort](#bubble-sort)

## Stack
Stack is a linear data structure which follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out).

### Mainly the following three basic operations are performed in the stack:

| Method        | Description           |
| ------------- |-----------------------|
| push          | Adds an item in the stack at end |
| pop           | Removes an item from the stack. The items are popped in the reversed order in which they are pushed.|
| peek/top      | Returns top element of stack   |
| isEmpty       | Returns true if stack is empty.  |
| printStack    | Returns entire stack  |

**[Code Link](https://github.com/pankajladhar/JS-DataStructure/blob/master/Stack/usingFactory.js)**

## Queue
Like Stack, Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO).  A good example of queue is any queue of consumers for a resource where the consumer that came first is served first. The difference between stacks and queues is in removing. In a stack we remove the item the most recently added; in a queue, we remove the item the least recently added.

### Mainly the following four basic operations are performed on queue::

| Method        | Description           |
| ------------- |-----------------------|
| enqueue          |  Adds an item to the queue |
| dequeue           | Removes an item from the queue. The items are popped in the same order in which they are pushed.|
| front      | Get the front item from queue   |
| rear       | Get the last item from queue  |
| printQueue    | Returns entire queue  |

**[Code Link](https://github.com/pankajladhar/JS-DataStructure/blob/master/Queue/usingFactory.js)**

## Bubble Sort
Bubble sort, sometimes referred to as sinking sort,
    is a simple sorting algorithm that repeatedly steps 
    through the list to be sorted,
    compares each pair of adjacent items and swaps them 
    if they are in the wrong order. 

**[Code Link](https://github.com/pankajladhar/JS-DataStructure/blob/master/BubbleSort/index.js)**

