# Algorithms

### Expectation
The Developer understands and can implement high-performance data retrieval over complex, structured data sets such as:
 - Search: Breadth / depth first search, A* search
 - Sorting (heal sort, quick sort, merge sort, insertion sort)
 - Hashing: Knowledge of what hash algorithms are and what problems they can address (MD5, collisions, linear probing)

### Experience Justification

## Search ALgorithms

#### Breadth First Search
The breadth first search algorithm is a method of searching through data in graph or tree data structures and it basically involves starting at the root node and traversing the tree by finding the nearest neighbours first, then going one depth deeper into another node.

It finds the shortest path from a given source vertex to all other vertices. It transverses breadthwards, starting from vertices that are of distance K from the source vertex, then moves to vertices that of distance K + 1 and so forth. It is applied in Dijkstra Algorithm.

#### Depth First Search
The depth first search is a method for exploring a tree or graph. In DFS, we go as deep as possible down one path, visiting unvisited nodes before backing up and trying a different one when there are no more unvisited nodes down the current path. 
 
Depth-first search is like walking through a maze. You explore one path, hit a dead end, and go back and try a different one.

#### A* Search
It is used for pathfinding and graph transversal. It is an informed search algorithm, meaning it is formulated in terms of weighted graphs. It aims at finding the shortest path or path with the smallest cost (least distance travelled and shortest time) to a goal node from a source node.

A* search is a combination of Djikstra's and Best First Search algorithms.


## Sorting ALgorithms

#### Heap Sort
Heap sort involves building a Heap data structure from the given array and then utilizing the Heap to sort the array. It does this by first heapifying (building a maximum heap of the array elements) the entire array. When the array is heapified, it swaps the first (which is the largest in a max heap) and the last items, putting the largest item in its place. Then it heapifies the array minus the last item (since it’s already in its correct position), swaps the first and largest in that section, and continues the same process until the entire array is sorted.

#### Quick Sort
Quick sort works by choosing an element as pivot and partitions the given array around the picked pivot, such that the left side of pivot contains all the elements that are less than the pivot element and the right side contains all elements greater than the pivot

#### Merge Sort
Merge sort is a divide-and-conquer algorithm that sorts a list by breaking it down into several sub-lists until each sublist consists of a single element. It then merges those sublists in a manner that results into a sorted list.

#### Insertion Sort 
Insertion sort sorts a list by iterating over the elements and inserting each element into its correct position in the sorted items within the list.
It compares the current element with the largest value in the sorted array. If the current element is greater, then it leaves the element in its place and moves on to the next element else it finds its correct position in the sorted array and moves it to that position.



## Hashing Algorithms

Hashing refers to the process of taking different chunks of data and combining them into a shorter piece of info, which in this case known as a hash.

A hash function is what determines the output of the hashing process. It processes input data of any size and returns a fixed length hash. They are designed to be collision-resistant i.e there should be a low probability that the same hash would be created for different input data.

#### MD5 (Message-Digest Algorithm 5) 
This is a hashing algorithm commonly used to validate data integrity when digital files are transferred or stored.

#### Linear probing 
This is the technique used in resolving collisions in hash tables. In summary, when a collision occurs, the next available slot in the table is used to store the new hash that resulted in a collision. 
