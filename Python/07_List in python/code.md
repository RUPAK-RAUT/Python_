>>> language_varities = ["C" , "C++" , "JAVA" , "Python"]
>>> language_varities                                    
['C', 'C++', 'JAVA', 'Python']
>>> print(language_varities) 
['C', 'C++', 'JAVA', 'Python']
>>> language_varities[0]     
'C'
>>> language_varities[3] 
'Python'
>>> print(language_varities[0]) 
C
>>> print(language_varities[-1])
Python
>>> print(language_varities[1:3])
['C++', 'JAVA']
>>> print(language_varities[:2])
['C', 'C++']
>>> print(language_varities[2:]) 
['JAVA', 'Python']
>>> language_varities[3]          
'Python'
>>> language_varities[3] = "C#"
>>> language_varities          
['C', 'C++', 'JAVA', 'C#']
>>> language_varities[1:2]     
['C++']
>>> language_varities[1:2] = ["net core"]
>>> language_varities                    
['C', 'net core', 'JAVA', 'C#']
>>> language_varities[1:3]               
['net core', 'JAVA']
>>> language_varities[1:3] =["Html","Javascript"]
>>> language_varities       
['C', 'Html', 'Javascript', 'C#']
>>> language_varities[1:1]
[]  
>>> language_varities[1:1]= ["test","test"]
>>> language_varities      
['C', 'test', 'test', 'Html', 'Javascript', 'C#']
>>> language_varities[1:2]               
['test']
>>> language_varities[1:3]                       
['test', 'test']
>>> language_varities[1:3] =[]
>>> language_varities         
['C', 'Html', 'Javascript', 'C#']
>>> language_varities
['C', 'Html', 'Javascript', 'C#']
>>> for language in language_varities:
...     print(language)
... 
C
Html
Javascript
C#
>>> for language in language_varities:
...     print(language, end= "-") 
... 
C-Html-Javascript-C#->>> 
>>> language_varities
['C', 'Html', 'Javascript', 'C#']
>>> if "CSS" in langauge_varities:
...     print("I have to learn CSS") 
... 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'langauge_varities' is not defined. Did you mean: 'language_varities'?
>>> if "CSS" in language_varities:   
...     print("I have to learn CSS")
... 
>>> if "Html" in langauge_varities:  
...     print("I have to learn Html") 
... 
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'langauge_varities' is not defined. Did you mean: 'language_varities'?
>>> if "Html" in language_varities:   
...     print("I have to learn Html")
... 
I have to learn Html
>>> language_varities.append("JavaScript") 
>>> language_varities                      
['C', 'Html', 'Javascript', 'C#', 'JavaScript']
>>> if "JavaScript" in language_varities:
...     print("I have to learn JavaScript too.") 
... 
I have to learn JavaScript too.
>>> language_varities                            
['C', 'Html', 'Javascript', 'C#', 'JavaScript']
>>> language_varities.pop()               
'JavaScript'
>>> language_varities       
['C', 'Html', 'Javascript', 'C#']
>>> language_varities.remove("C")
>>> language_varities
['Html', 'Javascript', 'C#']
>>> language_varities.insert(1,"Numpy")  
>>> language_varities
['Html', 'Numpy', 'Javascript', 'C#']
>>> language_varities_copy = language_varities.copy()
>>> language_varities_copy
['Html', 'Numpy', 'Javascript', 'C#']
>>> language_varities_copy.append("Python")
>>> language_varities_copy
['Html', 'Numpy', 'Javascript', 'C#', 'Python']
>>> range(10)                              
range(0, 10)
>>> print(range(10))
range(0, 10)
>>> y = range(10)
>>> y
range(0, 10)
>>> squared_num =[x**2 for x in range(10)]
>>> squared_num                           
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
>>> cube_num = [y**3 for y in range (5)]
>>> cube_num                            
[0, 1, 8, 27, 64]
>>>