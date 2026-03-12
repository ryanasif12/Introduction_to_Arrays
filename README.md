# Introduction to Arrays in Python
In this repo file you will see the information listed for Arrays including basic operations for Arrays, module of Array.

# What is Array
An Array is a data structure in Python which can only contain one datatype for all Elements in the Array.

# Why Use Array?
We use Array in Python Because it is very simple and uses less (limited) amount of Memory Storage So it is More faster interpreted and debugged unlike other datastructure like: lists, tuples, dicts, sets etc....

# How to Create An Array?
The syntax/code attached below shows  how we can create an array:

- Code: <br>
arr = [2,4,6,8,10,44] <br>
print(arr)

- Output: <br>
`[2,4,6,8,10,44]`

* arr is the variable name for Array which contains elements that a normal array would contain.

* print() is used to show elements in the Terminal (output for Python).

* print() is also built-in function in python

# How is Array different from other Data Structures?

- Array consumes less Memory.
- Array is represented by square brackets `[]`

# What is the Array module in Python?

-> It is a module package in python used to easily make and identify The Arrays in Code.

# Code using Array Module

- Code:  <br>
`import array` <br>
`arr = array.array('i', [3,5,2,6,9,1])` <br>
`print(arr)`

- Explanation: <br>

- `import array` gives an idea to Python that we are going to use an array.

- `arr` is the name of Variable used for storing the Array.

- `arr = array.array('i', [3,5,2,6,9,1])` is the syntax of making array `'i'` represents the array only allowing integers to be included in the array. If we use a datatype other then the character we gave it will raise a type error indicating we have made a type mistake in our code.

- `print(arr)` we use this when we have to show the array which is stored in variable arr in the output.

# Dimensions of Array
An Array has many dimensions in it. For example 1D which is only a line if viewed in math shapes.
Dimensions are very important because it makes the structure and space for data in an Array. Dimensios are neccesary to store organize,store and access data in more then one direction or space.

### Examples of [n]D arrays:

- 1D array: <br>

1D_arr = [5,8,2,9,10] <br>

- 2D array Explanation: <br>

2 Dimensional array is a Data Structure the represents the data like a table or matrix form in Python when we define the rows and columns to structure the Array.

### Syntax of 2D array:

`D_arr = [[3,6,2,8,5,9]]` <br>
`print(D_arr)` <br>

### Slicing an Array
`print(D_arr[0][3])` - Output: 8
- It is because `[0]` tells that we are going to go inside the element list `D_arr [[3,6,2,8,5,9]]` and `[3]` which chooses the element from the Array. As we know indexing starts from 0 (start) to -1 (ending) indexes in a sequence. In this case sequence is a Array. So `3` in the sequence will be on index 0 (`D_arr[0]`), `6` is on the first index (`D_arr[1]`), same is with element `2` which will be on index `2` (`D_arr[2]`) and finnaly element `8` will be on index 3 (`D_arr[3]`).