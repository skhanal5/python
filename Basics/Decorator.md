## About
* A function that returns another function
* Think function transformation 
	* Closures in functional programming
* Feel like Java Annotations (implementation is completely different though)
* Example:
```python
def f(arg):
    ...
f = staticmethod(f)

@staticmethod
def f(arg):
    ...
```