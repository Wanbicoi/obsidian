| Metric                                | Red-Black Tree                         | AVL Tree                                   | Splay Tree                                          |
| ------------------------------------- | -------------------------------------- | ------------------------------------------ |:--------------------------------------------------- |
| **Insertion in worst case**           | O(logN)                                | O(logN)                                    | Amortized O(logN)                                   |
| **Maximum height of tree**            | 2\*log(n)                              | 1.44\*log(n)                               | O(n)                                                |
| **Search in worst case**              | O(logN),  Moderate                     | O(logN),  Faster                           | Amortized O(logN), Slower                           |
| **Efficient Implementation requires** | Three pointers with color bit per node | Two pointers with balance factor per  node | Only two pointers with no extra information         |
| **Deletion in worst case**            | O(logN)                                | O(logN)                                    | Amortized O(logN)                                   |
| **Mostly used**                       | As universal data structure            | When frequent lookups are required         | When same element is  retrieved again and again     |
| **Real world Application**            | Database Transactions                  | Multiset, Multimap, Map, Set, etc.         | Cache implementation, Garbage collection Algorithms |

Ref: [https://www.geeksforgeeks.org/self-balancing-binary-search-trees/](https://www.geeksforgeeks.org/self-balancing-binary-search-trees/)