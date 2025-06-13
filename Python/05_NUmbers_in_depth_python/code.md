>>> x= 3
>>> y=6
>>> z =8
>>> x+y
9   
>>> 40 + 2.32
42.32
>>> int(3.167)
3   
>>> float(300)
300.0
>>> 'Hello' + 'Earth' 
'HelloEarth'
>>> x, y,z  
(3, 6, 8)
>>> x+1 , y*3
(4, 18)
>>> y % 2
0   
>>> z ** 2
64  
>>> z ** 5
32768
>>> 100 ** 2
10000
>>> 2 * 10
20  
>>> 2 * 100
200 
>>> 2** 10
1024
>>> 2** 100
1267650600228229401496703205376
>>> 2** 1000
10715086071862673209484250490600018105614048117055336074437503883703510511249361224931983788156958581275946729175531468251871452856923140435984577574698574803934567774824230985421074605062371141877954182153046474983581941267398767559165543946077062914571196477686542167660429831652624386837205668069376
>>> result = 1 / 3.0
>>> result
0.3333333333333333
>>> repr ('Groot')
"'Groot'"
>>> str ('Groot')
'Groot'
>>> print  ('Groot') 
Groot
>>> 1 < 2
True
>>> 5.0 ++ 5.0
10.0
>>> 5.0 == 5.0 
True
>>> 4.0 != 5.0
True
>>> x,y,z
(3, 6, 8)
>>> x<y<z
True
>>> x<y and y<z
True
>>> 1 == 2<3
False
>>> 1== 2 and 2<3
False
>>> import math
>>> math.floor (3.4) 
3
>>> math.floor (-3.4)
-4
>>> math.floor (3.9)  
3
>>> math.trunc(2.8) 
2
>>> math.trunc(-2.8) 
-2
>>> 99999999999 + 1
100000000000
>>> 99999999999 + 2.1
100000000001.1
>>> 99999999999 *2.1  
209999999997.9
>>> 999999999999999999999999999 * 2.1
2.1000000000000002e+27
>>> 2* 100
200
>>> 2** 100
1267650600228229401496703205376
>>> 2 +1j
(2+1j)
>>> (2+3j) *2
(4+6j)
>>> 0o20
16
>>> 0xff
255
>>> 0b1000
8
>>> oct(64)
'0o100'
>>> hex(64)
'0x40'
>>> bin(64)
'0b1000000'
>>> int(3.14)
3
>>> int ('64' , 8)
52
>>> int ('64' , 16) 
100
>>> x=1
>>> x<<2
4
>>> import random
>>> random.random()
0.25635346188146557
>>> random.random()
0.9197426977828983
>>> random.randint(1,100)   
99
>>> random.randint(1,100)
73

>>> l1 = ['Red' , 'Blue' , 'Green', 'Yellow']
>>> random.choice(l1) 
'Blue'
>>> random.choice(l1)
'Yellow'
>>> random.choice(l1)
'Red'
>>> random.shuffle(l1)
>>> l1
['Blue', 'Yellow', 'Green', 'Red']
>>> random.shuffle(l1)
>>> l1
['Blue', 'Green', 'Yellow', 'Red']
>>> 0.1 + 0.1+ 0.4
0.6000000000000001
>>> 0.1 + 0.1+ 0.1 - 0.3
5.551115123125783e-17
>>> (0.1 + 0.1+ 0.1) - 0.3 
5.551115123125783e-17
>>> from decimal import Decimal 
>>> Decimal ('0.1') + Decimal('0.1') + Decimal ('0.1')
Decimal('0.3')
>>> Decimal ('0.1') + Decimal('0.1') + Decimal ('0.1')- Decimal('0.3') 
Decimal('0.0')
>>> from fractions import Fraction
>>> myFra = Fraction (2,7)
>>> myFra                 
Fraction(2, 7)
>>> setone = {1,2,3,4}
>>> setone & {1,3}    
{1, 3}
>>> setone | {1,3} 
{1, 2, 3, 4}
>>> setone | {1,3,9} 
{1, 2, 3, 4, 9}
>>> setone             
{1, 2, 3, 4}
>>> setone - {1,2,3,4}   
set()
>>> type({})
<class 'dict'>
>>> type (True)
<class 'bool'>
>>> True == 1
True
>>> False == 0 
True
>>> True is 1
<stdin>:1: SyntaxWarning: "is" with 'int' literal. Did you mean "=="?
False
>>> True 
True
>>> True  + 4
5
>>>