
# Function
The keyword [`def`](https://docs.python.org/3/reference/compound_stmts.html#def) introduces a function _definition_.
```python
def foo(a, b, c):
	"""
	My docstring
	"""
	
	return (a + b) / c
```
## Calling ```foo``` with positional arguments
```python
foo(1, 2, 3)  # a = 1, b = 2, c = 3
```
## Calling ```foo``` with keywords arguments
```python
foo(b=2, a=1, c=3)  # any order for keywords args
```
```python
foo(1, b=2, c=3)  # mixing positional and keywords args
```
## Default args
```python
def connect(host, port=1234):
	...
	
> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzOTc4NDA3OSwxMjA1MDI3NjE3LDQ1Nz
EwNjg1XX0=
-->