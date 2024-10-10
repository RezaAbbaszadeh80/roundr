# My Package

A sample Python package.

## Installation

You can install the package using pip:

```
pip install round_utils
```

## Usage

Here is an example of how to use the package:

```python

from roundr import round_utils

print(round_utils(32.56, 1))  # 32.6
print(round_utils(349.5))  # 350
print(round_utils(6.54, 1))  # 6.5
print(round_utils(6.54))  # 7.0
print(round_utils('6.55'))  # 7.0
print(round_utils(6.56, '1'))  # 6.6
print(round_utils(6, 'e'))  # "Invalid input, try again!"
print(round_utils('r', 3))  # "Invalid input, try again!"

```
