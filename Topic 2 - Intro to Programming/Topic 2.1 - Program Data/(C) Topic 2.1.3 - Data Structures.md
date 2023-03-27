
In programming, data structures refer to formats used to efficiently store and access multiple elements of data. Common structures include:
- Dictionaries
    - A collection of multiple elements, which are stored in a key:value pair. Dictionaries may be ordered (as of Python 3.7 dictionaries are ordered, in lower versions they are not) and modified, but they do not allow for duplicates. 
        - my_dict = {

            "brand":"Toyota",

            "model":"Prius"

            }
- Arrays
    - A collection of multiple elements, which can only contain the same data type. Arrays are ordered, modifiable, can have duplicates, and can handle arithmetic operations directly. This means that arithmetic operations can be applied to the array without having to loop through the array manually. 
        - import array
        - my_array = array.array(1,2,3,4,5)
- Lists
    - A collection of multiple elements, which may contain different data types. Lists are ordered, modifiable, and can have duplicates.
        - my_list = ["a", 1, [4, 5]]

Data structures are essential in programming as they allow help to organise, store, and access data more efficiently. Without these structures, it would be more difficult to manage and operate on large amounts of data.  