# lazyRecursion

Usage Example:

```python
from lazyRecursion import RecursiveSequence

fibonacci = RecursiveSequence(
    induction_start={0: 1, 1:1},
    relative_indices=[-2,-1],
    recursion_function=lambda x1,x2: x1+x2,
    cache_file='fib_cache.json'
)
print(fibonacci[:10])
```
