1. What are the order of insertions/removals for the following data structures?
   - **Stack**: LAFO(last in, first out)
   - **Queue**: FAFO(first in, first out)

2. What is the retrieval time complexity for the following data structures?
    - **Linked List**
The traditional indexed for loop operation for linked list traversal is very slow as in order to retrieve any element the search has to start from the beginning.
    - **Hash Table**
Hash tables provide O(1) lookup on average, regardless of the number of items in the table. Worst case, time complexity in big O notation is O(n). 
    - **Binary Search Trees**
Binary search tree allow the operations to skip about half of the tree, so that each lookup takes time proportional to the logarithm of the number of items stored in the tree. It's much better than the linear time required to find the items by key in an unsorted array, but slower than the correspoding operations on hash tables. In the worst case, it takes time proportional to the tree's height. 

3. What are some advantages to using a Hash Tables over an array in JavaScript?
It can efficiently search/retrieve, insert and remove in one operation (O(1)). 