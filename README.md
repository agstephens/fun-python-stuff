# fun-python-stuff

Some nice features of Python to know about

## Features

### Generator expressions (like List Comprehensions)

https://www.pythonlikeyoumeanit.com/Module2_EssentialsOfPython/Generators_and_Comprehensions.html

```
>>> gen = (x for x in [1, 2, 3, 4, 5] if x > 3)
>>> gen.next()
4
>>> for i in gen: i
...
5
```

### Asterisk (\*) operator at the start of sequence "[\*seq, other, another]"

https://treyhunner.com/2018/10/asterisks-in-python-what-they-are-and-how-to-use-them/

```
>>> numbers = [2, 1, 3, 4, 7]
>>> more_numbers = [*numbers, 11, 18]
>>> print(*more_numbers, sep=', ')
2, 1, 3, 4, 7, 11, 18

>>> fruits = ['lemon', 'pear', 'watermelon', 'tomato']
>>> print(fruits[0], fruits[1], fruits[2], fruits[3])
lemon pear watermelon tomato
>>> print(*fruits)
lemon pear watermelon tomato
```

