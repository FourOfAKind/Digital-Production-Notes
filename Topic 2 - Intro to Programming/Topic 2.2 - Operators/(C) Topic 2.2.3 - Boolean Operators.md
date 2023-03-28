
In programming, Boolean Operators are used to combine or modify conditions and expressions. There are three basic boolean operators:
- NOT
    - NOT reverses the logical states of the current expression. If a condition is True, NOT makes it False and vice versa.
        - not(3 < 5) is False as 3 is smaller than 5, but not inverts this from True to False. 
        - not(3 > 5) is True as 3 is not bigger than 5, but not inverts this from False to True
- AND 
    - AND combines multiple conditions. If all conditions are True, AND returns True. Otherwise, AND returns False.
        - (3 > 2) and (4 > 3) is True as all conditions are True. 
        - (3 > 2) and (3 > 4) is False as only one condition is True.
        - (3 > 4) and (2 > 4) is False as no conditions are True.  
- OR
    - OR combines multiple conditions. If any conditions are True, OR returns True. Otherwise, OR returns False.
        - (3 > 2) or (4 > 3) returns True as all conditions are True. 
        - (3 > 2) or (3 > 4) will return True as at least one condition is True. 
        - (3 > 3) or (3 > 4) will return False as all conditions are False. 
        