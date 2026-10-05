# calcutils

A simple Python utility package providing basic math helper functions.
Created as part of a Python package publishing lab (PyPI & TestPyPI).

## Installation

    pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ calcutils_cyuzuzo

## Functions

| Function | Description |
|----------|-------------|
| `add(a, b)` | Returns the sum of two numbers |
| `multiply(a, b)` | Returns the product of two numbers |
| `average(numbers)` | Returns the arithmetic mean of a list of numbers; returns 0.0 if the list is empty |

## Usage

    from calcutils import operations

    print(operations.add(10, 25))                  # 35
    print(operations.multiply(4, 5))               # 20
    print(operations.average([10, 20, 30, 40]))    # 25.0

## License

MIT License
