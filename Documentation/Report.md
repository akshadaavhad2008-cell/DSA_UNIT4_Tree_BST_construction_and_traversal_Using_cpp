# BST Construction and Traversal

## 1. Introduction

A Binary Search Tree (BST) is a non-linear data structure used to store and organize data efficiently. Each node contains a value, a left child, and a right child. The left subtree contains smaller values, while the right subtree contains greater values. Tree traversal is used to visit and display all nodes.

## 2. Problem Statement

To develop a C++ program to construct a Binary Search Tree by inserting elements and perform Inorder, Preorder, and Postorder traversals to display the elements.

## 3. Objectives

* To understand the concept of a Binary Search Tree.
* To construct a BST using node insertion.
* To implement Inorder, Preorder, and Postorder traversals.
* To understand the practical application of tree data structures.

## 4. Software Requirements

* Programming Language: C++
* Compiler: GCC / Code::Blocks / Visual Studio Code
* Operating System: Windows / Linux

## 5. Data Structures Used

* **Binary Tree:** Organizes elements in a hierarchical structure.
* **Structure or Class:** Represents each node of the tree.
* **Pointers:** Connect nodes to their left and right children.
* **Recursion:** Used to perform tree traversal.

## 6. Algorithm

### A. BST Construction

1. Start the program.
2. Create an empty Binary Search Tree.
3. Enter the number of elements.
4. Insert each element into the BST.
5. If the tree is empty, create the root node.
6. If the element is smaller than the current node, insert it into the left subtree.
7. If the element is greater than the current node, insert it into the right subtree.
8. Repeat until all elements are inserted.

### B. Inorder Traversal

1. Visit the left subtree.
2. Visit the root node.
3. Visit the right subtree.

### C. Preorder Traversal

1. Visit the root node.
2. Visit the left subtree.
3. Visit the right subtree.

### D. Postorder Traversal

1. Visit the left subtree.
2. Visit the right subtree.
3. Visit the root node.

## 7. Sample Input

```text
Enter number of nodes: 7
Enter node values:
50 30 70 20 40 60 80
```

## 8. BST Structure

```text
          50
         /  \
       30    70
      / \    / \
     20 40  60 80
```

## 9. Sample Output

```text
BST constructed successfully!

Inorder Traversal: 20 30 40 50 60 70 80

Preorder Traversal: 50 30 20 40 70 60 80

Postorder Traversal: 20 40 30 60 80 70 50
```

## 10. Applications

* Searching and sorting data.
* Maintaining ordered information.
* Implementing sets and dictionaries.
* Organizing hierarch
