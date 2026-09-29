# Rectangle: Documentation

> A small library for calculating rectangle properties.

## Table of contents

1. [Overview](#overview)
2. [Function reference](#function-reference)
3. [Change history](#change-history)

## Overview

The `rectangle.py` module provides two functions that take the side
lengths of a rectangle and return its **area** and **perimeter**.

| Function    | Returns   | Formula       |
|-------------|-----------|---------------|
| `area`      | area      | `a * b`       |
| `perimeter` | perimeter | `2 * (a + b)` |

## Function reference

### `area(a, b)`

Calculates the area of a rectangle.

**Parameters**

- `a`: length of one edge
- `b`: length of the other edge

**Returns:** `a * b`

**Example**

```python
from rectangle import area

print(area(3, 4))  # 12
```

### `perimeter(a, b)`

Calculates the perimeter of a rectangle.

**Parameters**

- `a`: length of one edge
- `b`: length of the other edge

**Returns:** `2 * (a + b)`

**Example**

```python
from rectangle import perimeter

print(perimeter(3, 4))  # 14
```
