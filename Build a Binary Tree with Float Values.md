# Experiment 9(a): Binary Tree (Float Values)

## Aim
To write a Python program to build a binary tree with a root, left, and right node using float values.

---

## Algorithm

1. Start the program.
2. Import the `Node` class from the `binarytree` module.
3. Create a root node using the `Node` class and input a floating-point value for the root.
4. Create left and right child nodes for the root using floating-point values.
5. Convert the binary tree to a list.
6. Print the list of nodes.
7. End the program.

---

## Program

```
from  binarytree import build
l=[]
for i in range(3):
    a=float(input())
    l.append(a)
root=build(l)
print("List of nodes :",list(root))

```

## OUTPUT
![Screenshot (263)](https://github.com/user-attachments/assets/533733d2-787e-43bb-b7f9-7baf4f52bdc9)

## RESULT
Thus the python program is initialised and executed successfully.
