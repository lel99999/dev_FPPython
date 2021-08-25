# dev_FPPython
Functional Approach in Python

##### Python doesn't allow the creation of new operators, but but one can override existing operators
[http://blog.teamtreehouse.com/operator-overloading-python](http://blog.teamtreehouse.com/operator-overloading-python) <br/>

##### Use Infix module to emulate
Install infix: <br/>
```
$pip install infix
```

code:
```
from infix import mul_infix as Infix
Y = Infix(lambda x,y: x+y)
2 *X* 3
X(2,3)

# Used X as an Operator or Function
# When used as operator, need to surround X with multiplication operator, *

```
[https://pypi.org/project/infix/](https://pypi.org/project/infix/) <br/>

##### Using functools
[https://docs.python.org/3/library/functools.html](https://docs.python.org/3/library/functools.html) <br/>
```
# Get the product of list w/o using numpy
from functools import reduce
reduce(lambda x,y:x*y,a)
```
