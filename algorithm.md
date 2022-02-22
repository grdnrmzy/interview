1. What main data structures do you know?

---

## What is a Data Structure?

Data structures are methods of storing and organizing data in a computer system so that operations can be performed upon them more efficiently. When data is “unstructured,” it does not have a defined data model or is not organized in a manner that is conducive to operations or analysis.

Unstructured data is a common problem at organizations that have collected data but haven’t been storing or organizing it effectively. It is estimated that **80% of the world’s data is unstructured.** ^1^

Data structures take the form of different layouts, each of which is efficient for some operations but inefficient for others. The goal of the programmer is to determine which data structures are suitable for the data on hand so that that data can be leveraged to solve problems.

## Eight Data Structures to Master

Below are some of the most important data structures to be aware of. This isn’t an exhaustive list, and you can experiment to create your own data structures. But these are the building blocks that can help you establish a career in programming and data analysis.

### 1. Arrays

One of the simplest data structures, an array is a collection of items that are stored sequentially. An array contains values or variables—known as “elements”—of the same data type and is of a fixed size, so you cannot change the size of an array. Each item in an array is indexed starting with 0.

The best way to think about an array is like a weekly medication organizer. It includes small containers lined up in a sequence, and each container has elements inside.

Arrays are commonly used as structures for building other, more complicated data structures. They are also used for sorting algorithms.

### 2. Linked Lists

A linked list is a sequence of items arranged in a linear order all connected to each other. This means you must access data in order, so random access to data is not possible.

Each element in a linked list is called a “node,” and each node contains a key and a pointer. The pointer directs you to the next node, called a “next.” The sequence starts with a “head,” which directs you to the first element within the list. The last element of this list is known as the “tail.”

You can create a singly linked list, which lets you traverse each item in a forward direction from the head to the tail. Similarly, you can create a doubly-linked list, which can be traversed both forward and backward. And finally, you can create a circular linked list in which the next pointer of the tail points to the head and vice versa, forming a circle.

Linked lists are used for symbol table management in switching between programs using Alt + Tab (On a PC).

### 3. Stacks

A stack works almost exactly as it sounds. It’s like stacking elements within a tall container.

Stacks are known as LIFO (Last In First Out) structures. This means the element placed last can be accessed first. You can “push” a new element onto the top of the stack, or you can “pop,” deleting the element inserted last which is at the top of the stack.

Stacks are commonly used for parsing and evaluating mathematical expressions and to implement function calls in recursion programming.

### 4. Queues

A queue functions similarly to a stack, but instead of being a LIFO structure, it is a FIFO (First In First Out) structure. The easiest way to think about a queue is to think of a line of people waiting to enter a building. The person at the beginning of the line will enter the building first, while the person at the end will enter last.

You can enqueue an element in this structure, which means inserting the element to the end of the queue. You can also dequeue an element, which means deleting an element from the beginning of the queue.

Queues are often used to manage threads in multithreading, and they are (not surprisingly) used to implement priority queuing systems.

### 5. Hash Tables

A hash table structure associates each value with a key and then stores them. This makes it easy to look up values efficiently using a key. It’s an efficient way to insert and search for data regardless of its size, as it makes it easy to identify a specific object from a group of similar objects.

For example, if you go to college, you may be assigned a unique student ID number. This ID number is a key that can be used to retrieve information about you and your student record.

A hash table uses what’s known as a “hash function” to map a data set of any size to one of a fixed size—the hash table. The values that a hash function returns are known as “hash values.”

Hash tables are commonly used to create database indexes, to create associative arrays and to create a “set.”

### 6. Trees

A tree is a structure similar to a linked list because each item is linked. But in a tree items are linked in a hierarchal fashion, just like you might see in a visual representation of someone’s family tree. There are various types of trees, each suited to different applications.

For example, a binary search tree (BST) stores data in sorted order with every node in the binary comprised of the following attributes:

* Key (the value saved in the node)
* Left (pointer to the left child node)
* Right (pointer to the right child node)
* P (pointer to the parent node)

Binary search trees are used in many different types of search applications. Other types of trees are used in wireless networking and to create expression solvers.

### 7. Heaps

Similarly, a heap is a type of binary tree in which the parent nodes are compared to their children. This allows the values within the nodes to be arranged accordingly. Heaps can be represented as trees, but they can also be represented as binary arrays.

There are two types of heaps. In a min heap, the parent’s key is less than or equal to the keys of its children. In a max heap, the parent’s key is greater than or equal to the keys of its children.

