# dev_FPPython
Functional Approach in Python

##### PEP 3107 -- Function Annotations
This PEP introduces a syntax for adding arbitrary metadata annotations to Python functions. <br/>
[https://www.python.org/dev/peps/pep-3107/#lambda](https://www.python.org/dev/peps/pep-3107/#lambda) <br/>

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

prod = lambda z: reduce(lambda x, y: x * y, z)
```
