# B+-Tree
Insert 1,000 words into a B+ tree and then search the tree for a given word.

This project is a Python implementation of a **B+ Tree** used to store and search through the **1,000 most common English words**. It demonstrates balanced tree operations, node splitting, and fast lookup performance using a custom search function.

---

## Overview

The program:

- Loads words from `1000-most-common-words.txt`
- Inserts each word into a B+ Tree
- Allows fast lookup using a search function
- Demonstrates how a B+ Tree handles sorted data and maintains balance

---

## Features

- Full B+ Tree implementation  
- Leaf and internal node structures  
- Automatic splitting and balancing  
- Bulk word insertion  
- Fast search functionality

---

## Testing
To verify correctness, the list of words to search includes:

- The first word in the tree
- The last word in the tree
- Word selected from middle area of tree
- Word that is not in the tree

