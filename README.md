Download Link: https://assignmentchef.com/product/solved-cs575-homework-5
<br>
<h1></h1>

<ol>

 <li>Show the result of inserting 13, 8, 5, 9, 4, 6, 12, 2, 1 and 3 in that order into an initially empty AVL tree. Show the tree after each insertion, clearly labeling which tree is which<strong>. </strong></li>

 <li>Give pseudocode for a linear-time algorithm that verifies that an AVL tree is correctly maintained. Assume every node has fields key, data, height, left, and right and that keys can be compared with &lt;, ==, and &gt;. The algorithm should verify all of the following:

  <ul>

   <li>The tree is a binary search tree.</li>

   <li>The height information stored in each node is correct.</li>

   <li>Every node is balanced.</li>

  </ul></li>

</ol>

Your code should have a Boolean return type, and return true if the tree is a valid AVL tree, or  false if it violates any of the above properties.

<strong>Programming Part (75 points) What to hand in? </strong>

<ol>

 <li>Submit code with in-line documentation</li>

 <li>Run your code on your local machine as well as on ‘remote’. A readme file outlining how your code should be run.</li>

</ol>

<strong>You need to write the assignment in C++. For problems 1 to 3, use the skeleton code is  provided to you. </strong>

Consider the BST.h, BST.cpp and treetester.cpp files provided to you. These files only contain the insert, search and empty member functions.  Please make any changes necessary to compile and run the code.

<h1>Problem 1:</h1>

Write new member functions called

<ol>

 <li><strong>preOrder() </strong>that implements the preorder traversal algorithm of a binary search tree. Your member function should display each node’s data on the screen.</li>

 <li><strong>inOrder() </strong>that implements the inorder traversal algorithm of a binary search tree. Your member function should display each node’s data on the screen.</li>

</ol>




<ol>

 <li><strong>nodeCount()</strong> to count the number of nodes in a binary search tree. In this function, you should use a recursive function. You can’t just use a variable such as “mySize”.</li>

</ol>




<h1>Problem 2:</h1>




In this problem, you will write the delete member function to delete a node from a BST. Recall that to delete a node from a BST you need to consider the three cases that we discussed in class.




<ol>

 <li>The node has no children (easiest case)</li>

 <li>The node has only one child (easy case)</li>

 <li>The node has two children (hard case)</li>

</ol>




As an example consider the following BST. You need to create this BST by inserting these elements from the treetester.cpp file.










Delete nodes 13, 10 and 3 in order. Every time you delete a node, use the inorder() member function you wrote to show that the BST property is being maintained. Inorder() will print out the elements of a BST in sorted order.




Test your code with other BSTs to see if the delete member function is working correctly.




<h1>Problem 3:</h1>




Modify the provided files and write additional methods to the class and convert the Binary Search Tree to an AVL tree. Note that the tree should be balanced both after insertion and deletion.




<h1>Problem 4:</h1>

<strong> </strong>

Implement and test the longest common subsequence (LCS) problem. For this problem, you are required to maintain a two dimensional arrays for storing the tables. You need to output the LCS along with the length. You need to implement the algorithm covered in the lectures. You are not allowed to search for solutions on the web.