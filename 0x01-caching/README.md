# Caching
This project contains tasks for learning to cache data.

## Tasks To Complete
+ [x] 0. **Basic dictionary**<br/>[0-basic_cache.py](0-basic_cache.py) contains a Python class `BasicCache` that inherits from [BaseCaching](BaseCaching) and is a caching system:
  + You must use `self.cache_data` - dictionary from the parent class [BaseCaching](BaseCaching).
  + This caching system doesn't have limit.
  + `def put(self, key, item):`:
    + Must assign to the dictionary `self.cache_data` the `item` value for the key `key`.
    + If `key` or `item` is `None`, this method should not do anything.
  + `def get(self, key):`:
    + Must return the value in `self.cache_data` linked to `key`.
    + If `key` is `None` or if the `key` doesn't exist in `self.cache_data`, return `None`.

+ [x] 1. **FIFO caching**<br/>[1-fifo_cache.py](1-fifo_cache.py) contains a Python class `FIFOCache` that inherits from [BaseCaching](BaseCaching) and is a caching system:
