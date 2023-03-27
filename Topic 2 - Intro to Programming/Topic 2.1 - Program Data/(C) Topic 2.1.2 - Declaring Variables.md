
In programming, constants and variables are used to store data which may be accessed later in the program. 
- Variables
    - Values which can be changed in a program's runtime. Variables are used to store values which may vary or change later in the program (i.e. highest score, age). 
        - To declare a variable in Python, we use the following syntax: variable_name = value. For example:
            -  high_score = 492, age = "Sandra" (see 2.1.2 data types)
- Constants
    - Values which cannot be changed in the program's runtime. Constants are used to store fixed values, such as mathematical constants (Pi, Speed of Light, Avogadro's Constant)
        - In Python, there is no specific way to set constants (they are set in the same way as a variable), so we use UPPERCASE to indicate that something is a constant. 
            - NUM_OF_CARDS = 52
- Type Casting
    - In Python, you do not need to declare data types as Python will assume the data type based off what is stored in the variable. For example, Python will know "Sandra" is a string and that 492 is an integer. However, as different data types are processed differently, sometimes you may want to force a change of data type. This is known as Type Casting.
        - In Python, to change the data type of a variable, we use the following syntax: data_type(variable)
            - For example:
            - score = 500
            - str(score) will return "500" as it converts score to a string
