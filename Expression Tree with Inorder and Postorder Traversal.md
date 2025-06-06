# Experiment 9(c): Expression Tree – Inorder and Postorder Traversal

## Aim
To write a Python program to build the following expression tree and print the inorder and postorder traversal.


---

## Algorithm

1. Begin the program.
2. Import the necessary modules (`build`, `Node`) from the `binarytree` package.
3. Define a list `x` representing the binary tree in pre-order format.
4. Use the `build()` function to construct the expression tree from the list.
5. Print the inorder traversal of the expression tree using `.inorder`.
6. Print the postorder traversal of the expression tree using `.postorder`.
7. End the program.

---

## Program

```
from binarytree import build
x=['*','+','-',9,3,8,4]
tree=build(x)
print(tree.inorder)
print(tree.postorder)
```

## OUTPUT
![Screenshot (265)](https://github.com/user-attachments/assets/0263bd1c-4502-4f86-8f2b-9875b150c1a8)

## RESULT
Thus the python program was initialised and executed successfully.
