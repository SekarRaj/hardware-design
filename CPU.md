## Cache-Coherency
  When the same data is resident on multiple CPU core's cache and the data is modified in one of the cache it will cause coherency problem. The data is marked data across the caches to avoid this problem.

## Cache snooping protocols
 To prevent cache-coherency problem, **write invalidate protocol** removes copies of the data across all cores before writing to local cache. Read in the other cores trigger a cache miss and refreshed data will be populated to the core. Used in **UMA** systems.



https://frankdenneman.nl/2016/07/07/numa-deep-dive-part-1-uma-numa/



### Appendix
UMA - Unified Memory Access
SMP - Symmetric Multi-Processor (another name for UMA)
