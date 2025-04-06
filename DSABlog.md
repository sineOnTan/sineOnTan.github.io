# __Data Structures__

Mainly c++ data structures

## 06/04/2025

__Vectors__

One of the most basic DS in c++ so brief blog.
Due to its simplicity, it may be faster then binary searches and maps for **small data**.
For larger data structures where deletion and searches are required, maps tend to be faster.
One consideration for the use of vectors is the possibility of the time complexity of a reallocation of memory.
Typically insertion is constant time and this leads to an ammortised constant time. However in the worst case **INSERTION IS O(N) if a reallocation of memory is required.** [Push_back ref.](https://en.cppreference.com/w/cpp/container/vector/push_back)
Leading to sudden lag spikes. Under most situations, vectors are mainly used for storing input and known data.

