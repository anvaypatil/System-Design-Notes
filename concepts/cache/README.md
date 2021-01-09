## Cache
 A software component that stores data so that future requests for that data can be served faster; the data stored in a cache might be the result of an earlier computation or a copy of data stored elsewhere.  A cache hit occurs when the requested data can be found in a cache, while a cache miss occurs when it cannot. 

## Type of cache polices
 Caching improves performance by keeping recent or often-used data items in memory locations that are faster or computationally cheaper to access than normal memory stores. When the cache is full, the algorithm must choose which items to discard to make room for the new ones.

1. #### First in first out (FIFO)
The cache evicts the blocks in the order they were added, without any regard to how often or how many times they were accessed before.

1. #### Last in first out (LIFO) or First in last out (FILO)
The cache evicts the block added most recently first without any regard to how often or how many times it was accessed before.

1. #### Least recently used (LRU)

1. #### Time aware least recently used (TLRU)

1. #### Most recently used (MRU)

1. #### Pseudo-LRU (PLRU)

1. #### Random replacement (RR)

1. #### Segmented LRU (SLRU)

1. #### Least-frequently used (LFU)

1. #### Least frequent recently used (LFRU)

1. #### LFU with dynamic aging (LFUDA)

1. #### Low inter-reference recency set (LIRS)

1. #### CLOCK-Pro

1. #### Adaptive replacement cache (ARC)

1. #### AdaptiveClimb (AC)

1. #### Clock with adaptive replacement (CAR)

1. #### Multi queue (MQ)

1. #### Pannier: Container-based caching algorithm for compound objects