Heaps are often used in algorithms to create priority queues, and to find the smallest or largest value in an array.

### 8. Graphs

A graph is an abstract, non-linear data structure that is made of a finite set of nodes that are connected by edges. The nodes may be referred to as “vertices” and contain values, whereas the edges are simply lines or arcs that connect two nodes in the graph.

Graphs are often used to represent networks, such as circuit networks or even paths in a city. They're great for solving real-world problems, but they can also be used as representations of digital networks.

For example, on Facebook, each user could be represented with a node (or vertex). Each vertex could then contain information about that user, and each edge could represent their connection with another user.

---

2. As a data container, what are the main differences between array and list?


| List                                                                      | Array                                                                 |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Can consist of elements belonging to different data types                 | Only consists of elements belonging to the same data type             |
| No need to explicitly import a module for declaration                     | Need to explicitly import a module for declaration                    |
| Cannot directly handle arithmetic operations                              | Can directly handle arithmetic operations                             |
| Can be nested to contain different type of elements                       | Must contain either all nested elements of same size                  |
| Preferred for shorter sequence of data items                              | Preferred for longer sequence of data items                           |
| Greater flexibility allows easy modification (addition, deletion) of data | Less flexibility since addition, deletion has to be done element wise |
| The entire list can be printed without any explicit looping               | A loop has to be formed to print or access the components of array    |
| Consume larger memory for easy addition of elements                       | Comparatively more compact in memory size                             |

---

3. What is the difference between singly linked list and doubly linked list data structures?

**Singly linked list vs Doubly linked list**


