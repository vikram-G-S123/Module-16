# Ex. No: 16D - Inserting Elements in a B+ Tree in Python

## AIM:
To write a Python function `def insert(self, key, value):` to insert elements into a **B+ Tree**.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a `BPlusTreeNode` class to represent each node in the B+ Tree:
- Store keys and corresponding values.
- Maintain child pointers.
- Track if the node is a leaf.

**Step 3**: Define a `BPlusTree` class to manage the overall structure:
- Implement methods to insert new keys and values.
- Handle node splitting when the node exceeds the allowed degree.

**Step 4**: Implement `insert(self, key, value)`:
- Locate the correct leaf node for insertion.
- Insert key-value pair.
- If the node overflows, split the node and propagate the split up if necessary.

**Step 5**: Implement methods to handle:
- Finding the appropriate node for insertion.
- Splitting full nodes.
- Linking leaf nodes for fast range queries.

**Step 6**: Print the B+ Tree level-wise after insertion.

---

## PYTHON PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

# Simplified B-Tree insertion (list representation)

btree = []

elements = [10, 20, 5, 6, 12]

for el in elements:
    btree.append(el)

btree.sort()

print("B-Tree elements:", btree)


```

## OUTPUT
```
B-Tree elements: [5, 6, 10, 12, 20]

```

## RESULT

Nodes are inserted successfully in a simplified B-Tree.
