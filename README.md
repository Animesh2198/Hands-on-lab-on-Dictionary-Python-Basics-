# Hands-on-lab-on-Dictionary-Python-Basics-
In this repository we will understand about the Dictionary. 

**The Key is the first element  separated from its value by a colon**

To create a  Dictionary 

Dict = {"key1": 1, "key2": "2", "key3": [3, 3, 3], "key4": (4, 4, 4), ('key5'): 5, (0, 1): 6}
Dict
The output will be : 
{'key1': 1,
 'key2': '2',
 'key3': [3, 3, 3],
 'key4': (4, 4, 4),
 'key5': 5,
 (0, 1): 6}
 
 The keys can be strings. 
 
 To access the value of 1st key we will use
 Dict["key1"] 
 The value stored in key1 is 1 
 
 Keys can also be any immutable object such as a tuple:
 
 We can retrieve the keys of the dictionary using the method **keys()**:
 release_year_dict.keys() 
 
We can retrieve the values using the method **values()** : 
release_year_dict.values() 

To add a key or an entry into dictionary 
release_year_dict['Graduation'] = '2007'
release_year_dict

We can verify if an element is in the dictionary:
'The Bodyguard' in release_year_dict
