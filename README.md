Q1. What is a tuple in Python?
- A tuple in Python is an ordered, immutable collection of elements enclosed in parentheses `()`. It is a built-in data type that can store multiple items in a single variable. Tuples are similar to lists, but they cannot be modified once created, making them immutable.

Q2. How do you create a tuple in Python?
- There are multiple ways to create a tuple in Python:
  1. Using parentheses `()`:
     ```python
     my_tuple = (1, 2, 3)
     ```

  2. Using the `tuple()` constructor:
     ```python
     my_tuple = tuple([1, 2, 3])
     ```

Q3. What is the difference between a tuple and a list in Python?
- The main differences between a tuple and a list in Python are:
  - Mutability: Tuples are immutable, meaning their elements cannot be modified once created. Lists, on the other hand, are mutable and can be modified.
  - Syntax: Tuples are enclosed in parentheses `()` while lists are enclosed in square brackets `[]`.
  - Performance: Tuples are generally faster to access than lists.
  - Use cases: Tuples are typically used to store related pieces of data together, whereas lists are used for collections of similar or related items that may need to be modified.

Q4. Can a tuple be changed in Python?
- No, a tuple cannot be changed (immutable) once it is created. This means you cannot add, remove, or modify elements of a tuple. However, you can perform operations that do not modify the tuple, such as accessing elements or creating a new tuple based on existing tuples.

Q5. How do you access elements in a tuple?
- Elements in a tuple can be accessed using indexing. Indexing starts from 0, so the first element has an index of 0, the second element has an index of 1, and so on. You can use square brackets `[]` with the index value to access the corresponding element.
  ```python
  my_tuple = (1, 2, 3)
  print(my_tuple[0])  # Output: 1
  ```

Q6. How do you unpack a tuple in Python?
- Unpacking a tuple in Python allows you to assign the elements of a tuple to individual variables. This is done by providing the same number of variables on the left side of the assignment operator as there are elements in the tuple.
  ```python
  my_tuple = (1, 2, 3)
  a, b, c = my_tuple
  print(a, b, c)  # Output: 1 2 3
  ```
  In this example, the values of `a`, `b`, and `c` are assigned the respective values from the tuple. Unpacking can be used to conveniently assign multiple variables at once.
