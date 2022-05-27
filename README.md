import numpy as np
from numpy.random import randn
answer = None
x = randn()
if x>1:
    answer = "X greater then 1"
else:
    if x>=-1:
        answer = "Between -1 and 1"           # Nested statement
    else:
        answer = "Less then -1"
print(x)
print(answer)
