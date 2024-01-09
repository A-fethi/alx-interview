## Pascal's Triangle

This Python script includes a function to generate Pascal's triangle up to a specified number of rows.

# Functionality

The `pascal_triangle(n)` function takes an integer `n` as input and generates Pascal's triangle up to the nth row. The result is returned as a list of lists, where each list represents a row of the triangle.

If the input `n` is less than or equal to 0, an empty list is returned.

# Usage
- Save the function in a file named `0-pascal_triangle.py`.
- Incorporate the function into your Python script using the following import statement:

```console
from 0-pascal_triangle import pascal_triangle
```
- Utilize the function in your script, as illustrated in the example below:
```console
from 0-pascal_triangle import pascal_triangle

def print_triangle(triangle):
    """
    Print the Pascal's triangle.
    """
    for row in triangle:
        print("[{}]".format(",".join(map(str, row))))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))
```
- Execute your Python script to observe Pascal's triangle up to the 5th row being printed.

Ensure that the `0-pascal_triangle.py` file is located in the same directory as your main script, or adjust the import statement accordingly.
