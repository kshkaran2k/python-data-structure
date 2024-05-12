# List

In simple words, it is a collection of things. 

eg: `my_list = [1, 'apple', 23]`


## Properties

### Mutable
This means that it is changeable. Meaning we can add, remove and change items in the list after it has been created.

### Ordered  
This means that the items have defined order.  
It's items indexed and the index starts from zero(0).
The first element of the list `my_list` can be accessible by `my_list[0]`, the second element with `my_list[1]` and so on.

### Duplicate Values
The elements present in the list can be duplicate.
eg: `my_list01 = [1,2,3,4,1,2]`


## Operations on Lists

To undertand the various operation on the lists, we are considering 2 lists, `list01 = [4,1,4,2,3]` and `list02 = [7,5]` for the demonstration

| Method Name  	| Eg  	| Result  	| Description  	|   	|
|---	|---	|---	|---	|---	|
| append  	| list01.append(5)  	|  [4,1,4,2,3,5] 	| Adds elements to the existing list at the end 	|   	|
| clear  	| list01.clear()  	| []  	| Removes all the elements from the list  	|   	|
| copy  	| li01 = list01.copy()  	| l101 will have [4,1,4,2,3]  	| Creates a copy of the list  	|   	|
| count  	| list01.count(4)  	| 2  	| Returns the number of times '4' appears in the list  	|   	|
| extend  	| list01.extend(list02)  	| [4,1,4,2,3,7,5]  	| Add the elements of iterables to end of the list  	|   	|
| index  	| list01.index(4)  	| 0  	| Retuns the first position of the element '4' form the list  	|   	|
| insert  	| list01.insert(2,5)  	| [4,1,5,4,2,3]  	| Insert the value(5) at the position '2'  	|   	|
| pop  	| list01.pop(3)  	| 2  	| Removes the element on the position '3' and returns it  	|   	|
| remove  	| list01.remove(4)  	| [1,4,2,3]  	| Removes the first element at the specified value(4)  	|   	|
| reverse  	| list01.reverse()  	| [3,2,4,1,4]  	| Reverse the order of the list  	|   	|
| sort  	| list01.sort()  	| [1,2,3,4,4]  	| Sort the list   	|   	|
|   	|   	|   	|   	|   	|


### Difference between `append` and `extend`
- append (mostly used with the single value)  
`list01.append(list02)` will result `[1,2,3,4,2,[4,5]]`  
- extend (works only with the iterators)  
`list01.extend(list02)` will result `[1,2,3,4,2,4,5]`

