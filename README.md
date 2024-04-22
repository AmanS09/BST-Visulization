
**BSTVisualization**

This Java program visualizes a Binary Search Tree (BST) using Swing for the GUI. It allows users to dynamically add and delete nodes from the tree, with automatic visualization updates.


**Features:**

Interactive GUI: Add or delete nodes with buttons.
Tree Visualization: Dynamically updates the tree structure on screen.
Traversals Display: Shows Inorder, Preorder, and Postorder traversals.
BST Height: Displays the height of the BST.


**How to Use:**

Run the BSTVisulization.java file to start the program.
Use the "Add" and "Delete" buttons to interact with the BST.
The GUI updates to reflect changes in the tree structure.
Inorder, Preorder, and Postorder traversals are displayed dynamically.
The height of the BST is shown at the top of the GUI.

**Traversal Details:**

example:-

Preorder: Root-Left-Right traversal: 1 2 4 5 3 6 7

Inorder: Left-Root-Right traversal: 4 2 5 1 6 3 7

Postorder: Left-Right-Root traversal: 4 5 2 6 7 3 1

**Libraries Used:**

Java Swing for GUI components.

JFreeChart for utility functions.



## Explanation
### Adding Element in Binary Search Tree
- We can add element in BST using two ways.
	1. With using **"Add"** button.
	2. With pressing **"A"** or **"a"** or **"Enter"** key in keyboard.
	
![Add in BST](https://user-images.githubusercontent.com/55116730/102015789-a6009c00-3d83-11eb-8ae9-bf47b3fd6c67.gif "Adding Element in BST")

### Deleting Element from Binary Search Tree
- We can also delete element in BST using two ways.
	1. With using **"Delete"** button.
	2. With pressing **"D"** or **"d"** key in keyboard.

![Delete in BST](https://user-images.githubusercontent.com/55116730/102015791-a9942300-3d83-11eb-9c0f-4befc0288583.gif)
- If entered element is no present or Binary Search Tree is empty then it throws an popup window.
	1. BST Empty Error
![BST Empty Error](https://user-images.githubusercontent.com/55116730/102014950-9b8fd380-3d7e-11eb-845b-9ff621e5c559.jpg "BST Empty Error")
	2. Element Not Available Error
![Element Not Available Error](https://user-images.githubusercontent.com/55116730/102014949-9a5ea680-3d7e-11eb-9288-d9d3bc018ba8.jpg "Element Not Available Error")
