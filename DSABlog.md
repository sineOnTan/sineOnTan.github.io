# __Data Structures__

Mainly c++ data structures

## 16/05/2025

[Vector with Map properties](https://github.com/sineOnTan/DSA_Blog/blob/main/dualMap.cpp)

Allows 
- log(N) access time for first, last, largest and smallest.
- log(N) front and end insertion
- log(N) Swapping indexes and/or numbers

Essentially a Jack of All Trades of a data structure. Could implement more functions however this is the basic implementation.

## 06/04/2025

__Vectors__

One of the most basic DS in c++ so brief blog.
Due to its simplicity, it may be faster then binary searches and maps for **small data**.

For larger data structures where deletion and searches are required, maps tend to be faster.

One consideration for the use of vectors is the possibility of the time complexity of a reallocation of memory.

Typically insertion is constant time and this leads to an ammortised constant time. However in the worst case **INSERTION IS O(N) if a reallocation of memory is required.** [Push_back ref.](https://en.cppreference.com/w/cpp/container/vector/push_back)

Leading to sudden lag spikes. Under most situations, vectors are mainly used for storing input and known data.

