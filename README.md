# Day-92-Second-Smallest-Number
# Python Day 92 - Second Smallest Number

This program finds the second smallest number from a list.

## Example

Input:

```text
[10, 25, 7, 40, 15]
```

Output:

```text
Second smallest number: 10
```

## Concepts Used

* Lists
* `min()` function
* `remove()` method
* Variables
* `print()` function

## How It Works

1. Find the smallest number using `min()`.
2. Remove the smallest number using `remove()`.
3. Find the minimum number again.
4. The result is the second smallest number.

## Python Code

```python
numbers = [10, 25, 7, 40, 15]

smallest = min(numbers)

numbers.remove(smallest)

second_smallest = min(numbers)

print("Second smallest number:", second_smallest)
```
