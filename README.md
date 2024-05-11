# Interactive-Python

This module gives you an interpreter that saves your code in a file. 

```py
import console_save

# if you want to save your inputs, give a file path
your_file_path = "log.py" 

console_save.interact(your_file_path)
```

Or from command line

```cmd
python -m console_save "file_to_save.py"
```

Showcase (what is saved and what isn't saved in the given file) :

```py
->> a = 2 # variables are saved
->> b = 3 # saved
->> c = foo() # saved

->> a ## statements are not saved
2
->> a + b ## not saved 
5
->> a==2 ## not saved
True

*->> def x(): # functions are saved
\..   output = a+b # saved
\..   return(output) # saved
\... # this empty new line is not saved 

->> # any new line are saved

->> x() # function calls are not saved
5
->> -x() # but you can save function calls by adding a "-" in front
5
```

## Download 

With pip 

```cmd
pip install git+https://github.com/Nikolasitude/Interactive-Python.git
```
With github

```md
Download the console_save folder in the src/ directory
Or you can directly use interact.py that contains the interact() function 
```