| Singly linked list (SLL)                                                                                                                                                            | Doubly linked list (DLL)                                                                                                                                         |   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- |
| SLL nodes contains 2 field -data field and next link field.                                                                                                                         | DLL nodes contains 3 fields -data field, a previous link field and a next link field.                                                                            |   |
| [![linkedlist](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png) | [![dll](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/03/DLL1.png)](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/03/DLL1.png) |   |
| In SLL, the traversal can be done using the next node link only. Thus traversal is possible in one direction only.                                                                  | In DLL, the traversal can be done using the previous node link or the next node link. Thus traversal is possible in both directions (forward and backward).      |   |
| The SLL occupies less memory than DLL as it has only 2 fields.                                                                                                                      | The DLL occupies more memory than SLL as it has 3 fields.                                                                                                        |   |
| Complexity of insertion and deletion at a given position is O(n).                                                                                                                   | Complexity of insertion and deletion at a given position is O(1).                                                                                                |   |

---

4. What is the difference between stack and queue data structures?

   Stack and Queue both are the non-primitive data structures. The main differences between stack and queue are that stack uses LIFO (last in first out) method to access and add data elements whereas Queue uses FIFO (First in first out) method to access and add data elements.

---

5. What is algorithm complexity?

**Complexity of an algorithm is** **a measure of the amount of time and/or space required by an algorithm for an input of a given size (n)**

---

6. What are associative unordered and ordered containers?

## What are associative unordered and ordered containers?

The unordered associative containers are similar to the associative containers in the C++ Standard Library but have different constraints. As their name implies, the elements in the unordered associative containers are not ordered. The containers can still be iterated through like a regular associative container.

## What is associative container explain any two associative containers with their functions?

The defining characteristic of associative containers is that elements are inserted in a pre-defined order, such as sorted ascending. The associative containers can be grouped into two subsets: maps and sets. A map, sometimes referred to as a dictionary, consists of a key/value pair.

## What are sequence containers derived containers and associative containers?

Sequence containers implement data structures which can be accessed sequentially. Associative containers implement sorted data structures that can be quickly searched (O(log n) complexity).

## Is Vector a container?

Vector is a sequential container. Vector is not index based. Array is a fixed-size sequential collection of elements of the same type. Array is index based.

## What is the difference between map and multimap?

The essential difference between the two is that in a map the keys must be unique, while a multimap permits duplicate keys. In both containers, the sort order of components is the sort order of the keys, with the values corresponding to keys determining the order for duplicate keys in a multimap.

## What two types of containers does the STL provide?

Two basic types of containers:

* Sequences. User controls the order of elements. vector, list, deque.
* Associative containers. The container controls the position of elements within it. Elements can be accessed using a key. set, multiset, map, multimap.

## What is STL algorithm?

The Standard Template Library (STL) is a set of C++ template classes to provide common programming data structures and functions such as lists, stacks, arrays, etc. It is a library of container classes, algorithms, and iterators. A working knowledge of template classes is a prerequisite for working with STL.

## What is the difference between map and multimap associative containers?

The map and the multimap are both containers that manage key/value pairs as single components. The essential difference between the two is that in a map the keys must be unique, while a multimap permits duplicate keys.

## Why sequence container is used in SSIS?

The sequence container in SSIS is useful for grouping tasks together. We can split the control flow into multiple logical units using this. We will explore more on the Sequence container in this article.

## What is the main difference between a sequence container and an associative container?

Associative containers are designed to be especially efficient in accessing its elements by their key, as opposed to sequence containers which are more efficient in accessing elements by their position.

## How is unordered_multimap implemented?

The internal implementation of unordered_multimap is the same as that of unordered_map but for duplicate keys, another count value is maintained with each key-value pair.

## Can unordered_map have multiple values?

You can use both vector and pair as mentioned. You can also consider creating a struct if the number of values is fixed. This may be easier when you have multiple values from multiple data types in a single record.

## Does unordered map allow duplicates?

Because unordered_map containers do not allow for duplicate keys, this means that the function actually returns 1 if an element with that key exists in the container, and zero otherwise.

## Does unordered set allow duplicates?

Unordered sets do not allow duplicates and are initialized using comma-delimited values enclosed in curly braces.

## Which is an example of an unordered STL container?

For example, std::set is typically implemented as a red-black tree. Unordered STL containers are based on hash algorithms and unordered_set is a hash table. Unordered containers typically offer better algorithmic cost for operations like insertion, lookup and removal.

## How are the associative containers defined in STL?

The STL standard associative containers (set, multiset, map, multimap) allow access to elements using a key: For set and multiset element is its own key. For map and multimap elements are of type pair . pair is a standard template class defined as:

## What do you need to know about STL containers?

Container basics An STL container is a collection of objects of the same type (the elements). Container ownsthe elements. Creation and destruction is controlled by the container. Two basic types of containers: Sequences User controls the order of elements. vector, list, deque Associative containers

## What’s the difference between ordered and unordered containers?

The main difference is that if you iterate through an ordered container by incrementing the iterator, you’ll visit the elements of the container in the order of the keys. That doesn’t necessarily hold for unordered containers.

---

7. Explain what the binary tree is



## What Does Binary Tree Mean?

A binary tree is a tree data structure where each node has up to two child nodes, creating the branches of the tree. The two children are usually called the left and right nodes. Parent nodes are nodes with children, while child nodes may include references to their parents.

## Techopedia Explains Binary Tree

A binary tree is made up of at most two nodes, often called the left and right nodes, and a data element. The topmost node of the tree is called the root node, and the left and right pointers direct to smaller subtrees on either side.

Binary trees are used to implement binary search trees and binary heaps. They are also often used for sorting data as in a heap sort.

---

8. What is the difference between depth-first and breadth-first searches for binary tree?


**What are BFS and DFS for Binary Tree?**
A Tree is typically traversed in two ways:

* [Breadth First Traversal (Or Level Order Traversal)](https://www.geeksforgeeks.org/level-order-tree-traversal/)
* [Depth First Traversals](https://www.geeksforgeeks.org/618/)
  * Inorder Traversal (Left-Root-Right)
  * Preorder Traversal (Root-Left-Right)
  * Postorder Traversal (Left-Right-Root)

![Example Tree](https://media.geeksforgeeks.org/wp-content/cdn-uploads/2009/06/tree12.gif "tree12")

```
BFS and DFSs of above Tree

Breadth First Traversal : 1 2 3 4 5

Depth First Traversals:
      Preorder Traversal : 1 2 4 5 3 
      Inorder Traversal  :  4 2 5 1 3 
      Postorder Traversal : 4 5 2 3 1
```

**Why do we care?**
There are many tree questions that can be solved using any of the above four traversals. Examples of such questions are [size](https://www.geeksforgeeks.org/write-a-c-program-to-calculate-size-of-a-tree/), [maximum](http://geeksquiz.com/find-maximum-or-minimum-in-binary-tree/), [minimum](http://geeksquiz.com/find-maximum-or-minimum-in-binary-tree/), [print left view](https://www.geeksforgeeks.org/print-left-view-binary-tree/), etc.

**Is there any difference in terms of Time Complexity?**
All four traversals require O(n) time as they visit every node exactly once.

**Is there any difference in terms of Extra Space?**
There is difference in terms of extra space required.

1. Extra Space required for Level Order Traversal is O(w) where w is maximum width of Binary Tree. In level order traversal, queue one by one stores nodes of different level.
2. Extra Space required for Depth First Traversals is O(h) where h is maximum height of Binary Tree. In Depth First Traversals, stack (or function call stack) stores all ancestors of a node.

Maximum Width of a Binary Tree at depth (or height) h can be 2^h^ where h starts from 0. So the maximum number of nodes can be at the last level. And worst case occurs when Binary Tree is a perfect Binary Tree with numbers of nodes like 1, 3, 7, 15, …etc. In worst case, value of 2^h^ is **Ceil(n/2)** .

Height for a Balanced Binary Tree is O(Log n). Worst case occurs for skewed tree and worst case height becomes O(n).

So in worst case extra space required is O(n) for both. But worst cases occur for different types of trees.

***It is evident from above points that extra space required for Level order traversal is likely to be more when tree is more balanced and extra space for Depth First Traversal is likely to be more when tree is less balanced.***

**How to Pick One?**

1. Extra Space can be one factor (Explained above)
2. Depth First Traversals are typically recursive and recursive code requires function call overheads.
3. The most important points is, BFS starts visiting nodes from root while DFS starts visiting nodes from leaves. So if our problem is to search something that is more likely to closer to root, we would prefer BFS. And if the target node is close to a leaf, we would prefer DFS.

---



Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. Some examples of how hashing is used in our lives include:

* In universities, each student is assigned a unique roll number that can be used to retrieve information about them.
* In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.

In both these examples the students and books were hashed to a unique number.

Assume that you have an object and you want to assign a key to it to make searching easy. To store the key/value pair, you can use a simple array like a data structure where keys (integers) can be used directly as an index to store values. However, in cases where the keys are large and cannot be used directly as an index, you should use *hashing* .

In hashing, large keys are converted into small keys by using **hash functions** . The values are then stored in a data structure called **hash table** . The idea of hashing is to distribute entries (key/value pairs) uniformly across an array. Each element is assigned a key (converted key). By using that key you can access the element in **O(1)** time. Using the key, the algorithm (hash function) computes an index that suggests where an entry can be found or inserted.

Hashing is implemented in two steps:

1. An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
2. The element is stored in the hash table where it can be quickly retrieved using hashed key.
   hash = hashfunc(key)
   index = hash % array_size

In this method, the hash is independent of the array size and it is then reduced to an index (a number between 0 and array_size − 1) by using the modulo operator (%).

**Hash function**
A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.

To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:

1. Easy to compute: It should be easy to compute and must not become an algorithm in itself.
2. Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.
3. Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.
   **Note** : Irrespective of how good a hash function is, collisions are bound to occur. Therefore, to maintain the performance of a hash table, it is important to manage collisions through various collision resolution techniques.

***Need for a good hash function***

Let us understand the need for a good hash function. Assume that you have to store strings in the hash table by using the hashing technique {“abcdef”, “bcdefa”, “cdefab” , “defabc” }.

To compute the index for storing the strings, use a hash function that states the following:

The index for a specific string will be equal to the sum of the ASCII values of the characters modulo 599.

As 599 is a prime number, it will reduce the possibility of indexing different strings (collisions). It is recommended that you use prime numbers in case of modulo. The ASCII values of a, b, c, d, e, and f are 97, 98, 99, 100, 101, and 102 respectively. Since all the strings contain the same characters with different permutations, the sum will 599.

The hash function will compute the same index for all the strings and the strings will be stored in the hash table in the following format. As the index of all the strings is the same, you can create a list on that index and insert all the strings in that list.

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/dda3e36.jpg)

Here, it will take **O(n)** time (where n is the number of strings) to access a specific string. This shows that the hash function is not a good hash function.

Let’s try a different hash function. The index for a specific string will be equal to sum of ASCII values of characters multiplied by their respective order in the string after which it is modulo with 2069 (prime number).

String                                Hash function                               Index
abcdef       (97*1 + 98* 2 + 99*3 + 100* 4 + 101*5 + 102* 6)%2069       38
bcdefa       (98*1 + 99* 2 + 100*3 + 101* 4 + 102*5 + 97* 6)%2069       23
cdefab       (99*1 + 100* 2 + 101*3 + 102* 4 + 97*5 + 98* 6)%2069       14
defabc       (100*1 + 101* 2 + 102*3 + 97* 4 + 98*5 + 99* 6)%2069       11

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/e880c21.jpg)

**Hash table**
A hash table is a data structure that is used to store keys/value pairs. It uses a hash function to compute an index into an array in which an element will be inserted or searched. By using a good hash function, hashing can work well. Under reasonable assumptions, the average time required to search for an element in a hash table is **O(1)** .

Let us consider string S. You are required to count the frequency of all the characters in this string.

```
string S = “ababcd”
```

The simplest way to do this is to iterate over all the possible characters and count their frequency one by one. The time complexity of this approach is **O(26*N)** where **N** is the size of the string and there are 26 possible characters.

```
  void countFre(string S)
    {
        for(char c = ‘a’;c <= ‘z’;++c)
        {
            int frequency = 0;
            for(int i = 0;i < S.length();++i)
                if(S[i] == c)
                    frequency++;
            cout << c << ‘ ‘ << frequency << endl;
        }
    }
```

**Output**

```
a 2
b 2
c 1
d 1
e 0
f 0
…
z 0
```

Let us apply hashing to this problem. Take an array frequency of size 26 and hash the 26 characters with indices of the array by using the hash function. Then, iterate over the string and increase the value in the frequency at the corresponding index for each character. The complexity of this approach is **O(N)** where **N** is the size of the string.

```
 int Frequency[26];

    int hashFunc(char c)
    {
        return (c - ‘a’);
    }

    void countFre(string S)
    {
        for(int i = 0;i < S.length();++i)
        {
            int index = hashFunc(S[i]);
            Frequency[index]++;
        }
        for(int i = 0;i < 26;++i)
            cout << (char)(i+’a’) << ‘ ‘ << Frequency[i] << endl;
    }
```

**Output**

```
a 2
b 2
c 1
d 1
e 0
f 0
…
z 0
```

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/7ea3425.jpg)

**Collision resolution techniques**

*Separate chaining (open hashing)*

Separate chaining is one of the most commonly used collision resolution techniques. It is usually implemented using linked lists. In separate chaining, each element of the hash table is a linked list. To store an element in the hash table you must insert it into a specific linked list. If there is any collision (i.e. two different elements have same hash value) then store both the elements in the same linked list.

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/0e2c706.png)

The cost of a lookup is that of scanning the entries of the selected linked list for the required key. If the distribution of the keys is sufficiently uniform, then the average cost of a lookup depends only on the average number of keys per linked list. For this reason, chained hash tables remain effective even when the number of table entries (N) is much higher than the number of slots.

For separate chaining, the worst-case scenario is when all the entries are inserted into the same linked list. The lookup procedure may have to scan all its entries, so the worst-case cost is proportional to the number (N) of entries in the table.

In the following image, **CodeMonk** and **Hashing** both hash to the value **2** . The linked list at the index **2** can hold only one entry, therefore, the next entry (in this case **Hashing** ) is linked (attached) to the entry of **CodeMonk** .

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/2cabd32.jpg)

