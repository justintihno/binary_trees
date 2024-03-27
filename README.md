# Binary trees
#### C         Algorithm		Data structure

## Concepts

1. Binary tree (note the first line: Not to be confused with B-tree.)
2. Data Structure and Algorithms - Tree
3. Tree Traversal
4. Binary Search Tree
5. Data structures: Binary Tree

## Requirements
1. Editors: vim
2. All files were compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
3. Code uses the Betty style. Checked using betty-style.pl and betty-doc.pl
4. No global variables were used

### More Info
Data structures
The following data structures and types was used for binary trees.
Included in header file

Basic Binary Tree
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;

#### Binary Search Tree
typedef struct binary_tree_s bst_t;

#### AVL Tree
typedef struct binary_tree_s avl_t;

#### Max Binary Heap
typedef struct binary_tree_s heap_t;
