# Data Structures and ALgorithms

[Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

[Data Structures in 15min](https://www.youtube.com/watch?v=sVxBVvlnJsM)

Data structure being measured on how well an operation scales is called the Big O.

[Big O Explained](https://www.youtube.com/watch?v=v4cd1O4zkGw)

[Basic Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

Array is fixed sized and holds items of the same data type

* operations: traverse, search, update

Linked List is a sequential structure that consists of a sequence of items in linear order which are linked to each other.

* each element in the list is a node, each node has a key and pointer to successor node know as next, the head attribute points to the first element of the linked list, the last element is the tail

* types: singly linked list, doubly linked list, circular linked list

Why Big O

Big O is how Time scales with respect to some input variables

Describe runtime (of mowing grass)

O(a) where a is the amount of area

O(s^2)

If there are two different steps, add them together.

**Questions:**

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
    * The problem domain needs to be considered because not all data structures are created equal and may have accessibility issues or inability do to something needed for the application.
2. How can we ensure that we’ll avoid an infinite recursive call stack?
    * create a Base case so that it does not go in an infinite loop.