***Implementation of hash tables with separate chaining (open hashing)***

*Assumption*

Hash function will return an integer from 0 to 19.

```
vector <string> hashTable[20];
    int hashTableSize=20;
```

*Insert*

```
   void insert(string s)
    {
                // Compute the index using Hash Function
        int index = hashFunc(s);
        // Insert the element in the linked list at the particular index
        hashTable[index].push_back(s);
    }
```

*Search*

```
   void search(string s)
    {
        //Compute the index by using the hash function
        int index = hashFunc(s);
        //Search the linked list at that specific index
        for(int i = 0;i < hashTable[index].size();i++)
        {
            if(hashTable[index][i] == s)
            {
                cout << s << " is found!" << endl;
                return;
            }
        }
        cout << s << " is not found!" << endl;
    }
```

***Linear probing (open addressing or closed hashing)***

In open addressing, instead of in linked lists, all entry records are stored in the array itself. When a new entry has to be inserted, the hash index of the hashed value is computed and then the array is examined (starting with the hashed index). If the slot at the hashed index is unoccupied, then the entry record is inserted in slot at the hashed index else it proceeds in some probe sequence until it finds an unoccupied slot.

The probe sequence is the sequence that is followed while traversing through entries. In different probe sequences, you can have different intervals between successive entry slots or probes.

