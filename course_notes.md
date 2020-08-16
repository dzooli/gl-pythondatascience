# Python for Machine Learning

## Tools

- Anaconda Individual for Windows
- Anaconda prompt
  - install package:
  ```bash
  conda install numpy
  ```

### IDEs

Installed with the Anaconda Navigator

- Spyder
- Jupyter Notebooks

### Jupyter keyboard shortcuts

- Enter Command mode: ESC
- Enter Edit mode: ENTER

#### Command mode keys

- insert cell below: b
- insert cell above: a
- delete cell: dd
- convert cell to MarkDown: m
- convert cell to code: y
- Cell to heading 1-6: 1-6
- Cell to raw: r
- Cut cell: x
- Copy cell: c
- Paste cells below: v
- Paste cells above: SHIFT+v

#### Running the cells

1. SHIFT+ENTER: Run cell and select next
2. CTRL+ENTER: Run selected cells
3. ALT+ENTER: Run cell and insert below

#### Inline help

- SHIFT+TAB: Show declaration
- SHIFT+TAB+TAB: Show full description

## Python data types

Let's try to understand the Python data types.

### String

### Numbers

- integer
- float

### Boolean

### List

- del()
- list.remove()
- list.pop()
- list.append()
- sorted() vs. list.sort() (**sort() changes the original**)

### Dictionary

- [k:v, ...]

### Tuple

- ()

### Set

- {}

## Conditional statements

- **if, else, elif**

## Loops

- for
- while
- nested loops

## Functions

- **def** name(positional_params, keyword_params[=with_default_value])

## **Lambda's** and

## **List comprehension**

```python
l1 = [ x*y for x in range(0,11) for y in range(0,11)]
l2 = [ x*y for x in range(0,11) for y in range(0,11) if (x*y)%2 == 0]
```

## Filtering

```python
l1 = [1,2,3,4,5,6,7]
filtered = list(filter(lambda x: x%2==0, l1))
print(filtered)
```

## Map and Reduce, Iterate, Accumulate

See: [filter_map_spec_functions.jpynb](./filter_map_spec_functions.jpynb)

Used **libraries**:

- **functools** for reduce
- **operator** for reduce with addition
- **itertools** for accumulation
