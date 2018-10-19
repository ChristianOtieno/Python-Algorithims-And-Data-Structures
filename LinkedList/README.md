# lINKED liST

## ADVANTAGES

1. Linked lists are dynamic data structures(arrays are not!!!)
2. It can allocate the needed memory in run-time
3. Very efficient if we want to manipulate the first elements
4. EASY IMPLEMENTATIONS
5. Can store items with different sizes: an array assumes every element to be exactly the same
6. Is's easier for a linked list to grow ioragnically. An array's sixe needs to be known ahead of time, or re-created when it needs to grow

## DISADVANTAGES

1. Waste memory because of the references
2. Nodes in linked list must be read in order from the beginning as linked lists have sequential access(array items can be reached via indexes in O(1) time !!!)
3. Difficulties arise in linked lists when it comes to reverse traversing. Singly linked lists are extremely difficult to navigate backwards,

>Solution: doubly linked lists-> easier to read, but memory is wasted in allocating space for a back pointer.

## DELETING FROM LINKED LIST

1. The same as for insertion
2. O(1) time complexity: if we insert items at the beginning
3. O(N)time complexity: for inserting items at the end of list