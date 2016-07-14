---
title       : Python lists
description : Insert the chapter description here

--- type:NormalExercise lang:python xp:100 skills:1 key:c925563fdd
## Lists

Create a list `new_list` in Python, containing the elements 1, 2 and the string "a"

*** =instructions
- A list in python is created using the `[]` operator. 
- The list can be initialized as an empty list, or can contain initial values by providing them in the initialization operator.

$$ A = 
\begin{matrix}
	a & b & c \\\
	d & e & f \\\
	g & h & i
\end{matrix}
$$

*** =hint
- Fill in the requested items in the `[]` operator.
- A list in Python can contain different types of elements.

*** =sample_code
```{python}
# Initialize the list
new_list = 
```

*** =solution
```{python}
# Initialize the list
new_list = [1, 2, "a"]
```

*** =sct
```{python}
test_object("new_list",
            undefined_msg = "Don't forget to initialize 'new_list'",
            incorrect_msg = "The list should contain the elements 1, 2 and the string 'a'")

success_msg("Well done!")
```

--- type:NormalExercise lang:python xp:100 skills:1 key:8e691ef3d1
## Lists2

Create a list `new_list` in Python, containing the elements 1, 2 and the string "a"

*** =instructions
- A list in python is created using the `[]` operator. 
- The list can be initialized as an empty list, or can contain initial values by providing them in the initialization operator.

*** =hint
- Fill in the requested items in the `[]` operator.
- A list in Python can contain different types of elements.

*** =sample_code
```{python}
# Initialize the list
new_list = 
```

*** =solution
```{python}
# Initialize the list
new_list = [1, 2, "a"]
```

*** =sct
```{python}
test_object("new_list",
            undefined_msg = "Don't forget to initialize "new_list"",
            incorrect_msg = "The list should contain the elements 1, 2 and the string 'a'")

success_msg("Well done!")
```
