find the product of all value in a list

```
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]
result = 1
for number in numbers;
    result *= number
```

use  the function _reduce_ for a shorter _for_ loop

```
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]
result = reduce(lambda a,b: a*b, numbers)
```
