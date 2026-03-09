# Holberton School — Binary Trees

![Holberton](https://img.shields.io/badge/Holberton-School-red?style=flat-square) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c)

## Description

This repository explores **Binary Trees** and their variants in C. It covers tree construction, traversal algorithms, and operations on Binary Search Trees (BST), AVL Trees, and Max Binary Heaps.

## Data Structure

```c
typedef struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
} binary_tree_t;
```

## Topics Covered

| Topic | Description |
|-------|-------------|
| Tree creation & insertion | Build nodes and link them |
| Tree traversal | Pre-order, In-order, Post-order, Level-order |
| Tree measurement | Height, depth, size, balance factor |
| Binary Search Tree (BST) | Insertion, search, deletion |
| AVL Tree | Self-balancing BST |
| Max Binary Heap | Priority queue structure |

## Key Functions

- `binary_tree_node` — Create a new node
- `binary_tree_insert_left` / `binary_tree_insert_right` — Insert children
- `binary_tree_height` — Measure tree height
- `binary_tree_size` — Count total nodes
- `binary_tree_is_full` / `binary_tree_is_perfect` / `binary_tree_is_complete`
- `binary_tree_levelorder` — BFS traversal

## Learning Objectives

- Understand what a binary tree is and its properties
- Differentiate between BST, AVL, and Max Heap
- Implement traversal algorithms (DFS & BFS)
- Calculate height, depth, size, and balance factor
- Understand time complexity of tree operations

## Technologies

| Tool | Version |
|------|---------|
| Ubuntu | 22.04 LTS |
| GCC | 12.x |
| Betty Linter | Latest |

## Author

**Kevin Voka** — [GitHub](https://github.com/kevinvoka)

