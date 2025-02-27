Download link :https://programming.engineering/product/project-2-computing-eigenvalues-and-eigenvectors-using-normalized/


# Project-2-Computing-Eigenvalues-and-Eigenvectors-using-Normalized
Project 2: Computing Eigenvalues and Eigenvectors using Normalized
Power Iteration together with Deflation

Project Instructions:

For this project, you will work alone. No collaborations of any sort will be allowed with others. Any violation, regardless of the scope, will be directly referred to the department’s Ethical Commission.

You will submit your program (fully commented and documented) to Moodle. Late submission penalty is 20% for up to one week after the deadline. No credits will be given for late submissions beyond one week.

You will write in C/C++. You can use Dev-C++ as a compiler or any other compiler you wish. You can download Dev-C++ from: http://dev-c.en.malavida.com/

Your project will not only be graded on whether it works or not, but also on whether it has good programming style. Specifically, you are expected to use Object Oriented Programming concepts you learned in labs.

You should turn in:

– Source code: Fully commented. You should be explicit in your comments. An educated person reading your code should clearly understand the purpose of each line. Executable or object files are not accepted. The file name should be source.cpp

– A Readme file: A short file named readme.txt containing information regarding how to compile and run your program including the necessary arguments. If your program is incomplete, this should be indicated in the beginning of the Readme file.

Important: You should upload two files, named source.cpp and readme.txt. DO NOT upload .zip or .rar files, or you will be penalized. Project Goals:

In this project, you will be implementing the normalized power iteration algorithm together with deflation to find two eigenvalues and corresponding eigenvector for the dominant eigenvalue of a given matrix A, where A is a square matrix.

Your program should read A from an input file and output the dominant eigenvalue, its corresponding eigenvector and the next eigenvalue as a text file.

Example:

The file “A.txt” contains:

3.14 1.59 2.65 3.58

9.79 3.23 8.46 2.64

3.38 3.27 9.50 2.88

4.19 7.16 9.39 9.37

Tolerance is given as 1e-6.

Then the output file should contain:

Eigenvalue#1: 20.49

0.35

0.62

0.55

1.00

Eigenvalue#2: 3.91

Programming Details:

Your program should

have three command line arguments for the parameters. (Command line arguments can be thought of as the inputs of the main function.) The first argument is the name of the file you read the matrix from, the second argument is the tolerance, which will be used in the normalized power iteration algorithm, and the third argument is the name of your output file,

use dynamically allocated memory to store the matrix,

print out an error message and quit if it detects any problems,

calculate the eigenvalues and corresponding eigenvector and write them in a text file.


**********About Object Oriented Programming**********

In this project you will use matrices and matrix operations. In order to implement this project as an object oriented program; for example, you can declare a class (an object) named Matrix, and implement all matrix operations such as multiplication, addition, transpose, as methods of this class. This way, you don’t need to have a lot of complex loops in your program.
