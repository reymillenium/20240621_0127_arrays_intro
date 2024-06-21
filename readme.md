# COP 1334 Assignment - Introduction to C++

## Chapter 7: Arrays & Vectors

## Title: Arrays Intro

### Exercise Description:

Create a program that does the following:

Creates an integer array  of 10 numbers. Do not initialize

Fill array using a for loop that calls a function to get a value that gets put into the array

Use separate functions to get the following:

Sum of the elements

Average

Highest element using a for loop. Do not use max

## Execution from the Terminal (Alternative way without an IDE):

We must provide to the Compiler the same switches that we usually do in the IDE:

```terminal
g++ -Wall -std=c++17 main.cpp
```

That will create a file named 'a.out' if you are working in MacOS or a .exe file if you are on Windows. That's the default executable file's name when we don't provide a name.

But we can also specify the name of the resulting executable file:

```terminal
g++ -Wall -std=c++17 main.cpp -o your_prefered_executable_file_name
```

And in order to run that a.out file, we must execute on the terminal:

```terminal
 % ./a.out
```

## Result of Execution on the Terminal (MacOS example):

```terminal
reinier@reinier % ./your_prefered_executable_file_name

Please type a number (0 - 2147483647): 32
Please type a number (0 - 2147483647): 43
Please type a number (0 - 2147483647): 54
Please type a number (0 - 2147483647): 678
Please type a number (0 - 2147483647): 9789
Please type a number (0 - 2147483647): 34
Please type a number (0 - 2147483647): 343
Please type a number (0 - 2147483647): 34
Please type a number (0 - 2147483647): 34
Please type a number (0 - 2147483647): 2

The sum of the elements is 11,043
The average is 1,104.30
The highest element is 9,789
  
Process finished with exit code 0
reinier@reinier % 
```

### Author

**Reinier Garcia**

* [Github](https://github.com/reymillenium)
* [Twitter](https://twitter.com/ReinierGarciaR)
* [Linkedin](https://www.linkedin.com/in/reiniergarcia/)
* [Website](https://www.reiniergarcia.dev/)
* [Stack Overflow](https://stackoverflow.com/users/9616949/reinier-garcia)

### License

Copyright © 2024, [Reinier Garcia](https://github.com/reymillenium).


