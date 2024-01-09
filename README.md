

<div align="center">
  <h2 style="margin-bottom: 0;">Python Questions 2024</h2>
  <img src="https://github.com/Aashwin-Kumar/My-python-image/blob/main/7LIV.gif" alt="Python gif" width="100"/>
</div>

<hr style="border: 1px solid gray; margin: 10px 0;">

<p align="center">From novice to expert levels, challenge your grasp of Python—whether you're brushing up on the basics, diving into advanced concepts, or gearing up for that crucial coding interview! 💡🔥 Keep an eye on this repository as I consistently introduce fresh problem sets. The answers? They're neatly tucked away in the **hidden sections** beneath the questions—just click to reveal. Let the coding adventure begin! 🚀🐍 </p>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 1 What is the output of the following code snippet?

```python
my_list = [1, 2, 3, 4, 5]
my_list = my_list[-1:-4:-1]
print(my_list)
```

Which of the following options is correct?

- a) [5, 4, 3]
- b) [5, 4, 3, 2, 1]
- c) [4, 3, 2]
- d) [3, 4, 5]

<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) [5, 4, 3]

Explanation:

The code creates a list my_list with values [1, 2, 3, 4, 5].
The slicing operation my_list[-1:-4:-1] extracts elements starting from the last element (-1) to the third element from the end (-4) in reverse order (-1 step).
Therefore, the result is [5, 4, 3].

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 2 What is the output of the following code snippet?

```python
x = 5
y = 5
print(x is y)
```

Which of the following options is correct?

- a) True
- b) False
- c) Depends on the Python version
- d) Error
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) True

Explanation:

In CPython, small integers (usually -5 to 256) are cached and reused, so x is y will be True for small integers.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 3 What is the output of the following code snippet?

```python
my_str = "Python"
result = my_str[6:] + my_str[:6]
print(result)
```

Which of the following options is correct?

- a) "Python"
- b) "PythonPython"
- c) "onPyth"
- d) Error
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) "Python"

Explanation:

Slicing is forgiving in Python. When the indices exceed the length of the string, it wraps around.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 4 What is the output of the following code snippet?

```python
def func(a, b=[]):
    b.append(a)
    return b

print(func(1))
print(func(2))
```

Which of the following options is correct?

- a) [1], [2]
- b) [1], [1, 2]
- c) [1], [2]
- d) Error
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: b) [1], [1, 2]

Explanation:

The default value for b is mutable (a list), and it is shared among all calls to the function.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 5 What is the output of the following code snippet?

```python
x = 10
y = 0
result = x/y if y != 0 else "Undefined"
print(result)
```

Which of the following options is correct?

- a) 0
- b) "Undefined"
- c) Error
- d) 1
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: b) "Undefined"

Explanation:

The conditional expression checks if y is not equal to 0, and if true, it returns the result of x/y; otherwise, it returns "Undefined."

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 6 What is the output of the following code snippet?

```python
a = [1, 2, 3]
b = [4, 5]
c = a + b
print(c)
```

Which of the following options is correct?

- a) [1, 2, 3, 4, 5]
- b) [[1, 2, 3], [4, 5]]
- c) Error
- d) [4, 5, 1, 2, 3]
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) [1, 2, 3, 4, 5]

Explanation:

The + operator concatenates lists.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 7 What is the output of the following code snippet?

```python
nums = [1, 2, 3, 4, 5]
result = [x if x % 2 == 0 else -x for x in nums]
print(result)
```

Which of the following options is correct?

- a) [1, -2, 3, -4, 5]
- b) [2, 4, 6, 8, 10]
- c) [-1, -2, -3, -4, -5]
- d) [1, 2, 3, 4, 5]
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) [1, -2, 3, -4, 5]

Explanation:

List comprehension with a conditional expression that negates odd numbers.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 8 What is the output of the following code snippet?

```python
my_dict = {1: 'one', 2: 'two', 3: 'three'}
result = my_dict.get(4, 'four')
print(result)
```

Which of the following options is correct?

- a) 4
- b) 'four'
- c) 'three'
- d) Error
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: b) 'four'

Explanation:

The get method returns the value for the specified key or a default value if the key is not present.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 9 What is the output of the following code snippet?

```python
a = [1, 2, 3]
b = a.copy()
b[0] = 5
print(a)
```

Which of the following options is correct?

- a) [1, 2, 3]
- b) [5, 2, 3]
- c) [1, 5, 3]
- d) Error
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: a) [1, 2, 3]

Explanation:

The copy method creates a new list, so modifying b does not affect a.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 10 What is the output of the following code snippet?

```python
def outer():
    x = 10
    def inner():
        nonlocal x
        x += 5
    inner()
    return x

result = outer()
print(result)
```

Which of the following options is correct?

- a) 10
- b) 15
- c) Error
- d) 5
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: b) 15

Explanation:

The nonlocal keyword allows the inner function to modify the variable in the outer scope.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">

Q. 11 What is the output of the following code snippet?

```python
original_list = [1, [2, 3], 4]
shallow_copy = original_list.copy()

shallow_copy[0] = 5  
shallow_copy[1][0] = 'a' 

print(original_list)
```

Which of the following options is correct?

- a) [5, ['a', 3], 4]
- b) [5, [2, 3], 4]
- c) [1, ['a', 3], 4]
- d) [1, [2, 3], 4]
  
<details>
<summary>Click to reveal the answer</summary>

The correct answer is: c) [1, ['a', 3], 4]

Explanation:

modifications to the elements within nested objects (like shallow_copy[1][0]) impact both the original and the shallow copied lists, as they share references to the same nested objects.

</details>

<hr style="border: 1px solid gray; margin: 10px 0;">


