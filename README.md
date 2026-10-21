  # PRACTICAL-1

## Summary

In this practical, different sorting techniques such as **Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort** were implemented and analyzed. Their execution times and time complexities were compared to understand their performance. Bubble Sort, Selection Sort, and Insertion Sort generally take **O(n²)** time, while Merge Sort and Quick Sort are more efficient for larger datasets. Merge Sort has **O(n log n)** time complexity in all cases, whereas Quick Sort provides **O(n log n)** average performance but may take **O(n²)** in the worst case.

## Conclusion

The practical demonstrates that sorting algorithms differ significantly in their performance. Simple algorithms such as Bubble, Selection, and Insertion Sort are suitable for smaller datasets, while Merge Sort and Quick Sort are better choices for larger datasets. The comparison helps in selecting an appropriate sorting technique based on the size and requirements of the data.

  

  
# PRACTICAL-2

## Summary

In this practical, **Linear Search and Binary Search** algorithms were implemented and compared based on their performance. Linear Search checks the elements sequentially until the required element is found, giving it a time complexity of **O(n)**. Binary Search repeatedly divides the sorted data into two parts and searches only the required portion, resulting in a time complexity of **O(log n)**. However, Binary Search can only be applied when the data is sorted.

## Conclusion

Both searching techniques successfully locate the required element in a dataset. Linear Search is simple and can be used with sorted or unsorted data, while Binary Search provides much faster searching for large sorted datasets. Therefore, Binary Search is preferred when the data is sorted and performance is important, whereas Linear Search is useful for smaller or unsorted collections.

 

# PRACTICAL-3

## Summary

In this practical, the **Max-Heap Sort** algorithm was implemented using the Max Heap data structure. The algorithm first converts the given elements into a Max Heap, where the largest element is placed at the root. The largest element is then moved to its correct position by swapping it with the last element, followed by readjusting the heap. This process continues until all elements are sorted in ascending order. Heap Sort provides **O(n log n)** time complexity.

## Conclusion

The Max-Heap Sort algorithm successfully sorts the given elements using the properties of a Max Heap. It provides consistent **O(n log n)** performance and does not require additional arrays for sorting. Therefore, Heap Sort is an efficient and reliable sorting technique, especially when consistent performance and memory usage are important.



  # PRACTICAL-4

## Summary

In this practical, the factorial of a number was calculated using two different approaches: **iteration and recursion**. The user provides a number as input, and both methods are used to find its factorial. The execution time of each approach is calculated using Python’s `time.perf_counter()` function. The iterative approach uses a loop to perform the calculation, whereas the recursive approach calls the same function repeatedly until the base condition is satisfied.

## Conclusion

Both approaches successfully produce the factorial of the given number. The time complexity of both iterative and recursive methods is **O(n)**. However, their space complexities are different. The iterative method requires **O(1)** extra space, while the recursive method requires **O(n)** space due to the recursive function calls stored in the call stack. Hence, iteration is more efficient in terms of memory, while recursion offers a straightforward and logical way to implement factorial calculation.


# PRACTICAL-5

## Summary

In this practical, the **0/1 Knapsack Problem** was implemented using the **Dynamic Programming** technique. The objective is to select items with given weights and values while ensuring that the total weight does not exceed the capacity of the knapsack. A Dynamic Programming table is used to store the solutions of smaller subproblems and reuse them to find the optimal solution. This approach avoids repeated calculations and efficiently determines the maximum possible value. The time complexity of the algorithm is **O(n × W)** and the space complexity is **O(n × W)**, where `n` is the number of items and `W` is the knapsack capacity.

## Conclusion

The Dynamic Programming approach successfully solves the 0/1 Knapsack Problem by finding the combination of items that gives the **maximum value within the given capacity**. Storing intermediate results reduces repeated computations and makes the algorithm more efficient than a simple recursive approach. Therefore, Dynamic Programming is an effective technique for solving optimization problems such as the Knapsack Problem.



# PRACTICAL-6

## Summary

In this practical, the **Matrix Chain Multiplication** problem was implemented using the **Dynamic Programming** technique. The objective is to determine the most efficient order for multiplying a sequence of matrices so that the total number of scalar multiplications is minimized. Since matrix multiplication is associative, the matrices can be grouped in different ways, but each order may require a different number of operations. Dynamic Programming stores the minimum multiplication cost for smaller matrix chains and uses these results to determine the optimal order for the complete chain. The time complexity of the algorithm is **O(n³)** and the space complexity is **O(n²)**.

## Conclusion

