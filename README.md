# DAA-Practical-2021

complexity in Red-Black Tree -
inserting a node - O(log n)
deleting a node - O(log n)
searching a node - O(log n)

Applications of Red-Black Tree
1) Real-world uses of red-black trees include TreeSet, TreeMap, and Hashmap in the Java Collections Library.
2) Linux also uses red-black trees in the mmap and munmap operations for file/memory mapping.
3) Red-Black trees are used for geometric range searches, k-means clustering, and text-mining.

Time complexity    bubble    selection   insertion   merge   
best                O(n)      O(n^2)      O(n)        O(nlogn)
average             O(n^2)    O(n^2)      O(n^2)      O(nlogn)
worst               O(n^2)    O(n^2)      O(n^2)      O(nlogn)

quick sort is a divide and conquer approach with  T(n) = T(k) + T(n-k-1) + cn
worst case -  T(n) = T(0) + T(n-1) + cn = O(n^2)
best case -   T(n) = 2T(n/2) + cn = O(nlogn)
average case - T(n) = 2T(n/2) + cn = O(nlogn)

applications -
bubble sort - It can be used to sort the students on basis of their height in a line.
selection sort - Can be useful when memory write is a costly operation.
insertion sort - Insertion sort is used when number of elements is small. It can also be useful when input array is almost sorted, only few elements are misplaced in complete big array.
merge sort - Merge sort can be implemented without extra space for linked lists.
quick sort - Quicksort is used everywhere where a stable sort is not needed.
