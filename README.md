# Online Bipartite Matching Instances

Denote a bipartite graph by G = (N,V,E) where E is the subset of edges in N × V and n = |N| = |V|. This project contains the instances used in [1]:

  1. **small.zip** contains 20 small instances with n = 10, each one randomly generated by having a possible edge in N × V be present independently with a probability of 25%. 

  2. **large_dense.zip** contains 20 large, dense instances with n = 100, each one randomly generated by having a possible edge in N × V be present independently with a probability of 10%.

  3. **large_sparse.zip** contains 20 large, sparse instances with n = 100, each one randomly generated by having a possible edge in N × V be present independently with probability of 2.5%.

  4. **regular.zip** contains a set of large, k-regular graphs with n = 100 and k ∈ {3, 4, 5, 6}, constructed in the following way: Indexing both impressions and ads from 0 to n − 1, each impression i is adjacent to ads {i,i+1,...,i+k−1} mod k.

Each instance corresponds to 0-1 matrix of size n^2 given in a CSV file.

[1] *Dynamic Relaxations for Online Bipartite Matching*. Alfredo Torrico and Alejandro Toriello, 2022.
