Download Link: https://assignmentchef.com/product/solved-coen171-homework-1-imperative-programming
<br>
The goal of this assignment is to introduce you to writing code in two imperative language designed for different purposes. You should not mimic Pascal code in C, nor C code in Pascal, but rather use the best mechanisms provided by each language. Use the Linux machines in the Engineering Computing Center for this assignment. The Pascal compiler is fpc and the C compiler is gcc.

<h1>1        Quicksort</h1>

Under /scratch/coen171/homework1, you will find an implementation in Pascal of <strong><em>quicksort</em></strong>, an efficient sorting algorithm. Translate the program to C, keeping the same procedure and function names and parameters, for all but the top-level program, which will become the function main in C. Call this program sort.c and place it in the shared folder.

<strong>Goal:              </strong>To learn about methods of passing parameters and recursion.

<strong>Hints:        </strong>None.

<h1>2        BinarySearchTrees</h1>

A <strong><em>binary search tree </em></strong>is either empty, or it consists of a node with two binary search trees as subtrees. Each node holds an integer. The elements in a binary search tree are arranged so that smaller elements appear in the left subtree of a node and larger elements appear in the right subtree. In the course folder, you fill find an implementation of a binary search tree in C. Translate the program to Pascal, keeping the same function names and parameters, for all but the function main, which will become the top-level program in Pascal. Call this program tree.p and place it in the shared folder.

<strong>Goal:            </strong>To learn about types and data representation.

<strong>Hints:        </strong>You will need to use a record or structure to represent a tree node, and tree nodes need to be dynamically allocated. It is easiest to have both functions be recursive. You will find an example in Pascal of a stack built using a linked list in the course folder.