When searching for an entry, the array is scanned in the same sequence until either the target element is found or an unused slot is found. This indicates that there is no such key in the table. The name "open addressing" refers to the fact that the location or address of the item is not determined by its hash value.

Linear probing is when the interval between successive probes is fixed (usually to 1). Let’s assume that the hashed index for a particular entry is **index** . The probing sequence for linear probing will be:

index = index % hashTableSize
index = (index + 1) % hashTableSize
index = (index + 2) % hashTableSize
index = (index + 3) % hashTableSize

and so on…

![enter image description here](https://he-s3.s3.amazonaws.com/media/uploads/9c56c0d.jpg)

Hash collision is resolved by open addressing with linear probing. Since **CodeMonk** and **Hashing** are hashed to the same index i.e. **2** , store **Hashing** at **3** as the interval between successive probes is **1** .

***Implementation of hash table with linear probing***

*Assumption*

* There are no more than 20 elements in the data set.
* Hash function will return an integer from 0 to 19.
* Data set must have unique elements.

```
 string hashTable[21];
    int hashTableSize = 21;
```

*Insert*

```
void insert(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc(s);
        //Search for an unused slot and if the index will exceed the hashTableSize then roll back
        while(hashTable[index] != "")
            index = (index + 1) % hashTableSize;
        hashTable[index] = s;
    }
```

*Search*

```
   void search(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc(s);
         //Search for an unused slot and if the index will exceed the hashTableSize then roll back
        while(hashTable[index] != s and hashTable[index] != "")
            index = (index + 1) % hashTableSize;
        //Check if the element is present in the hash table
        if(hashTable[index] == s)
            cout << s << " is found!" << endl;
        else
            cout << s << " is not found!" << endl;
    }
```

**Quadratic Probing**

Quadratic probing is similar to linear probing and the only difference is the interval between successive probes or entry slots. Here, when the slot at a hashed index for an entry record is already occupied, you must start traversing until you find an unoccupied slot. The interval between slots is computed by adding the successive value of an arbitrary polynomial in the original hashed index.

Let us assume that the hashed index for an entry is **index** and at **index** there is an occupied slot. The probe sequence will be as follows:

index = index % hashTableSize
index = (index + 1^2^ ) % hashTableSize
index = (index + 2^2^ ) % hashTableSize
index = (index + 3^2^ ) % hashTableSize

and so on…

***Implementation of hash table with quadratic probing***

*Assumption*

* There are no more than 20 elements in the data set.
* Hash function will return an integer from 0 to 19.
* Data set must have unique elements.

```
string hashTable[21];
    int hashTableSize = 21;
```

**Insert**

```
   void insert(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc(s);
        //Search for an unused slot and if the index will exceed the hashTableSize roll back
        int h = 1;
        while(hashTable[index] != "")
        {
            index = (index + h*h) % hashTableSize;
                 h++;
        }
        hashTable[index] = s;
    }
```

**Search**

```
void search(string s)
    {
        //Compute the index using the Hash Function
        int index = hashFunc(s);
         //Search for an unused slot and if the index will exceed the hashTableSize roll back
       int h = 1;
        while(hashTable[index] != s and hashTable[index] != "")
        {
            index = (index + h*h) % hashTableSize;
                 h++;
        }
        //Is the element present in the hash table
        if(hashTable[index] == s)
            cout << s << " is found!" << endl;
        else
            cout << s << " is not found!" << endl;
    }
```

**Double hashing**

Double hashing is similar to linear probing and the only difference is the interval between successive probes. Here, the interval between probes is computed by using two hash functions.

Let us say that the hashed index for an entry record is an index that is computed by one hashing function and the slot at that index is already occupied. You must start traversing in a specific probing sequence to look for an unoccupied slot. The probing sequence will be:

index = (index + 1 * indexH) % hashTableSize;
index = (index + 2 * indexH) % hashTableSize;

and so on…

Here, **indexH** is the hash value that is computed by another hash function.

**Implementation of hash table with double hashing**

*Assumption*

* There are no more than 20 elements in the data set.
* Hash functions will return an integer from 0 to 19.
* Data set must have unique elements.

```
    string hashTable[21];
    int hashTableSize = 21;
```

**Insert**

```
  void insert(string s)
    {
        //Compute the index using the hash function1
        int index = hashFunc1(s);
        int indexH = hashFunc2(s);
        //Search for an unused slot and if the index exceeds the hashTableSize roll back
        while(hashTable[index] != "")
            index = (index + indexH) % hashTableSize;
        hashTable[index] = s;
    }
```

**Search**

```
  void search(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc1(s);
        int indexH = hashFunc2(s);
         //Search for an unused slot and if the index exceeds the hashTableSize roll back
        while(hashTable[index] != s and hashTable[index] != "")
            index = (index + indexH) % hashTableSize;
        //Is the element present in the hash table
        if(hashTable[index] == s)
            cout << s << " is found!" << endl;
        else
            cout << s << " is not found!" << endl;
    }
```
