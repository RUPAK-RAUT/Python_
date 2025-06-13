>>> pen = "Red Pen"
>>> first_char = pen[0]  
>>> print(first_char)
R   
>>> pen
'Red Pen'
>>> slice_pen = pen[0:4]
>>> print(slice_pen)    
Red 
>>> pen[0:4]
'Red '
>>> pen[-1]  
'n' 
>>> num_list = "0123456789"
>>> num_list[:]
'0123456789'
>>> num_list[0:5]
'01234'
>>> num_list[4:]  
'456789'
>>> num_list[:8] 
'01234567'
>>> num_list[0:7:2]
'0246'
>>> pen
'Red Pen'

>>> print(pen.lower())
red pen
>>> print(pen.upper()) 
RED PEN
>>> pen = "   Red Pen  "
>>> pen
'   Red Pen  '
>>> print(pen.strip())
Red Pen
>>> pen = "Red pen"
>>> print(pen.replace("Red","Black"))
Black pen
>>> pen
'Red pen'
>>> pen = "Red , Balck , Green , Blue"
>>> print(pen.split())
['Red', ',', 'Balck', ',', 'Green', ',', 'Blue']
>>> print(pen.split(", "))
['Red ', 'Balck ', 'Green ', 'Blue']
>>> pen = "Red pen"

>>> print(pen.find("pen"))
4
>>> pen = "Red pen pen pen"
>>> print(pen.count("pen")) 
3
>>> pen_type = "Red "
>>> quantity = 4
>>> order = "I need {} packets of {} pen"  
>>> order
'I need {} packets of {} pen'
>>> print(order.format(quantity , pen_type))
I need 4 packets of Red  pen
>>> pen_variety = ["Red", "Black", "Blue", "Yellow"]
>>> pen_variety                                     
['Red', 'Black', 'Blue', 'Yellow']
>>> print("".join(pen_variety))
RedBlackBlueYellow
>>> print("  ".join(pen_variety))
Red  Black  Blue  Yellow
>>> print(" -- ".join(pen_variety)) 
Red -- Black -- Blue -- Yellow
>>> print(" ,  ".join(pen_variety)) 
Red ,  Black ,  Blue ,  Yellow
>>> pen
'Red pen pen pen'
>>> pen = "Red pen"
>>> pen
'Red pen'
>>> print(len(pen)) 
7
>>> pen
'Red pen'
>>> for letter in pen:
... print(letter) 
  File "<stdin>", line 2
    print(letter) 
    ^
IndentationError: expected an indented block after 'for' statement on line 1
<!--                  -->
>>> for letter in pen:
...     print(letter)
... 
R
e
d

p
e
n

>>> pen = "He said, \"Red pen is smooth\" " 
>>> pen
'He said, "Red pen is smooth" '
>>> pen = "Red \nPen"
>>> pen
'Red \nPen'
>>> print(pen)
Red 
Pen
>>> pen = r"Red\nPen" 
>>> print(pen)        
Red\nPen
>>> pen = r"c:\\user\\pwd\\"
>>> print(pen)       
c:\\user\\pwd\\
>>> pen = r"c:\user\pwd"                     
>>> print(pen)
c:\user\pwd
>>> pen = "c:\\user\\pwd"    
>>> pen
'c:\\user\\pwd'
>>> print(pen)
c:\user\pwd
>>> pen = "Red pen"
>>> print("Red" in pen)  
True
>>> print("Reed" in pen)
False
>>>