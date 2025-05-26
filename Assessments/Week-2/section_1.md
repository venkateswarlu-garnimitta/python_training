# Week 2 Assessment

## Section 1: Multiple Choice Questions


1. **What is the output of `list(map(lambda x: x*2, [1,2,3]))`?**

   A. [2,4,6]  ✔️

   B. [1,2,3]

   C. [1,4,9]

   D. Error

2. **Which keyword is used to create a generator function?**

   A. gen

   B. yield  ✔️

   C. return

   D. def

3. **What will be the output of: `def func(x=1): return x + 1; print(func())`?** 

   A. 1

   B. 2  ✔️

   C. None

   D. Error

4. **Which function is used to reduce a list to a single value?**

   A. filter()

   B. map()

   C. reduce()  ✔️

   D. zip()

5. **Which is NOT a Python built-in data type?**

   A. list

   B. tuple

   C. array  ✔️

   D. set

6. **What is the result of `filter(lambda x: x%2==0, [1,2,3,4])`?**

   A. [1,3]

   B. [2,4]  ✔️

   C. [1,2,3,4]

   D. [2]

7. **What will be printed: `a = [1,2,3]; b = iter(a); print(next(b))`?** 

   A. 1  ✔️

   B. 2

   C. 3

   D. Error

8. **Which function combines two lists into tuples?**

   A. map()

   B. zip() ✔️

   C. filter()

   D. enumerate()

9. **What is the result of `sum(map(len, ['ab', 'cde']))`?**

   A. 3

   B. 5  ✔️

   C. 6

   D. Error

10. **Which of the following is a decorator syntax in Python?**

    A. #decorator

    B. @decorator  ✔️

    C. *decorator

    D. &decorator

11. **What happens if a function decorated by a decorator does not return a value?**

    A. Returns None ✔️

    B. Raises an error

    C. The original function runs

    D. Skips execution

12. **What is the output of `(lambda x: x**2)(3)`?**

    A. 6

    B. 9 ✔️

    C. 3

    D. Error

13. **What is the output of `list(enumerate(['a','b']))`?**

     A. [(0, 'a'), (1, 'b')]  ✔️

     B. [('a',0), ('b',1)]

     C. ['a', 'b']

     D. Error

14. **Which of these statements is True about recursion?**

    A. Recursion always terminates 

    B. Recursion can replace loops  ✔️

    C. Recursion cannot be used in Python

    D. Recursion requires no base case

15. **Which of these returns an iterator object?**

    A. list()

    B. iter() ✔️

    C. tuple()

    D. dict()

16. **What will be the output of this code:**

```bash

def foo():
    yield 1
    return 2
x = list(foo())
print(x)

```

    A. [1,2]

    B. [1]  ✔️

    C. [2]

    D. Error

17. **Which of the following is NOT True for lambda functions?**

    A. They can have multiple expressions ✔️

    B. They can be assigned to a variable

    C. They return a function object

    D. They can be used as arguments

18. **What is the output of this code:

```bash
a = [1,2,3]
b = map(lambda x: x+1, a)
print(list(b))
print(list(b))

```
    A. [2,3,4] [2,3,4]

    B. [2,3,4] []  ✔️

    C. [] []

    D. Error

19. **Which of these is a side effect of using recursion?**

    A. Increased performance

    B. Reduced stack depth

    C. Stack overflow risk  ✔️

    D. Memory leak

20. **Which of the following about decorators is correct?**

    A. Decorators must always return the original function

    B. Decorators cannot modify arguments

    C. Decorators are applied at runtime

    D. Decorators are applied at function definition  ✔️


## Section 2: Coding Questions

1.  Write a function that uses a lambda to double a number.
```
Example 1:
Input: 5
Output: 10

Example 2:
Input: 12
Output: 24

Example 3:
Input: -7
Output: -14
```


2. Write a function that takes a list and returns a new list with only even numbers using filter.
```
Example 1:
Input: [1, 2, 3, 4, 5, 6]
Output: [2, 4, 6]

Example 2:
Input: [11, 13, 15, 18, 20]
Output: [18, 20]

Example 3:
Input: [7, 9, 21]
Output: []
```

3.  Write a decorator that times the execution of a function and prints the time taken.
```
Example 1:
A function that adds numbers from 1 to 1,000,000
Output: Time taken: ~0.05 seconds

Example 2:
A function that sleeps for 2 seconds
Output: Time taken: ~2.00 seconds

Example 3:
A function that multiplies two numbers (e.g., 10 * 20)
Output: Time taken: ~0.00001 seconds

```


4. Write a recursive function that takes a number n and returns a list of all numbers from n down to 1 and then back up to n.
```
Example 1:
Input: 3
Output: [3, 2, 1, 2, 3]

Example 2:
Input: 5
Output: [5, 4, 3, 2, 1, 2, 3, 4, 5]
```