# php-foundations-datastructures--Edianon-Jasper-Glenn-
Core Functionality
This system provides three distinct methods for managing and accessing book data, each using different programming approaches for optimal performance.

1. Recursive Category Display

Processes nested book categories through self-calling functions

Dynamically adjusts indentation to visualize hierarchy depth

Handles unlimited subcategory levels without manual configuration

Visual Output Example:

Fiction
....Science Fiction
........Dune
........Neuromancer
........Foundation
....Fantasy
........The Name of the Wind
........Mistborn
........The Way of Kings
Non-Fiction
....Science
........A Brief History of Time
........The Selfish Gene
........Sapiens
2. Hash Table Data Retrieval

Implements associative arrays for O(1) access time

Maps book titles directly to metadata collections

Provides immediate fail-safes for missing entries

Data Retrieval Example:

=== BOOK DETAILS ===
Title: Neuromancer
• Author: William Gibson
• Published: 1984
• Category: Science Fiction

Title: Mistborn
• Author: Brandon Sanderson  
• Published: 2006
• Category: Fantasy

Title: Unknown Book
• STATUS: Not found in database
3. Binary Search Tree Operations

Maintains sorted order through tree structure properties

Enables efficient search operations with O(log n) complexity

Automatically outputs elements in sorted sequence via inorder traversal

Search & Sort Example:

ALPHABETICAL INDEX:
A Brief History of Time
Foundation
Mistborn
Neuromancer
Sapiens
The Name of the Wind
The Way of Kings

QUERY RESULTS:
Search("Neuromancer"): ✓ FOUND
Search("The Hobbit"): ✗ NOT FOUND  
Search("Foundation"): ✓ FOUND
