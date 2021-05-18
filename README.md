# DAA-Practical-2021

#### [Error] 'nullptr' was not declared in this scope.

#### if in red_black_tree program, this error occurs,then change language standard (-std) to ISO C++11 in the compiler settings.
```text
##### Common Applications of Sorting:

Searching - Binary search enables you to test whether an item is in a dictionary in O (lg n) time, once 
the keys are all sorted. Search pre-processing is perhaps the single most important application of sorting.

Closest pair - Given a set of n numbers, how do you find the pair of numbers that have the smallest difference 
between them? After the numbers are sorted, the closest pair of numbers will lie next to each other somewhere in 
sorted order.

Element uniqueness - Are there any duplicates in a given a set of n items? The most efficient algorithm is to sort them 
and then do a linear scan though them checking all adjacent pairs.

Frequency distribution - Given a set of n items, which element occurs the largest number of times in the set? If the items 
are sorted, we can sweep from left to right and count them, since all identical items will be lumped together during sorting.

Selection - What is the kth largest item in the set? If the keys are placed in sorted order in an array, the kth largest can be 
found in constant time by simply looking at the kth position of the array.
time complexity:-
Bubble sort :- worst   :-  О(N^2)
               average :-  Θ(N^2)
               best    :-  Ω(N)
               
Selection sort :- worst   :- O(N^2)
                  average :- Θ(N^2)
                  best    :- Ω(N^2)
               
Insertion sort :- worst   :- O(N^2)
                  average :- Θ(N^2)
                  best    :- 	Ω(N)		
               
Merge sort :- worst   :- O(N log N)
              average :- Θ(N log N)	
              best    :- Ω(N logN)
              
Quick sort :- worst   :- O(N^2)
              average :- Θ(N logN)	
              best    :- Ω(N logN)
```       
```text          
A minimum spanning tree (MST) or minimum weight spanning tree for a weighted, connected, undirected graph is a 
spanning tree with a weight less than or equal to the weight of every other spanning tree. The weight of a spanning 
tree is the sum of weights given to each edge of the spanning tree.

A minimum spanning tree has (V – 1) edges where V is the number of vertices in the given graph. 

the given minimum spanning tree algorithm is Kruskal’s Minimum Spanning Tree Algorithm.
it is a greedy algorithm.
Kruskal’s algorithm’s time complexity is O(E log V), V being the number of vertices.
Kruskal’s algorithm runs faster in sparse graphs.
```
```text
A red-black tree is a kind of self-balancing binary search tree where each node has an extra bit, and that bit is often 
interpreted as the colour (red or black). These colours are used to ensure that the tree remains balanced during insertions 
and deletions. Although the balance of the tree is not perfect, it is good enough to reduce the searching time and maintain 
it around O(log n) time, where n is the total number of elements in the tree.

Real-world uses of red-black trees include TreeSet, TreeMap, and Hashmap in the Java Collections Library. Also, the Completely Fair 
Scheduler in the Linux kernel uses this data structure. Linux also uses red-black trees in the mmap and munmap operations for file/memory 
mapping.

Furthermore, red-black trees are used for geometric range searches, k-means clustering, and text-mining.
```
