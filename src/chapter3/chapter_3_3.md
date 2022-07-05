# Lists

A list is a ordered collection of items. 
Items can be of any datatype including List
Lists are mutable. Once declared the items can be changed, size can be changed.

```python
list_ = ['abc', 123, ['a', "String"]]

print(list_)
print(list_[0:2])
print(list_[2][0])
list_[0] = 'xyz'
print(list_)
```

Output
```
['abc', 123, ['a', "String"]]
['abc', 123]
a
['xyz', 123, ['a', "String"]]
``` 
