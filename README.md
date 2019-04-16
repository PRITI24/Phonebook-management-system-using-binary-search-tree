# Phonebook-management-system-using-binary-search-tree
4th Semester Computer Engineering Project
# MKSSS'S CUMMINS COLLEGE OF ENGINEERING FOR WOMEN

# Taught data structures
1)Binary Search tree
2)Avl tree
3)Traversals of binary tree-a)Inorder
                            b)Preorder
                            c)Postorder
4)Red-black tree
5)Hashing-a)Linear Probing
          b)Double hashing
          c)Separate Chaining
          d)Quadratic hashing
6)Heap-a)max heap
       b)min heap
7)File handling in java
8)Kruskal's algorithm,Prim's algorithm

# Topic: THIS DEMONSTRATES THE PHONEBOOK MANAGEMENT SYSTEM WITH BINARY SEARCH TREE SO THAT TRAVERSING WILL BE EASY THROUGH THE PHONEBOOK.....
# In eclipse

# Phonebook management have three main operations:
#1.Searching
#3.Deleting
These three operation can be performed efficiently(among above data structures) with BST.
Bst gives the sorted phonebook display naturally without any sorting operations.
# Time complexities in O

1.Searching O(Log n)
2.Deletion O(Log n)
3.Display O(n)
4.Update O(log n)
# OPERATIONS IMPLEMENTED.............
1)Search
2)Insert
3)Display
4)Delete
5)Update
# OUTPUT:-In eclipse java

/*
**********WELCOME TO OUR PHONEBOOK**********

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
2

Enter the Name    : 
pooja

Enter the phone no: 
7894561230

Enter the Email id : 
pol
Enter Valid Email address :
pok

Do you want to Add any Phone Record (0/1): 
1

Enter the Name    : 
sangeeta

Enter the phone no: 
7854123960

Enter the Email id : 
wwd
Enter Valid Email address :
wds

Do you want to Add any Phone Record (0/1): 
1

Enter the Name    : 
sony

Enter the phone no: 
2365987410

Enter the Email id : 
cvcd
Enter Valid Email address :
fdfd

Do you want to Add any Phone Record (0/1): 
0

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
3
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
pooja	    7894561230	      pok
sangeeta	    7854123960	      wds
sony	    2365987410	      fdfd
-----------------------------------------------

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
1
Enter a Name tobe searched
sangeeta

	-----RECORD FOUND-----
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
sangeeta	    7854123960	      wds

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
3
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
pooja	    7894561230	      pok
sangeeta	    7854123960	      wds
sony	    2365987410	      fdfd
-----------------------------------------------

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
4
Enter a Contact name you want to delete
sangeeta
sangeeta

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
3
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
pooja	    7894561230	      pok
sony	    2365987410	      fdfd
-----------------------------------------------

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
5
Enter a Contact Name you want to update
pooja
Enter New Number : 
6666662134

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-

3
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
pooja	    6666662134	      pok
sony	    2365987410	      fdfd
-----------------------------------------------

Do you want to continue?(0/1)--OPERATIONS--
1

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-
1
Enter a Name tobe searched
sony

	-----RECORD FOUND-----
-----------------------------------------------
NAME	|  CONTACT NUMBER  |	EMAIL
-----------------------------------------------
sony	    2365987410	      fdfd

Do you want to continue?(0/1)--OPERATIONS--
6

 1. Search             
 2. Insertion/Creation 
 3. All Contacts Information 
 4. Removal 
 5. Change a Phonenumber 
 6. Exit 
ENTER YOUR CHOICE:-

*/
