# Tuples

A tuple is a ordered collection of items.
Tuples are immutable. Once declared the items cannot be changed, size cannot be changed.

```python
tuple_ = ('abc', 123, ['a', "String"])

print(tuple_)
print(tuple_[0:2])
print(tuple_[2][0])
tuple_[0] = 'xyz'
print(tuple_)
```

Output
```
('abc', 123, ['a', "String"])
('abc', 123)
a
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment
```
