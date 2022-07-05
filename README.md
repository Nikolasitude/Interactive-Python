# Interactive-Python
Have you ever wanted to save what you coded in the interactive python interpreter into a file ?

```
import interactive

#if you want to save your inputs, give a file path
your_file_path = "log.py" 

interactive.interact(your_file_path)
```

The bold lines will be stored :

**>>> a = 2** #stored

**>>> b = 3** #stored

\>>> a ## not stored

2

\>>> a + b ## not stored

5

**>>> def x():** #stored

**...   output = a+b** #stored

**...   return output** #stored

\>>>

**>>> x()** #stored
