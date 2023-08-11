# Data Structures
Data structures are fundamental constructs used in computer science and programming to organize and store data in a way that enables efficient manipulation, retrieval, and management. 
</br>
Some common types of data structures include:
1. Arrays
2. Linked Lists. Linked lists consist of nodes, where each node holds data and a reference to the next node in the sequence. Linked lists are efficient for inserting and deleting elements, especially in the middle, but accessing elements requires traversal ( refers to the process of moving through the elements or nodes of the structure sequentially, one by one, linked lists do not offer direct random access like arrays, where you can access elements by their index).
3. Stacks. Stacks follow the Last-In-First-Out (LIFO) principle.
4. Queues: Queues follow the First-In-First-Out (FIFO) principle.
5. Trees. Trees are a way to organize things hierarchically, making them useful for things like organizing files on your computer, representing relationships in databases, or even figuring out the fastest way to search for something in computer programs.
6. Graphs. Graphs help us see how things are connected, help us understand relationships and navigate through information.
7. Hash Tables
8. Heaps. Heap  is like a special arrangement of data where each thing (let's call them "elements") has a value, and the elements are arranged so that the tallest or smallest element is always at the top. Heaps are used in computer programs when you need to quickly find the biggest or smallest value from a collection of data.
9. Tries. Tries are tree-like structures used for storing dynamic sets of strings. They are particularly efficient for searching and indexing.

#  Binary Search Tree
A Binary Search Tree is designed to efficiently store and retrieve data while maintaining a specific order among its elements. It's commonly used in computer science for various applications that involve searching and organizing data.

</br>
A binary search tree, or "ordered binary tree" is a type of binary tree where the nodes are arranged in order: for each node, all elements in its left subtree are less than the parent node, and all the elements in its right subtree are greater than the parent node.
</br>
They are used to implement dictionaries, implement multilevel indexing in DBs. as well as Implementing search algorithms.

# Bloom Filter
A Bloom Filter is a space-efficient probabilistic data structure used for quickly checking whether an item is a member of a set or not. </br>
It's important to note that Bloom Filters can produce false positives due to the possibility of hash collisions (different items hashing to the same positions). </br>
A common use case is checking the availability of a username. This used to be used in search engines, and currently has found use in blockchain technology

#  Disjoint Set ( union find)
It is a data structure that helps keep track of elements that are divided into different groups or sets (according to some criteria)
Disjoint-set is a data structure that keeps track of a elements broken down into sets, of which each set is unique. It is useful for keep track or elements as you can compare sets to see what set they belong to. They are two main functions used on these sets, being union and find.
It has two primary operations: Find and Union
Given an elelement Find will tell you what group an element belongs to. Find(x)
Union merges two groups together
</br>
The main operations it supports are:
MakeSet: This operation creates a new set containing a single element.
Union: This operation combines two sets into one. It takes two elements from different sets and makes them part of the same set.
Find: This operation determines which set an element belongs to. It helps find the representative or parent element of the set to which an element belongs.
The uses for this data structure are compilers and symbolic computation, image processing, network connectivity
