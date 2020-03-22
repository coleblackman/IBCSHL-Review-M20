- [Topic 5 Abstract data structures](#topic-5-abstract-data-structures)
  - [Recursion](#recursion)
    - [5.1.1 Situations using recursion](#511-situations-using-recursion)
    - [5.1.2 Recursive thinking](#512-recursive-thinking)
    - [5.1.3 Trace recursion](#513-trace-recursion)
  - [ADTs](#adts)
    - [5.1.4-5 Two-dimensional arrays](#514-5-two-dimensional-arrays)
    - [5.1.6-7 Stacks](#516-7-stacks)
    - [5.1.8-9 Queue](#518-9-queue)
  - [Linked Lists](#linked-lists)
    - [5.1.11 dynamic data structure](#5111-dynamic-data-structure)
    - [LL diagrams](#ll-diagrams)
  - [Trees](#trees)
    - [5.1.16 Traversals](#5116-traversals)
      - [In-order](#in-order)
      - [Post-order](#post-order)
      - [Pre-order](#pre-order)
    - [5.1.19 static vs dynamic data structures](#5119-static-vs-dynamic-data-structures)

# Topic 5 Abstract data structures

## Recursion

### 5.1.1 Situations using recursion

- Snowflakes, fractals, tower of hanoi

### 5.1.2 Recursive thinking

### 5.1.3 Trace recursion


## ADTs

### 5.1.4-5 Two-dimensional arrays

### 5.1.6-7 Stacks

LIFO
push/pop
isEmpty in java
ex: undo button, call stack, browser back button

### 5.1.8-9 Queue

FIFO
enqueue/dequeue
ex: CPU scheduling, print queue, keyboard buffer

## Linked Lists

- Unlike arrays, sequential access only
- Not static 
- dynamic
- Easy to insert/delete from middle of a LL

- each element is a node
  - Stores information
  - Points to the next node

### 5.1.11 dynamic data structure
 
> DDS - has the ability to shrink/grow

> pointer - variable whose value is the address of another variable

### LL diagrams
Circularly linked list:

![](2020-03-21-15-03-18.png)

Doubly linked list

Singly linked list

Circularly Doubly linked list

## Trees

binary trees are not ordered, binary search trees are ordered

### 5.1.16 Traversals

![](2020-03-21-15-12-58.png) 
- Dartford Grammar School



#### In-order
LEFT → NODE → RIGHT
#### Post-order
LEFT → RIGHT → NODE
#### Pre-order
NODE → LEFT → RIGHT

> Dynamic data structure

### 5.1.19 static vs dynamic data structures
(Computersciencewiki.org)
| Static Data Structure                                                                                           | Dynamic data structure                                                                                  |
|-----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| Inefficient as memory is allocated that may not be needed.                                                      | Efficient as the amount of memory varies as needed.                                                     |
| Fast access to each element of data as the memory location is fixed when the program is written.                | Slower access to each element as the memory location is allocated at run-time.                          |
| Memory addresses allocated will be contiguous so quicker to access.                                             | Memory addresses allocated may be fragmented so slower to access.                                       |
| Structures are a fixed size, making them more predictable to work with. For example, they can contain a header. | Structures vary in size so there needs to be a mechanism for knowing the size of the current structure. |
| The relationship between different elements of data does not change.                                            | The relationship between different elements of data will change as the program is run.                  |



