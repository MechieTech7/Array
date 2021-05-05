# Array
Day 3: Wednesday - The goal of this exercise is to help the students understand the following.
What is Array?
An array is a collection of similar types of data.

Why is Array important?
if we want to store the names of 100 people then we can create an array of the string type that can store 100 names.

When to use Array data structure?
Array is a container which can hold a fix number of items and these items should be of the same type. Most of the data structures make use of arrays to implement their algorithms. Following are the important terms to understand the concept of Array. Element − Each item stored in an array is called an element.


How to declare an array?
dataType[] arrayName;

How to store primitive data types in an array?
it can be stored in array but not in array list.


How to store objects in an array?
Assigning values to an element in an array is similar to assigning values to scalar variables. Simply reference an individual element of an array using the array name and the index inside parentheses, then use the assignment operator (=) followed by a value.

How to retrieve primitive data from an array?
by get method.

Exercise:
In the StudentProfile Class which is already created as part of Day 1 exercise declare an array called marks[] to store 5 subject marks of the student.

Add a setter method that accepts marks[] and sets the values to the array. Clue here is you have to use a for loop in the setter method to process the parameter and assign the value to the marks[] in the class.

Note: It is not a good practise to use logics in constructor hence it is advised to use the setter method at this point. Later on advanced arrays we will come to know how to handle this operation in a simple manner.

Add a method called displayMarks() to show the marks.

From the main() call the setter and pass the marks[]
E.g stud1.setMarks(int[] marks)
Call stud1.displayMarks() and verify the values are shown correctly.
