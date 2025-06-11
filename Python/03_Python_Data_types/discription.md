<!-- Simple math -->
>>> 10+12
22  
>>> 10*2
20  
>>> 2**100
1267650600228229401496703205376
>>> 2.5* 5
12.5
>>> import math
>>> math.pi
3.141592653589793

<!-- Generate random number/choices -->

>>> import random    
>>> random.random()
0.5047631666899699
>>> random.choice([1,2,3,4,5])
1   
>>> 
>>> random.choice([1,2,3,4,5])
5   

>>> username = "HelloEarth"
"nameError means it does not contain that type of name."

>>> len(Groot)
Traceback (most recent call last):    
  File "<stdin>", line 1, in <module> 
NameError: name 'Groot' is not defined

<!-- Shows the length  -->

>>> len (username)
10
<!-- array -->
>>> username [2]   
'l'

<!-- TypeError means it cannot be changed hence string are called immutable -->
>>> username [1] = 'E'
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> username [-1]      
'h'
>>> username [-2] 
't'

<!-- only takes the 1st ,2nd & 3rd not take 4th -->
>>> username [1:4]    
'ell'

<!-- error because i have given '=' -->
>>> mylist [123 , "Boom" , 3.14]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'mylist' is not defined. Did you mean: 'list'?

<!-- array list -->

>>> mylist = [123 , "Boom" , 3.14]
>>> mylist 
[123, 'Boom', 3.14]
>>> len(mylist)
3
>>> mylist [0]
123
>>> mylist [-1]
3.14

<!-- D means Dictionary . it starts and end with curly brackets {....} -->

>>> myD = {'one' : 'Earth' , 'two' : 'people' , 'Hero' : 'Avenger'}
>>> myD
{'one': 'Earth', 'two': 'people', 'Hero': 'Avenger'}

>>> myD['Hero']
'Avenger'

<!-- keyError means it does not contain that type of file . Here ,we have Hero file but i have put their name Heros which cause KeyError -->

>>> myD['Heros']
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'Heros'

<!-- Tup means Tuple and it stars and ends with parenthesis (...) -->
>>> myTup = (1,2,3,4)
>>> myTup[0]
1
>>> len(myTup)
4
>>>                   
