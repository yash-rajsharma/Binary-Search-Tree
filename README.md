<img  src = 'https://s3.studylib.net/store/data/009567192_1-d038e09169581a1f430135d4a3101beb.png' alt = "Binary Search Tree Image" width ="100%" />

# Binary Search Tree (BST) Implementation in JavaScript

This Repository contains a simple implementation of a **Binary Search Tree (BST)** in JavaScript. The BST data structure is designed for efficient **insertion**, **lookup**, and **deletion** operations, typically with a time complexity of **O(log n)** when the tree is balanced.

## Overview

A **Binary Search Tree** (BST) is a data structure where:
- Each node has a **value**, and at most two **children**: a left and a right child.
- The **left child** node's value is **less than** the parent node's value.
- The **right child** node's value is **greater than** the parent node's value.
- This organization enables fast search, insert, and delete operations.

## Features

This BST implementation includes the following operations:
- **Insert**: Adds a new value to the tree in the correct position.
- **Lookup**: Finds and returns a node with a specified value.
- **Remove**: Deletes a node with a specified value and restructures the tree accordingly.

## Code Structure

- **Node Class**: Defines a single node in the BST, with properties for the value, left child, and right child.
- **BinarySearchTree Class**: Manages the tree's root node and contains methods for `insert`, `lookup`, and `remove` operations.
  

## Complexity Analysis

The time complexity of operations in a Binary Search Tree (BST) can vary based on whether the tree is balanced. Here’s a breakdown:

| Operation | Average Time Complexity | Worst Time Complexity |
|-----------|-------------------------|------------------------|
| **Insert**    | O(log n)                | O(n)                  |
| **Lookup**    | O(log n)                | O(n)                  |
| **Remove**    | O(log n)                | O(n)                  |

- **Average Case**: For a balanced tree, the average time complexity for `insert`, `lookup`, and `remove` operations is **O(log n)**, as the tree height is minimized.
- **Worst Case**: If the tree becomes unbalanced (e.g., through sequential insertion of sorted data), it degrades to **O(n)**, resembling a linked list.

In an unbalanced tree, all nodes could align in a single path, which leads to the slower, linear **O(n)** complexity for all operations.

