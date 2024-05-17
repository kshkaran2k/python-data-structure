# Dictionary

It is used to store the data in key, value pairs. 

eg: `my_dict = {"lang": "python", "ds":"dictionary"}`


## Properties

### Mutable
This means that it is changeable. Meaning we can add, remove and change items in the list after it has been created.

### Ordered  
This means that the data have defined order.  
eg: The result of `{"language":"python", "language":"c++"}` and `{"language":"c++", "language":"python"}` are different.

**NOTE**: As of Python version 3.7, dictionaries are ordered. In Python 3.6 and earlier, dictionaries are unordered.

### Duplicate Values
It doesn't support duplicate keys. But the values can be duplicate for different keys. It will overwrite the values for the same key.
eg: `{"language":"python", "language":"c++"}` will result in `{"language":"c++"}`

