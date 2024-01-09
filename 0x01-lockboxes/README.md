# Lockboxes

## Description

This Python puzzle involves determining whether it's possible to open all locked boxes in a given sequence. Each box is numbered, and inside each box, there may be keys that match other boxes. The challenge is to figure out if, starting from an initially unlocked box, you can use the keys to open all the boxes in the sequence.

## Puzzle Details

- Each box is represented as a list.
- Keys with numbers corresponding to box numbers can open those boxes.
- The first box (`boxes[0]`) is initially unlocked.
- The task is to implement the `canUnlockAll` method, which returns `True` if all boxes can be opened and `False` otherwise.


## Method Signature

```console
def canUnlockAll(boxes):
    """Method that determines if all boxes can be opened."""
```

## Input

`boxes`: A list of lists, where each inner list represents a box and contains positive integers as keys.

## Output

Returns `True` if all boxes can be opened, and `False` otherwise.

## Example Usage

```console
boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))  # Output: False
```
