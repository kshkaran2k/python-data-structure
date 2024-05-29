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

## Operations on Dictionaries

To undertand the various operation on the dictionary, we are considering the following variables, `dict01 = {"name":"kaushik", "skills":['python','sql']}`, `a = ('key01', 'key02')` and `b = 0` for the demonstration


| Method Name  	| Eg  	| Result  	| Description  	|
|---	|---	|---	|---	|
| clear  	| dict01.clear()  	|  {} 	| Clear the dictionary 	|
| copy  	| d01 = dict01.copy()  	| {"name":"kaushik", "skills":['python','sql']}  	| Create a copy of the dictionary  	|
| fromkeys  	| newdict = dict.fromkeys(a, b)  	| {'key01': 0, 'key02': 0}  	| Returns a dictionary with a specified keys and value  	|
| get  	| dict01.get('name')  	| kaushik  	| Returns the value of the item with the specified key  	|
| items  	| dict01.items()  	| dict_items([('name', 'kaushik'), ('skills', ['python', 'sql'])])  	| Returns a list of tuple for each key value pair  	|
| keys  	| dict01.keys()  	| dict_keys(['name', 'skills'])  	| Retuns a list containing the keys of the dictionary  	|
| pop  	| dict01.pop('skills')  	| ['python','sql']  	| Removes the element with the specified keys  	|
| popitem  	| dict01.popitem()  	| ('name', 'kaushik')  	| Removes the last inserted key-value pair  	|
| setdefault  	| dict01.setdefault('skills', 'js')  	| ['python', 'sql']  	| Returns the value of the specified key otherwise insert the key with specified value  	|
| update  	| dict01.update({'year':2024})  	| {'name': 'kaushik', 'skills': ['python', 'sql'], 'year': 2024}  	| Update the dictionary with the specified key-value pair  	|
| values  	| dict01.values()  	| dict_values(['kaushik', ['python', 'sql']])  	| Returns a list of all the values of the dictionary   	|
|   	|   	|   	|   	|
