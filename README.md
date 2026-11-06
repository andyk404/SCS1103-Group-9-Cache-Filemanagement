Title: Which Blocks Deserve the Cache? FIFO vs LRU on a Storage Request Trace.

Question: Does least recently used (LRU) replacement give a higher block-cache hit rate than first in first out (FIFO) on a public Meta storage trace, at the same cache size?

Aim: To compare FIFO and LRU block-cache replacement on a public Meta storage request trace, and find out which gives more cache hits.
Objectives
1. Build a simple block-cache simulator in Python that applies FIFO and LRU replacement to a list of block requests.
2. Run both policies on a sample of the 2023 Meta storage trace, at five cache sizes (1%, 2%, 5%, 10% and 20% of the unique blocks in the sample).
3. Evaluate by measuring hit rate and number of misses at each size, with FIFO as the baseline. LRU succeeds if its hit rate is at least 5 percentage points above FIFO at 3 or more of the 5 sizes. We first check the simulator against a hand-worked 10-request example.


| Member Name | Registration Number |
| :--- | :--- |
| Malcolm Mahlengezana. | N02643222D |
| Devonna Nyemba. | N02643851V |
| Andy Mbodza. | N02646755H |
|Eliwedd Jnr Muzavazi. | N02652495B|
