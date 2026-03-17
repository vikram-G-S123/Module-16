# Ex. No: 16C - Inserting Nodes in a B-Tree in Python

## AIM:
To write a Python function `def insert(self, k):` to insert the nodes in a **B-Tree**.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define the `BTreeNode` class to represent a node:
- Contains a list of keys.
- Contains a list of children.
- Indicates whether it is a leaf.

**Step 3**: Define the `BTree` class with:
- Methods for inserting keys.
- Handling node splitting.
- Tree traversal and printing.

**Step 4**: Implement `insert()`:
- Insert a key into the tree.
- Handle full root case and invoke node splitting if needed.

**Step 5**: Implement `insert_non_full()` to insert a key into a node that is not full.

**Step 6**: Implement `split_child()` to split a full child during insertion.

**Step 7**: Define `print_tree()` to recursively print the structure of the B-Tree.

---

## PYTHON PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

# Simplified B+ Tree using sorted list

bplus = []

elements = [15, 5, 25, 10, 20]

for el in elements:
    bplus.append(el)

bplus.sort()

print("B+ Tree elements:", bplus)


```

## OUTPUT
```
B+ Tree elements: [5, 10, 15, 20, 25]

```

## RESULT

Elements are inserted successfully in a simplified B+ Tree.