The Dynamic Programming approach successfully determines the **optimal order of matrix multiplication** while minimizing the total number of scalar operations. By storing the results of previously solved subproblems, unnecessary repeated calculations are avoided. Therefore, Matrix Chain Multiplication using Dynamic Programming provides an efficient solution for finding the minimum multiplication cost, especially when dealing with a large number of matrices.



# PRACTICAL-7

## Summary

This practical demonstrates the **Coin Change problem** using the Dynamic Programming approach. The objective is to determine the minimum number of coins needed to form a specified amount. Dynamic Programming maintains a table of previously computed values and reuses them whenever required. This prevents the same subproblems from being calculated multiple times. The algorithm requires **O(n × A)** time and **O(A)** additional space.

## Conclusion

The Dynamic Programming technique provides an effective way to solve the minimum coin change problem. By saving the results of smaller subproblems, it avoids unnecessary repeated calculations and improves the overall efficiency of the program. The method successfully determines the minimum number of coins required for the target amount and performs significantly better than a basic recursive solution for larger inputs.



# PRACTICAL-8

## Summary

This practical demonstrates the development of a **Mini AI Text Classification Application** using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to classify text into predefined categories based on its content. The application processes the input text, converts it into numerical features, and uses a trained machine learning model to predict the appropriate category. This practical helps understand the basic working of AI-based text classification systems and their applications in spam detection, sentiment analysis, and text categorization.

## Conclusion

The Mini AI Text Classification Application successfully demonstrates how Artificial Intelligence and Machine Learning can be used to automatically classify text data. By applying text preprocessing, feature extraction, and classification techniques, the application predicts the category of the given text. This approach reduces manual effort and improves the efficiency of text analysis. Therefore, text classification is an important NLP application used in email filtering, customer feedback analysis, sentiment detection, and other real-world applications.



# PRACTICAL-9

## Summary

This practical demonstrates **Prim's Algorithm** to find the Minimum Spanning Tree (MST) of a connected, weighted, undirected graph. The objective is to connect all vertices with the minimum possible total edge weight without forming any cycles. Prim's Algorithm starts from any vertex and repeatedly selects the minimum-weight edge that connects a visited vertex to an unvisited vertex. This process continues until all vertices are included in the spanning tree. The algorithm is useful in network design, road construction, and communication systems.

## Conclusion

Prim's Algorithm successfully determines the Minimum Spanning Tree by selecting the minimum-weight edges while avoiding cycles. It connects all vertices of a graph with the minimum total cost. The algorithm provides an efficient solution for problems involving network connectivity and resource optimization. Therefore, Prim's Algorithm is an important greedy technique used in designing cost-effective networks and solving graph optimization problems.



# PRACTICAL-10

## Summary

This practical demonstrates **Kruskal’s Algorithm** to find the Minimum Spanning Tree (MST) of a connected, weighted, undirected graph. The objective is to connect all vertices with the minimum possible total edge weight without forming any cycles. Kruskal’s Algorithm sorts all edges in increasing order of their weights and selects the smallest edge that does not create a cycle. This process continues until all vertices are connected. The algorithm uses the Greedy approach and is useful in network design, road construction, and communication systems. Its time complexity is O(E log E), where E represents the number of edges.

## Conclusion

Kruskal’s Algorithm successfully finds the Minimum Spanning Tree by selecting the minimum-weight edges while avoiding cycles. It connects all vertices with the minimum total cost and provides an efficient solution to graph optimization problems. The algorithm uses sorting and the Union-Find data structure to detect cycles efficiently. Therefore, Kruskal’s Algorithm is an important greedy technique for designing cost-effective networks and solving minimum spanning tree problems.



# PRACTICAL-11

## Summary

This practical demonstrates the implementation of the **Floyd–Warshall Algorithm** to find the shortest distances between all pairs of vertices in a weighted graph. The algorithm uses a dynamic programming approach to calculate the shortest paths by considering each vertex as an intermediate vertex. It updates the distance matrix whenever a shorter path is found through an intermediate vertex. The algorithm can handle positive edge weights and negative edge weights, provided there are no negative-weight cycles. Its time complexity is O(V³), and its space complexity is O(V²).

## Conclusion

The Floyd–Warshall Algorithm successfully calculates the shortest distances between every pair of vertices in a graph. By repeatedly updating the distance matrix, it determines the minimum distance between vertices through different intermediate paths. This algorithm is useful in network routing, transportation systems, and graph-based applications. Therefore, Floyd–Warshall is an important dynamic programming technique for solving all-pairs shortest-path problems.



