# Aim: To study and implement C++Pointer basics

# Software Required:

Visual Studio

# Theory: 

•	Pointers are symbolic representations of addresses. 

•	They enable programs to simulate call-by-reference as well as to create and manipulate dynamic data structures. 

•	Iterating over elements in arrays or other data structures is one of the main use of pointers. 

•	The address of the variable you’re working with is assigned to the pointer variable that points to the same data type (such as an int or string).

Uses of Pointers:

. Pointers are a useful concept in C++ that allow direct access to memory addresses, providing greater control over memory and data manipulation. Below are some primary uses of pointers in C++:

. Dynamic Memory Allocation: Pointers allow memory to be allocated dynamically at runtime using operators like new and delete. This enables the creation of objects or arrays whose sizes are determined during execution.

. Implementing Data Structures: Pointers are used to implementing complex data structures such as linked lists, trees, and graphs, where elements are dynamically allocated and linked together.

. Pass Arguments by Pointer: Pass the argument with their address and make changes in their value using pointer. So that the values get changed into the original argument.

# Implementation:

Pointers in C++ were implemented using the following codes,

1.Increment of pointers

2.Addition or Subtraction of Pointers

3.Reversing an Array using a Pointer

4.Printing a String using Pointers

# Algorithm:

Increment of pointers:

1.Start

2.Initialize an integer variable

Set a = 50.

3.Create an integer pointer and assign the address of a

aptr = &a.

4.Display the address stored in aptr (before increment).

5.Increment the integer pointer (aptr++).

This increases the address by sizeof(int) bytes.

6.Display the address stored in aptr (after increment).

7.Initialize a float variable

Set b = 20.22.

8.Create a float pointer and assign the address of b

bptr = &b.

9.Display the address stored in bptr (before increment).

10.Increment the float pointer (bptr++).

This increases the address by sizeof(float) bytes.

11.Display the address stored in bptr (after increment).

12.Initialize a double variable

Set c = 2.45768.

13.Create a double pointer and assign the address of c

cptr = &c.

14.Display the address stored in cptr (before increment).

15.Increment the double pointer (cptr++).

This increases the address by sizeof(double) bytes.

16.Display the address stored in cptr (after increment).

17.Initialize a boolean variable

Set d = true.

18.Create a boolean pointer and assign the address of d

dptr = &d.

19.Display the address stored in dptr (before increment).

20.Increment the boolean pointer (dptr++).

This increases the address by sizeof(bool) bytes.

21.Display the address stored in dptr (after increment).

22.End

Reversing an Array using a Pointer:

1.Start

2.Input the array size

3.Read size.

4.Declare an array of given size

arr[size].

5.Input size elements into the array

6.Loop i = 0 to size-1:

7.Read arr[i].

8.Initialize a pointer to the last element of the array

ptr = arr + size - 1.

9.Traverse the array in reverse using the pointer

10.Loop i = 0 to size-1:

11.Print the value at *ptr.

12.Decrement the pointer (ptr--).

13.End

Addition or Subtraction of Pointers:

1.Start

2.Initialize two integer variables

a = 50

b = 20

3.Declare two integer pointers

aptr, bptr

4.Assign addresses of variables to pointers

aptr = &a

bptr = &b

5.Dereference the pointers to access values

Get value of *aptr (which is a)

Get value of *bptr (which is b)

6.Perform subtraction of values

diff = *aptr - *bptr

7.Perform addition of values

sum = *aptr + *bptr

8.Display results

Print diff

Print sum

9.End

# Conclusion:

Hence, we have learned and implemented basics of pointers in C++






