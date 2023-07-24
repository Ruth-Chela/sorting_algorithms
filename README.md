For this project you are given the following print_array, and print_list functions:# sorting_algorithms
sorting algorithims and Big O team projects
At least four different sorting algorithms
What is the Big O notation, and how to evaluate the time complexity of an algorithm
How to select the best sorting algorithm for a given input
What is a stable sorting algorithm
The simplest definition I can give for Big-O notation is this:

Big-O notation is a relative representation of the complexity of an algorithm.

There are some important and deliberately chosen words in that sentence:

relative: you can only compare apples to apples. You can't compare an algorithm to do arithmetic multiplication to an algorithm that sorts a list of integers. But a comparison of two algorithms to do arithmetic operations (one multiplication, one addition) will tell you something meaningful; representation: Big-O (in its simplest form) reduces the comparison between algorithms to a single variable. That variable is chosen based on observations or assumptions. For example, sorting algorithms are typically compared based on comparison operations (comparing two nodes to determine their relative ordering). This assumes that comparison is expensive. But what if the comparison is cheap but swapping is expensive? It changes the comparison; and complexity: if it takes me one second to sort 10,000 elements, how long will it take me to sort one million? Complexity in this instance is a relative measure to something else.
Reference stackoverflow: What is a plain English explanation of “Big O” notation?

At least four different sorting algorithms
Bubble sort
Insertion sort
Selection sort
Quick sort
