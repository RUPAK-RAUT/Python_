>>> import sys
>>> sys.getrefcount (24601)
3
>>> sys.getrefcount (2601)
3
>>> sys.getrefcount ('Hari')
4294967295
>>> sys.getrefcount ('Hi')
4294967295
>>> sys.getrefcount ('H')
4294967295
>>> a = 3
>>> a = 'Hello Earth'
>>> a = 3.14
>>> a = 5
>>> b = 2
>>> a
5
>>> b
2
>>> a = a+2
>>> a
7
>>> myListOne = [1,2,3]
>>> myListTwo = myListOne
>>> myListOne = 'Ironman'
>>> myListTwo
[1, 2, 3]
>>> myListOne = [1,2,3]
>>> myListOne[0] = 55  
>>> myListOne          
[55, 2, 3]
>>> myListTwo
[1, 2, 3]
>>> l1 = [1,2,3]
>>> l2 = l1
>>> l1
[1, 2, 3]
>>> l2
[1, 2, 3]
>>> l1[0] = 77
>>> l1
[77, 2, 3]
>>> l2
[77, 2, 3]
>>> p1 = [1,2,3]
>>> p2 = p1
>>> p2 = [1,2,3]
>>> p1[0] = 99
>>> p1
[99, 2, 3]
>>> p2
[1, 2, 3]
>>> h1 = [1,2,3]
>>> h2 = h1[:]
>>> h1
[1, 2, 3]
>>> h2
[1, 2, 3]
>>> h1[0] = 55
>>> h1
[55, 2, 3]
>>> h2
[1, 2, 3]
>>> import copy
>>> h1[0] = 55
>>> h1
[55, 2, 3]
>>> h2
[1, 2, 3]
>>> import copy
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> m
[1, 2, 3]
>>> n
[1, 2, 3]
>>> m == n
True
>>> m is n
True
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> m
[1, 2, 3]
>>> n
[1, 2, 3]
>>> m == n
True
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> m
[1, 2, 3]
>>> n
[1, 2, 3]
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> m
[1, 2, 3]
>>> h2 = copy.deepcopy(h1)
>>> m = [1,2,3]
>>> n= [1,2,3]
>>> m = n
>>> m
>>> n= [1,2,3]
>>> m = n
>>> m
[1, 2, 3]
>>> m = n
>>> m
[1, 2, 3]
>>> m
[1, 2, 3]
[1, 2, 3]
>>> n
[1, 2, 3]
>>> m == n
True
>>> m is n
True
>>> m = [1,2,3]
>>> m = n
>>> m == n
True
>>> m is n
True
>>> m = [1,2,3]
>>> m == n
True
>>> m is n
False
>>>






