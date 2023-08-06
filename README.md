# SuperMarket-Management-linked-list-implementation-in-C
This project is an implementation of a food store management system using linked lists in C. It extends the solution from a previous homework assignment (Homework 2). The program includes several functionalities:

General Linked List: A singly linked list is implemented to hold elements of any type, allowing for flexible data storage. The required functions include initializing the list, adding elements, removing elements (with support for freeing memory), freeing the entire list, and printing all elements.
SuperMarket Structure: The SuperMarket structure is modified to store products in a sorted linked list, using the product's barcode as the sorting key. The previous array-based product list is removed, and the productCount variable is eliminated.
Customer Structure: The Customer structure is extended to include fields for the number of purchases made in the store and the total amount spent.
Food Company: The Food Company allows sorting its array of customers based on various criteria, such as name, number of purchases, and total spending. The sorting is done using the qsort function from the stdlib library. Additionally, the company provides a binary search capability to find customers in the sorted array.
File Handling: The program saves all data in binary and text files. The binary file, "SuperMarket.bin," stores the company's data, while the text file, "Customers.txt," stores the customer information.
Generic Array Function: A generic function, generalArrayFunction, is implemented to handle arrays of any type. It traverses the array and calls a specified function for each element.
The main function initializes the system by loading data from the appropriate files. If the data loading fails, the system is initialized from user input, as in Homework 2. The program menu offers options for sorting customers by a chosen attribute and searching for customers based on the sorted array.

At the end of the program, it saves the Food Company's data to the corresponding files.

