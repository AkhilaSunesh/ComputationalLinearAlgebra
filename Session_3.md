#### Pseudocode: Solution of system of equations
```
FUNCTION Solution (A,b):
  Create Augmented matrix : k=[A|b]
  Reduce in Row Reduced Echleon form
  Rank = no. of non zero rows RREF
  IF Rank(k)= Rank (A):
  print (System is inconsistent)
  ELSE IF:
  Solve using back substitution
END FUNCTION
```
# Python Fundamentals
## Python Programming Overview
- Variables
- Python Programming style
## String (ordered, immutable, hetergeneous)
`upper()`: Converts all characters to uppercase. <br>
`lower()`: Converts all characters to lowercase. <br>
`strip()`: Removes leading and trailing whitespace. <br>
`replace(old, new)`: Replaces occurrences of a substring with another substring. <br>
`split(separator)`: Splits the string into a list based on a separator.<br>
##  List Type (ordered, mutable, dynamic, heterogeneous)
`append(item)`: Adds an item to the end of the list. <br>
`insert(index, item)`: Inserts an item at a specified index. <br>
`remove(item)`: Removes the first occurrence of an item. <br>
`pop(index)`: Removes and returns the item at the specified index. <br>
`sort()`: Sorts the list in ascending order. <br>
`reverse()`: Reverses the order of the list. <br>
## Tuple Type (ordered, immutable, fixed size, heterogeneous)
`count(item)`: Returns the number of occurrences of the specified item. <br>
`index(item)`: Returns the index of the first occurrence of the specified item. <br>
## Mapping Types
### Dictionary (unordered, mutable, keys, values)
`keys()`: Returns a view object of all keys. <br>
`values()`: Returns a view object of all values. <br>
`items()`: Returns a view object of all key-value pairs. <br>
`get(key, default)`: Returns the value for the specified key, or a default value if the key is not found. <br>
`pop(key, default)`: Removes and returns the value for the specified key, or a default value if the key is not found. <br>
### Set (Unordered, mutable, unique, unindexed)
`add(item)`: Adds an item to the set. <br>
`remove(item)`: Removes an item from the set; raises KeyError if item is not present. <br>
`discard(item)`: Removes an item from the set if present; does not raise an error if item is not found. <br>
`pop()`: Removes and returns an arbitrary item from the set. <br>
`clear()`: Removes all items from the set. <br>
###  Frozen Sets (Unordered, immutable, unique, unindexed)
- Creating Frozen Sets:  `frozenset()`
- ```python
  # Creating a frozen set
numbers = frozenset([1, 2, 3, 4, 5])
fruits = frozenset({"apple", "banana", "cherry"})```

`copy()` : Returns a shallow copy of the frozen set. <br>
`difference(other)` : Returns a new frozen set with elements in the original frozen set but not in other. <br>
`intersection(other)` : Returns a new frozen set with elements common to both frozen sets. <br>
`union(other)` : Returns a new frozen set with elements from both frozen sets. <br>
`symmetric_difference(other)` : Returns a new frozen set with elements in either frozen set but not in both. <br>
## Control Structures
- conditional
- looping
- control flow
## Functions





